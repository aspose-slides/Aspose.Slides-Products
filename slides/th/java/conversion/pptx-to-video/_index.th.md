---
title: แปลง PPTX เป็นวิดีโอใน Java
url: /th/java/conversion/pptx-to-video/
keywords: แปลง PPTX เป็นวิดีโอ, PPTX เป็นวิดีโอ, PowerPoint เป็นวิดีโอ, PPT เป็น MP4, Java API, Java Library
description: แปลง PPTX เป็นวิดีโอใน Java ใช้ Java library API เพื่อแปลง PowerPoint เป็นวิดีโอ
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง PPTX เป็นวิดีโอใน Java" h2="Java API ข้ามแพลตฟอร์มอันทรงพลังสำหรับการแปลง PowerPoint เป็นวิดีโอโดยใช้โค้ด Java" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง PowerPoint เป็นวิดีโอโดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ Java**](https://products.aspose.com/slides/th/java/) เป็นไลบรารี Java อันทรงพลังที่ใช้สร้าง แก้ไข และจัดการงานนำเสนอ และยังแปลงงานนำเสนอ PowerPoint เป็นเอกสารและวิดีโออื่นๆ . ในกรณีนี้ ในการแปลง PowerPoint เป็นวิดีโอ คุณต้องใช้ **Aspose.Slides** ควบคู่ไปกับ **ffmpeg**

นี่เป็นวิธีการทำงานของกระบวนการแปลง PPTX เป็นวิดีโอ: Aspose.Slides ใช้เพื่อสร้างชุดของเฟรม (จากสไลด์การนำเสนอ) จากนั้นใช้ FFMpegCore (ffmpeg) เพื่อสร้างวิดีโอตามเฟรม

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง PPTX เป็นวิดีโอ" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง **Aspose.Slides สำหรับ Java** โดยทำตามคำแนะนำ[ที่นี่](https://docs.aspose.com/slides/java/installation/) ดาวน์โหลด **ffmpeg** [ที่นี่](https://ffmpeg.org/download.html)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}

เพิ่มลงในไฟล์ POM ของคุณ:

```
   <การพึ่งพา>
     <groupId>net.bramp.ffmpeg</groupId>
     <artifactId>ffmpeg</artifactId>
     <เวอร์ชัน>0.7.0</เวอร์ชัน>
   </พึ่งพา>
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
คัดลอก วาง แล้วเรียกใช้โค้ด Java PowerPoint เป็นวิดีโอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{% blocks/products/pf/feature-page-section  h2="แปลง PowerPoint เป็นวิดีโอใน Java" %}}
ใช้รหัส Java นี้เพื่อแปลง PPTX เป็นวิดีโอ:

{{% blocks/products/pf/agp/code-block title="รหัส Java สำหรับการแปลง PowerPoint เป็นวิดีโอ" offSpacer="true" %}}
```java

Presentation presentation = new Presentation();
try {
    // Adds a smile shape and then animates it
    IAutoShape smile = presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.SmileyFace, 110, 20, 500, 500);
    ISequence mainSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
    IEffect effectIn = mainSequence.addEffect(smile, EffectType.Fly, EffectSubtype.TopLeft, EffectTriggerType.AfterPrevious);
    IEffect effectOut = mainSequence.addEffect(smile, EffectType.Fly, EffectSubtype.BottomRight, EffectTriggerType.AfterPrevious);
    effectIn.getTiming().setDuration(2f);
    effectOut.setPresetClassType(EffectPresetClassType.Exit);

    final int fps = 33;
    ArrayList<String> frames = new ArrayList<String>();

    PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation);
    try
    {
        PresentationPlayer player = new PresentationPlayer(animationsGenerator, fps);
        try {
            player.setFrameTick((sender, arguments) ->
            {
                try {
                    String frame = String.format("frame_%04d.png", sender.getFrameIndex());
                    ImageIO.write(arguments.getFrame(), "PNG", new java.io.File(frame));
                    frames.add(frame);
                } catch (IOException e) {
                    throw new RuntimeException(e);
                }
            });
            animationsGenerator.run(presentation.getSlides());
        } finally {
            if (player != null) player.dispose();
        }
    } finally {
        if (animationsGenerator != null) animationsGenerator.dispose();
    }

    // Configure ffmpeg binaries folder. See this page: https://github.com/rosenbjerg/FFMpegCore#installation
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
} catch (IOException e) {
    e.printStackTrace();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PowerPoint เป็นไฟล์ในรูปแบบอื่นๆ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-word/" name="PPTX TO WORD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}