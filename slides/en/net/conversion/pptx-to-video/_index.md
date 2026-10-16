---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to Video in C#
url: /net/conversion/pptx-to-video/
keywords: Convert PPTX to video, PPTX to video, PowerPoint to video, PPTX to MP4, C# API, .NET Library
description: Convert PPTX to video in C#. Use Aspose.Slides for .NET with FFmpeg to render PowerPoint slides as video frames.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTX to Video in C#" h2="Render PowerPoint slides to video frames in C# using Aspose.Slides for .NET and FFmpeg." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PowerPoint to Video in C#" variant="code" %}}

Use this code to convert PPTX to video:

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# code for converting PowerPoint to video" >}}
```cs
using Aspose.Slides;
using Aspose.Slides.Export;
using FFMpegCore;
using System.Collections.Generic;

const int framesPerSecond = 30;
var framePaths = new List<string>();

using var presentation = new Presentation("template.pptx");
using var animationsGenerator = new PresentationAnimationsGenerator(presentation);
using var player = new PresentationPlayer(animationsGenerator, framesPerSecond);

player.FrameTick += (presentationPlayer, frameArguments) =>
{
    var framePath = $"frame_{presentationPlayer.FrameIndex:D4}.png";
    using var frame = frameArguments.GetFrame();
    frame.Save(framePath);
    framePaths.Add(framePath);
};

animationsGenerator.Run(presentation.Slides);

GlobalFFOptions.Configure(new FFOptions { BinaryFolder = @"c:\tools\ffmpeg\bin" });
FFMpeg.JoinImageSequence("presentation.webm", framesPerSecond, framePaths.ToArray());
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PowerPoint to Video Using Aspose.Slides" %}}

[Aspose.Slides for .NET](/slides/net/) can render PowerPoint presentations to image frames. To create a video, render frames with `PresentationAnimationsGenerator` and `PresentationPlayer`, then pass those frames to `ffmpeg` through `FFMpegCore`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PPTX to Video" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install `Aspose.Slides.NET` and `FFMpegCore` packages.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Download `ffmpeg` from [ffmpeg.org](https://ffmpeg.org/download.html).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure `GlobalFFOptions` with the `ffmpeg` binary folder.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use `PresentationAnimationsGenerator` and `PresentationPlayer` to render frames, then call `FFMpeg.JoinImageSequence`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
