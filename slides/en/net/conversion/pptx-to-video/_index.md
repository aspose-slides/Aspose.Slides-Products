---
title: Convert PPTX to Video in C#
url: /net/conversion/pptx-to-video/
keywords: Convert PPTX to video, PPTX to video, PowerPoint to video, PPTX to MP4, C# API, .NET Library
description: Convert PPTX to video in C#. Use Aspose.Slides for .NET with FFmpeg to render PowerPoint slides as video frames.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTX to Video in C#" h2="Render PowerPoint slides to video frames in C# using Aspose.Slides for .NET and FFmpeg." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Video Using Aspose.Slides" %}}

[Aspose.Slides for .NET](/slides/net/) can render PowerPoint presentations to image frames. To create a video, render frames with `PresentationAnimationsGenerator` and `PresentationPlayer`, then pass those frames to `ffmpeg` through `FFMpegCore`.

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Convert PPTX to Video" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install `Aspose.Slides.NET` and `FFMpegCore` packages.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Download `ffmpeg` from [ffmpeg.org](https://ffmpeg.org/download.html).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Configure `GlobalFFOptions` with the `ffmpeg` binary folder.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Use `PresentationAnimationsGenerator` and `PresentationPlayer` to render frames, then call `FFMpeg.JoinImageSequence`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< blocks/products/pf/feature-page-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert PowerPoint to Video in C#" %}}
Use this code to convert PPTX to video:

{{% blocks/products/pf/agp/code-block title="C# code for converting PowerPoint to video" offSpacer="true" %}}
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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Bitmap Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-emf/" name="PPTX TO EMF" description="Enhanced Metafile Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Graphics Interchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hypertext Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="JPEG Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument Presentation Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument Presentation Template" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Portable Document Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-png/" name="PPTX TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-pot/" name="PPTX TO POT" description="PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-potm/" name="PPTX TO POTM" description="PowerPoint Macro-Enabled Template" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-potx/" name="PPTX TO POTX" description="PowerPoint Open XML Template" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Macro-Enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="PowerPoint Open XML Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="PowerPoint 97-2003 Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Macro-Enabled Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Scalable Vector Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWF Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Tagged Image File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-word/" name="PPTX TO WORD" description="Word Processing Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML Paper Specification" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
