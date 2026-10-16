---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX'i Java'da Videoya Dönüştür
url: /tr/java/conversion/pptx-to-video/
keywords: PPTX'i videoya, PPTX'i videoya, PowerPoint'i videoya, PPT'yi MP4'e, Java API'sini, Java Kitaplığını dönüştürün
description: Java'da PPTX'i videoya dönüştürün. PowerPoint'i videoya dönüştürmek için Java kitaplığı API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX'i Java'da videoya dönüştürün" h2="Java kodunu kullanarak PowerPoint'i videoya dönüştürmek için güçlü platformlar arası Java API'si" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java'da PowerPoint'i videoya dönüştürün" variant="code" %}}

PPTX'i videoya dönüştürmek için bu Java kodunu kullanın:

{{< blocks/products/pf/slides-design-update-10-2026/code title="PowerPoint'i videoya dönüştürmek için Java kodu" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides kullanarak PowerPoint'i videoya dönüştürün" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/), sunumlar oluşturmak, düzenlemek ve değiştirmek ve ayrıca PowerPoint sunumlarını diğer belgelere ve videolara dönüştürmek için kullanılan güçlü bir Java kitaplığıdır. . Bu durumda, PowerPoint'i videoya dönüştürmek için **ffmpeg** ile birlikte **Aspose.Slides** kullanmanız gerekir.

PPTX'ten videoya dönüştürme işlemi şu şekilde çalışır: Aspose.Slides, bir dizi kare (sunum slaytlarından) oluşturmak için kullanılır ve ardından, karelere dayalı bir video oluşturmak için FFMpegCore (ffmpeg) kullanılır.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPTX'i videoya dönüştürme yöntemi" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for Java**'yı [buradaki](https://docs.aspose.com/slides/java/installation/) talimatları izleyerek kurun. **ffmpeg**'i [buradan] indirin(https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Bunu POM dosyanıza ekleyin:

```
   <bağımlılık>
     <groupId>net.bramp.ffmpeg</groupId>
     <artifactId>ffmpeg</artifactId>
     <version>0.7.0</version>
   </bağımlılık>
```{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Java PowerPoint to video kodunu kopyalayın, yapıştırın ve çalıştırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Dönüşümler" subTitle="PowerPoint'i başka biçimlerdeki dosyalara da dönüştürebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptx-to-word/" name="PPTX TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
