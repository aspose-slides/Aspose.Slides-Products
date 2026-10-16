---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie PPT in Video in C++
url: /de/cpp/conversion/ppt-to-video/
keywords: Konvertieren Sie PPT in Video, PPT in Video, PowerPoint in Video, PPT in MP4, C++-API, C++-Bibliothek
description: Konvertieren Sie PPT in Video in C++. Verwenden Sie die C++-Bibliotheks-API, um PowerPoint in Video zu konvertieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie PPT in Video in C++" h2="Leistungsstarke plattformübergreifende C++-API zum Konvertieren von PowerPoint in Videos mithilfe von C++-Code" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie PowerPoint in C++ in ein Video" variant="code" %}}

Verwenden Sie diesen C++-Code, um PPT in Video zu konvertieren:

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++-Code zum Konvertieren von PowerPoint in Video" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie PowerPoint mit Aspose.Slides in ein Video" %}}

[**Aspose.Slides für C++**](https://products.aspose.com/slides/de/cpp/) ist eine leistungsstarke C++-Bibliothek, die zum Erstellen, Bearbeiten und Bearbeiten von Präsentationen sowie zum Konvertieren von PowerPoint-Präsentationen in andere Dokumente und Videos verwendet wird . In diesem Fall müssen Sie zum Konvertieren von PowerPoint in Video **Aspose.Slides** neben **ffmpeg** verwenden.

So funktioniert der PPT-zu-Video-Konvertierungsprozess: Aspose.Slides wird verwendet, um eine Reihe von Frames (aus den Präsentationsfolien) zu generieren, und dann wird FFMpegCore (ffmpeg) verwendet, um ein Video basierend auf den Frames zu erstellen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie PPT in Video" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie **Aspose.Slides für C++**, indem Sie den Anweisungen [hier](https://docs.aspose.com/slides/cpp/installation/) folgen. Laden Sie **ffmpeg** [hier] herunter.(https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie den Pfad zu „ffmpeg.exe“ zur Umgebungsvariablen „PATH“ hinzu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kopieren Sie den C++ PowerPoint to Video-Code, fügen Sie ihn ein und führen Sie ihn dann aus.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere unterstützte Konvertierungen" subTitle="Sie können PowerPoint auch in Dateien in anderen Formaten konvertieren" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
