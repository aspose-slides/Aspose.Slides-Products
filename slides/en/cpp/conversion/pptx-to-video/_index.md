---
title: Convert PPTX to Video in C++
url: /cpp/conversion/pptx-to-video/
keywords: Convert PPTX to video, PPTX to video, PowerPoint to video, PPTX to MP4, C++ API, C++ Library
description: Convert PPTX to video in C++. Use Aspose.Slides for C++ with ffmpeg to render PowerPoint slides to video frames and create a video file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTX to Video in C++" h2="Create video from PowerPoint slides using Aspose.Slides for C++ and ffmpeg." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Video Using Aspose.Slides" %}}

[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) can render PowerPoint presentations to image frames. To create a video, render frames with `PresentationAnimationsGenerator` and `PresentationPlayer`, then pass those frames to `ffmpeg`.

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section h2="How to Convert PPTX to Video" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install `Aspose.Slides for C++` from [NuGet](https://www.nuget.org/packages/Aspose.Slides.Cpp/) or the [releases page](https://releases.aspose.com/slides/cpp/), and install `ffmpeg` from the [ffmpeg download page](https://ffmpeg.org/download.html).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add `ffmpeg.exe` to the `PATH` environment variable.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Run the C++ code to render PPTX frames and create an MP4 video.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Video in C++" %}}

Use this C++ code to convert PPTX to video:

{{% blocks/products/pf/agp/code-block title="PPTX to Video C++ Conversion Source Code" offSpacer="true" %}}

```cpp
void SaveFrame(System::SharedPtr<PresentationPlayer> presentationPlayer, System::SharedPtr<FrameTickEventArgs> eventArguments)
{
    auto frameFileName = String::Format(u"frame_{0}.png", presentationPlayer->get_FrameIndex());
    eventArguments->GetFrame()->Save(frameFileName);
}

void Run()
{
    auto presentation = MakeObject<Presentation>(u"presentation.pptx");

    const int framesPerSecond = 33;
    auto animationsGenerator = MakeObject<PresentationAnimationsGenerator>(presentation);
    auto player = MakeObject<PresentationPlayer>(animationsGenerator, framesPerSecond);
    player->FrameTick += SaveFrame;

    animationsGenerator->Run(presentation->get_Slides());

    auto ffmpegParameters = String::Format(
        u"-loglevel {0} -framerate {1} -i {2} -y -c:v {3} -pix_fmt {4} {5}",
        u"warning", framesPerSecond, u"frame_%d.png", u"libx264", u"yuv420p", u"video.mp4");
    auto ffmpegProcess = Process::Start(u"ffmpeg", ffmpegParameters);
    ffmpegProcess->WaitForExit();

    presentation->Dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-word/" name="PPTX TO WORD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}