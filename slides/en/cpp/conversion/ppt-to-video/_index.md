---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPT to Video in C++
url: /cpp/conversion/ppt-to-video/
keywords: Convert PPT to video, PPT to video, PowerPoint to video, PPT to MP4, C++ API, C++ Library
description: Convert PPT to video in C++. Use Aspose.Slides for C++ with ffmpeg to render PowerPoint slides to video frames and create a video file.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPT to Video in C++" h2="Create video from PowerPoint slides using Aspose.Slides for C++ and ffmpeg." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PowerPoint to Video in C++" variant="code" %}}

Use this C++ code to convert PPT to video:

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT to Video C++ Conversion Source Code" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PowerPoint to Video Using Aspose.Slides" %}}

[Aspose.Slides for C++](/slides/cpp/) can render PowerPoint presentations to image frames. To create a video, render frames with `PresentationAnimationsGenerator` and `PresentationPlayer`, then pass those frames to `ffmpeg`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PPT to Video" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install `Aspose.Slides for C++` from [NuGet](https://www.nuget.org/packages/Aspose.Slides.Cpp/) or the [releases page](https://releases.aspose.com/slides/cpp/), and install `ffmpeg` from the [ffmpeg download page](https://ffmpeg.org/download.html).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add `ffmpeg.exe` to the `PATH` environment variable.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Run the C++ code to render PPT frames and create an MP4 video.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
