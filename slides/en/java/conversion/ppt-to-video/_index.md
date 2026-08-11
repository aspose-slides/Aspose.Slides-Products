---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPT to Video in Java
url: /java/conversion/ppt-to-video/
keywords: Convert PPT to video, PPT to video, PowerPoint to video, PPT to MP4, Java API, Java Library
description: Convert PPT to video in Java. Use Aspose.Slides for Java and ffmpeg to render PowerPoint slides as video frames and assemble them into a video file.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT to video in Java" h2="Render PowerPoint slides to video frames and assemble them into a video file using Java code" >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to video using Aspose.Slides" %}}

[Aspose.Slides for Java](/slides/java/) can render PowerPoint presentations to image frames. To create a video, render frames with `PresentationAnimationsGenerator` and `PresentationPlayer`, then pass those frames to `ffmpeg`.

This `PPT` to video workflow uses Aspose.Slides to generate presentation frames and the Java `ffmpeg` wrapper to assemble the frames into a video file.

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPT to video" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) and download [ffmpeg](https://ffmpeg.org/download.html).
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}

Add this dependency to your `pom.xml` file:

```xml
<dependency>
    <groupId>net.bramp.ffmpeg</groupId>
    <artifactId>ffmpeg</artifactId>
    <version>0.7.0</version>
</dependency>
```

{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Run the Java PowerPoint to video code.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert PowerPoint to video in Java" %}}
Use this Java code to convert `PPT` to video:

{{% blocks/products/pf/agp/code-block title="Java code for converting PowerPoint to video" offSpacer="true" %}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    final int framesPerSecond = 30;

    PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation);
    try {
        PresentationPlayer presentationPlayer = new PresentationPlayer(animationsGenerator, framesPerSecond);
        try {
            presentationPlayer.setFrameTick((sender, arguments) -> {
                String framePath = String.format("frame_%04d.png", sender.getFrameIndex());
                arguments.getFrame().save(framePath);
            });
            animationsGenerator.run(presentation.getSlides());
        } finally {
            presentationPlayer.dispose();
        }
    } finally {
        animationsGenerator.dispose();
    }

    FFmpeg ffmpeg = new FFmpeg("path/to/ffmpeg");
    FFprobe ffprobe = new FFprobe("path/to/ffprobe");

    FFmpegBuilder builder = new FFmpegBuilder()
            .addExtraArgs("-start_number", "1")
            .setInput("frame_%04d.png")
            .addOutput("output.avi")
            .setVideoFrameRate(FFmpeg.FPS_24)
            .setFormat("avi")
            .done();

    FFmpegExecutor executor = new FFmpegExecutor(ffmpeg, ffprobe);
    executor.createJob(builder).run();
} finally {
    presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/ppt-to-tiff/" name="PPT TO TIFF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
