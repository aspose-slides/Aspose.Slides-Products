---
title: Convert PPT to Video in C++
url: /cpp/conversion/ppt-to-video/
keywords: Convert PPT to video, PPT to video, PowerPoint to video, PPT to MP4, C++ API, C++ Library
description: Convert PPT to video in C++. Use Aspose.Slides for C++ with ffmpeg to render PowerPoint slides to video frames and create a video file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT to Video in C++" h2="Create video from PowerPoint slides using Aspose.Slides for C++ and ffmpeg." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Video Using Aspose.Slides" %}}

[Aspose.Slides for C++](/slides/cpp/) can render PowerPoint presentations to image frames. To create a video, render frames with `PresentationAnimationsGenerator` and `PresentationPlayer`, then pass those frames to `ffmpeg`.

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section h2="How to Convert PPT to Video" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install `Aspose.Slides for C++` from [NuGet](https://www.nuget.org/packages/Aspose.Slides.Cpp/) or the [releases page](https://releases.aspose.com/slides/cpp/), and install `ffmpeg` from the [ffmpeg download page](https://ffmpeg.org/download.html).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Add `ffmpeg.exe` to the `PATH` environment variable.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Run the C++ code to render PPT frames and create an MP4 video.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Video in C++" %}}

Use this C++ code to convert PPT to video:

{{% blocks/products/pf/agp/code-block title="PPT to Video C++ Conversion Source Code" offSpacer="true" %}}

```cpp
void SaveFrame(System::SharedPtr<PresentationPlayer> presentationPlayer, System::SharedPtr<FrameTickEventArgs> eventArguments)
{
    auto frameFileName = String::Format(u"frame_{0}.png", presentationPlayer->get_FrameIndex());
    eventArguments->GetFrame()->Save(frameFileName);
}

void Run()
{
    auto presentation = MakeObject<Presentation>(u"presentation.ppt");

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

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}