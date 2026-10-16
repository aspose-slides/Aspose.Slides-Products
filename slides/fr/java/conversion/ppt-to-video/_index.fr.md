---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PPT en vidéo en Java
url: /fr/java/conversion/ppt-to-video/
keywords: Convertir PPT en vidéo, PPT en vidéo, PowerPoint en vidéo, PPT en MP4, Java API, Java Library
description: Convertir PPT en vidéo en Java. Utiliser l'API de la bibliothèque Java pour convertir PowerPoint en vidéo
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PPT en vidéo en Java" h2="API Java multiplateforme puissante pour convertir PowerPoint en vidéo à l'aide de code Java" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PowerPoint en vidéo en Java" variant="code" %}}

Utilisez ce code Java pour convertir PPT en vidéo :

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code Java pour convertir PowerPoint en vidéo" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PowerPoint en vidéo à l'aide d'Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/fr/java/) est une puissante bibliothèque Java utilisée pour créer, éditer et manipuler des présentations et également convertir des présentations PowerPoint en d'autres documents et vidéos . Dans ce cas, pour convertir PowerPoint en vidéo, vous devez utiliser **Aspose.Slides** avec **ffmpeg**.

Voici comment fonctionne le processus de conversion PPT en vidéo : Aspose.Slides est utilisé pour générer un ensemble d'images (à partir des diapositives de présentation), puis FFMpegCore (ffmpeg) est utilisé pour créer une vidéo basée sur les images.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir PPT en vidéo" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez **Aspose.Slides pour Java** en suivant les instructions [ici](https://docs.aspose.com/slides/java/installation/). Téléchargez **ffmpeg** [ici.](https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez ceci à votre fichier POM :

```
   <dépendance>
     <groupId>net.bramp.ffmpeg</groupId>
     <artifactId>ffmpeg</artifactId>
     <version>0.7.0</version>
   </dépendance>
```{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Copiez, collez, puis exécutez le code Java PowerPoint vers vidéo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir PowerPoint en fichiers dans d'autres formats" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
