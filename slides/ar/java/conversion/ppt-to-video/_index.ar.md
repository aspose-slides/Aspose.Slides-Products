---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل PPT إلى فيديو بجافا
url: /ar/java/conversion/ppt-to-video/
keywords: تحويل PPT إلى فيديو ، PPT إلى فيديو ، PowerPoint إلى فيديو ، PPT إلى MP4 ، Java API ، مكتبة Java
description: تحويل PPT إلى فيديو بجافا. استخدم Java Library API لتحويل PowerPoint إلى فيديو
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل PPT إلى فيديو بجافا" h2="واجهة برمجة تطبيقات Java قوية ومتعددة المنصات لتحويل PowerPoint إلى فيديو باستخدام كود Java" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PowerPoint إلى فيديو بجافا" variant="code" %}}

استخدم كود Java هذا لتحويل PPT إلى فيديو:

{{< blocks/products/pf/slides-design-update-10-2026/code title="كود جافا لتحويل PowerPoint إلى فيديو" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PowerPoint إلى فيديو باستخدام Aspose.Slides" %}}

[** Aspose.Slides for Java **](https://products.aspose.com/slides/ar/java/) هي مكتبة Java قوية تُستخدم لإنشاء العروض التقديمية وتعديلها ومعالجتها وكذلك تحويل عروض PowerPoint التقديمية إلى مستندات ومقاطع فيديو أخرى . في هذه الحالة ، لتحويل PowerPoint إلى فيديو ، تحتاج إلى استخدام ** Aspose.Slides ** بجانب ** ffmpeg **.

هذه هي الطريقة التي تعمل بها عملية تحويل PPT إلى فيديو: Aspose.Slides تستخدم لإنشاء مجموعة من الإطارات (من شرائح العرض التقديمي) ثم FFMpegCore (ffmpeg) تُستخدم لإنشاء فيديو على أساس الإطارات.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل PPT إلى فيديو" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت ** Aspose.Slides for Java ** باتباع التعليمات [هنا](https://docs.aspose.com/slides/java/installation/). تنزيل ** ffmpeg ** [هنا.](https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}أضف هذا إلى ملف POM الخاص بك:

""
   <الاعتماد>
     <groupId> net.bramp.ffmpeg </groupId>
     <artifactId> ffmpeg </artifactId>
     <الإصدار> 0.7.0 </version>
   <الاعتماد>
""{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}انسخ والصق ثم قم بتشغيل Java PowerPoint إلى رمز الفيديو.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PowerPoint إلى ملفات بتنسيقات أخرى" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
