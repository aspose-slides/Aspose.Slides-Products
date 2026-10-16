---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter PPT para Vídeo em C#
url: /pt/net/conversion/ppt-to-video/
keywords: Converta PPT para vídeo, PPT para vídeo, PowerPoint para vídeo, PPT para MP4, C# API, Biblioteca .NET
description: Converta PPT para vídeo em C#. Use a API da biblioteca .NET para converter PowerPoint em vídeo
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converter PPT para vídeo em C#" h2="Poderosa API .NET multiplataforma para converter PowerPoint em vídeo usando código C# em plataformas NET Framework, .NET Core, Windows Azure, Mono ou Xamarin" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter PowerPoint para vídeo em C#" variant="code" %}}

Use este código para converter PPT em vídeo:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código C# para converter PowerPoint em vídeo" >}}
```cs

using System.Collections.Generic;
using Aspose.Slides;
using FFMpegCore; // Will use FFmpeg binaries we extracted to "c:\tools\ffmpeg" before
using Aspose.Slides.Animation;
using (Presentation presentation = new Presentation())

{
    // Adds a smile shape and then animates it
    IAutoShape smile = presentation.Slides[0].Shapes.AddAutoShape(ShapeType.SmileyFace, 110, 20, 500, 500);
    IEffect effectIn = presentation.Slides[0].Timeline.MainSequence.AddEffect(smile, EffectType.Fly, EffectSubtype.TopLeft, EffectTriggerType.AfterPrevious);
    IEffect effectOut = presentation.Slides[0].Timeline.MainSequence.AddEffect(smile, EffectType.Fly, EffectSubtype.BottomRight, EffectTriggerType.AfterPrevious);
    effectIn.Timing.Duration = 2f;
    effectOut.PresetClassType = EffectPresetClassType.Exit;

   const int Fps = 33;
   List<string> frames = new List<string>();

   using (var animationsGenerator = new PresentationAnimationsGenerator(presentation))
    using (var player = new PresentationPlayer(animationsGenerator, Fps))
    {
        player.FrameTick += (sender, args) =>
        {
            string frame = $"frame_{(sender.FrameIndex):D4}.png";
            args.GetFrame().Save(frame);
            frames.Add(frame);
        };
        animationsGenerator.Run(presentation.Slides);
    }

    // Configure ffmpeg binaries folder. See this page: https://github.com/rosenbjerg/FFMpegCore#installation
    GlobalFFOptions.Configure(new FFOptions { BinaryFolder = @"c:\tools\ffmpeg\bin", });
    // Converts frames to webm video
    FFMpeg.JoinImageSequence("smile.webm", Fps, frames.Select(frame => ImageInfo.FromPath(frame)).ToArray());

}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter PowerPoint para vídeo usando Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/pt/net/) é uma poderosa biblioteca .NET usada para criar, editar e manipular apresentações e também converter apresentações do PowerPoint em outros documentos e vídeos. Nesse caso, para converter PowerPoint em vídeo, você precisa usar **Aspose.Slides** juntamente com **ffmpeg** e **FFMpegCore** (um NET ffmpeg wrapper gratuito).

É assim que o processo de conversão de PPT para vídeo funciona: Aspose.Slides é usado para gerar um conjunto de quadros (a partir dos slides da apresentação) e então o FFMpegCore (ffmpeg) é usado para criar um vídeo baseado nos quadros.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como converter PPT para vídeo" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale **Aspose.Slides para .NET** e **FFMpegcore**: Execute `dotnet add package Aspose.Slides.NET --version 22.12.0` e então execute `dotnet add package FFMpegCore --version 4.8.0`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Baixe o ffmpeg [aqui.](https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}FFMpegCore requer que você especifique o caminho para o ffmpeg baixado (por exemplo, extraído para “C:\tools\ffmpeg”): `GlobalFFOptions.Configure(new FFOptions { BinaryFolder = @"c:\tools\ffmpeg\bin",} ); `{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Copie, cole e execute o PowerPoint para código de vídeo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outras conversões compatíveis" subTitle="Você também pode converter PowerPoint para arquivos em outros formatos" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
