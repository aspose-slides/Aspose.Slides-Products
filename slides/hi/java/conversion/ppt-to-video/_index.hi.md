---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: जावा में पीपीटी को वीडियो में बदलें
url: /hi/java/conversion/ppt-to-video/
keywords: PPT को वीडियो में, PPT को वीडियो में, PowerPoint को वीडियो में, PPT को MP4 में, Java API, Java लाइब्रेरी में कनवर्ट करें
description: जावा में पीपीटी को वीडियो में बदलें। PowerPoint को वीडियो में बदलने के लिए Java लाइब्रेरी API का उपयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="जावा में पीपीटी को वीडियो में बदलें" h2="जावा कोड का उपयोग करके PowerPoint को वीडियो में बदलने के लिए शक्तिशाली क्रॉस-प्लेटफ़ॉर्म Java API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="जावा में PowerPoint को वीडियो में कनवर्ट करें" variant="code" %}}

पीपीटी को वीडियो में बदलने के लिए इस जावा कोड का प्रयोग करें:

{{< blocks/products/pf/slides-design-update-10-2026/code title="PowerPoint को वीडियो में बदलने के लिए जावा कोड" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides का उपयोग करके PowerPoint को वीडियो में बदलें" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hi/java/) एक शक्तिशाली जावा लाइब्रेरी है जिसका उपयोग प्रस्तुतियों को बनाने, संपादित करने और हेरफेर करने और PowerPoint प्रस्तुतियों को अन्य दस्तावेज़ों और वीडियो में बदलने के लिए किया जाता है . इस स्थिति में, PowerPoint को वीडियो में बदलने के लिए, आपको **Fmpeg** के साथ **Aspose.Slides** का उपयोग करना होगा।

पीपीटी से वीडियो रूपांतरण प्रक्रिया इस प्रकार काम करती है: Aspose.Slides का उपयोग फ्रेम का एक सेट (प्रस्तुति स्लाइड से) उत्पन्न करने के लिए किया जाता है और फिर FFMpegCore (ffmpeg) का उपयोग फ्रेम के आधार पर वीडियो बनाने के लिए किया जाता है।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="पीपीटी को वीडियो में कैसे बदलें" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[यहाँ](https://docs.aspose.com/slides/java/installation/) निर्देशों का पालन करके **Aspose.Slides for Java** इंस्टॉल करें। डाउनलोड **Ffmpeg** [यहां।](https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}इसे अपनी पीओएम फ़ाइल में जोड़ें:

```
   <निर्भरता>
     <groupId>net.bramp.ffmpeg</groupId>
     <artifactId>ffmpeg</artifactId>
     <संस्करण>0.7.0</संस्करण>
   </निर्भरता>
```{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रतिलिपि बनाएँ, चिपकाएँ, और फिर Java PowerPoint को वीडियो कोड में चलाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित रूपांतरण" subTitle="आप PowerPoint को अन्य स्वरूपों में फ़ाइलों में भी रूपांतरित कर सकते हैं" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
