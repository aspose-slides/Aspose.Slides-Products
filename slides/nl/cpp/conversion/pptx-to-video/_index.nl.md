---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer PPTX naar video in C++
url: /nl/cpp/conversion/pptx-to-video/
keywords: Converteer PPTX naar video, PPTX naar video, PowerPoint naar video, PPTX naar MP4, C++ API, C++ bibliotheek
description: Converteer PPTX naar video in C++. Gebruik de C++-bibliotheek-API om PowerPoint naar video te converteren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer PPTX naar video in C++" h2="Krachtige platformonafhankelijke C++ API voor het converteren van PowerPoint naar video met behulp van C++-code" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PowerPoint naar video in C++" variant="code" %}}

Gebruik deze C++-code om PPTX naar video te converteren:

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++-code voor het converteren van PowerPoint naar video" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer PowerPoint naar video met behulp van Aspose.Slides" %}}

[**Aspose.Slides voor C++**](https://products.aspose.com/slides/nl/cpp/) is een krachtige C++-bibliotheek die wordt gebruikt voor het maken, bewerken en manipuleren van presentaties en ook voor het converteren van PowerPoint-presentaties naar andere documenten en video's . In dit geval moet u **Aspose.Slides** naast **ffmpeg** gebruiken om PowerPoint naar video te converteren.

Dit is hoe het conversieproces van PPTX naar video werkt: Aspose.Slides wordt gebruikt om een ​​set frames te genereren (van de presentatiedia's) en vervolgens wordt FFMpegCore (ffmpeg) gebruikt om een ​​video te maken op basis van de frames.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe PPTX naar video te converteren" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer **Aspose.Slides voor C++** door de instructies [hier](https://docs.aspose.com/slides/cpp/installation/) te volgen. Download **ffmpeg** [hier.](https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pad naar `ffmpeg.exe` toevoegen aan omgevingsvariabele `PATH`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kopieer, plak en voer vervolgens de C++ PowerPoint-naar-videocode uit.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere ondersteunde conversies" subTitle="U kunt PowerPoint ook converteren naar bestanden in andere formaten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/pptx-to-word/" name="PPTX TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
