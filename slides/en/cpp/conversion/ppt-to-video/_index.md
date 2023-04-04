---
title:  Convert PPT to Video in C++
url: /cpp/conversion/ppt-to-video/
keywords: Convert PPT to video, PPT to video, PowerPoint to video, C++ API, C++ Library
description: Convert PPT to video in C++. Use C++ library API to convert PowerPoint to video
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT to video in C++" h2="Powerful cross-platform C++ API for converting PowerPoint to video using C++ code" >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to video using Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/cpp/) is a powerful C++ library used to create, edit and manipulate presentations and also convert PowerPoint presentations to other documents and videos. In this case, to convert PowerPoint to video, you need to use **Aspose.Slides** alongside **ffmpeg**. 

This is how the PPT to video conversion process works: Aspose.Slides is used to generate a set of frames (from the presentation slides) and then FFMpegCore (ffmpeg) is used to create a video based on the frames.

{{% /blocks/products/pf/feature-page-section %}}



{{< blocks/products/pf/feature-page-section  h2="How to convert PPT to video" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for C++** by following the instructions [here](https://docs.aspose.com/slides/cpp/installation/). Download **ffmpeg** [here.](https://ffmpeg.org/download.html)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}

Add path to `ffmpeg.exe` to environment variable `PATH`.

{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Copy, paste, and then run the C++ PowerPoint to video code.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}



{{% blocks/products/pf/feature-page-section  h2="Convert PowerPoint to video in C++" %}}
Use this C++ code to convert PPT to video:

{{% blocks/products/pf/agp/code-block title="C++ code for converting PowerPoint to video" offSpacer="true" %}}
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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}