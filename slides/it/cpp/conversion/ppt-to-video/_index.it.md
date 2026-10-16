---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti PPT in video in C++
url: /it/cpp/conversion/ppt-to-video/
keywords: Converti PPT in video, PPT in video, PowerPoint in video, PPT in MP4, API C++, Libreria C++
description: Converti PPT in video in C++. Usa l'API della libreria C++ per convertire PowerPoint in video
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti PPT in video in C++" h2="Potente API C++ multipiattaforma per convertire PowerPoint in video utilizzando il codice C++" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti PowerPoint in video in C++" variant="code" %}}

Usa questo codice C++ per convertire PPT in video:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Codice C++ per convertire PowerPoint in video" >}}
```c++

void OnFrameTick(System::SharedPtr<PresentationPlayer> sender, System::SharedPtr<FrameTickEventArgs> args)
{
    System::String fileName = System::String::Format(u"frame_{0}.png", sender->get_FrameIndex());
    args->GetFrame()->Save(fileName);
}

void Run()
{
    auto presentation = System::MakeObject<Presentation>();
    auto slide = presentation->get_Slide(0);

    // Adds a smile shape and then animates it
    System::SharedPtr<IAutoShape> smile = slide->get_Shapes()->AddAutoShape(ShapeType::SmileyFace, 110.0f, 20.0f, 500.0f, 500.0f);
    auto sequence = slide->get_Timeline()->get_MainSequence();
    System::SharedPtr<IEffect> effectIn = sequence->AddEffect(smile, EffectType::Fly, EffectSubtype::TopLeft, EffectTriggerType::AfterPrevious);
    System::SharedPtr<IEffect> effectOut = sequence->AddEffect(smile, EffectType::Fly, EffectSubtype::BottomRight, EffectTriggerType::AfterPrevious);
    effectIn->get_Timing()->set_Duration(2.0f);
    effectOut->set_PresetClassType(EffectPresetClassType::Exit);

    const int32_t fps = 33;

    auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation);
    auto player = System::MakeObject<PresentationPlayer>(animationsGenerator, fps);
    player->FrameTick += OnFrameTick;
    animationsGenerator->Run(presentation->get_Slides());

    const System::String ffmpegParameters = System::String::Format(
        u"-loglevel {0} -framerate {1} -i {2} -y -c:v {3} -pix_fmt {4} {5}",
        u"warning", m_fps, "frame_%d.png", u"libx264", u"yuv420p", "video.mp4");
    auto ffmpegProcess = System::Diagnostics::Process::Start(u"ffmpeg", ffmpegParameters);
    ffmpegProcess->WaitForExit();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti PowerPoint in video utilizzando Aspose.Slides" %}}

[**Aspose.Slides per C++**](https://products.aspose.com/slides/it/cpp/) è una potente libreria C++ utilizzata per creare, modificare e manipolare presentazioni e anche convertire presentazioni PowerPoint in altri documenti e video . In questo caso, per convertire PowerPoint in video, devi utilizzare **Aspose.Slides** insieme a **ffmpeg**.

Ecco come funziona il processo di conversione da PPT a video: Aspose.Slides viene utilizzato per generare un set di frame (dalle diapositive della presentazione) e quindi FFMpegCore (ffmpeg) viene utilizzato per creare un video basato sui frame.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come convertire PPT in video" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa **Aspose.Slides per C++** seguendo le istruzioni [qui](https://docs.aspose.com/slides/cpp/installation/). Scarica **ffmpeg** [qui.](https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Aggiungi il percorso a `ffmpeg.exe` alla variabile d'ambiente `PATH`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Copia, incolla e quindi esegui PowerPoint C++ nel codice video.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altre conversioni supportate" subTitle="Puoi anche convertire PowerPoint in file in altri formati" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
