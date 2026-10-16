---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX'i C# ile Videoya Dönüştür
url: /tr/net/conversion/pptx-to-video/
keywords: PPTX'i videoya, PPTX'i videoya, PowerPoint'i videoya, PPTX'i MP4'e, C# API'sini, .NET Library'ye dönüştürün
description: PPTX'i C# dilinde videoya dönüştürün. PowerPoint'i videoya dönüştürmek için .NET kitaplık API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX'i C# dilinde videoya dönüştürün" h2="NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında C# kodunu kullanarak PowerPoint'i videoya dönüştürmek için güçlü çapraz platform .NET API'si" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# ile PowerPoint'i videoya dönüştürün" variant="code" %}}

PPTX'i videoya dönüştürmek için bu kodu kullanın:

{{< blocks/products/pf/slides-design-update-10-2026/code title="PowerPoint'i videoya dönüştürmek için C# kodu" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides kullanarak PowerPoint'i videoya dönüştürün" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/tr/net/), sunumlar oluşturmak, düzenlemek ve değiştirmek ve ayrıca PowerPoint sunumlarını diğer belgelere dönüştürmek için kullanılan güçlü bir .NET kitaplığıdır. ve videolar. Bu durumda, PowerPoint'i videoya dönüştürmek için **ffmpeg** ve **FFMpegCore** (ücretsiz bir NET ffmpeg sarıcı) ile birlikte **Aspose.Slides** kullanmanız gerekir.

PPTX'ten videoya dönüştürme işlemi şu şekilde çalışır: Aspose.Slides, bir dizi kare (sunum slaytlarından) oluşturmak için kullanılır ve ardından, karelere dayalı bir video oluşturmak için FFMpegCore (ffmpeg) kullanılır.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPTX'i videoya dönüştürme yöntemi" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET** ve **FFMpegcore**'u kurun: "dotnet add package Aspose.Slides.NET --version 22.12.0" çalıştırın ve sonra "dotnet add package FFMpegCore --version 4.8.0" çalıştırın{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ffmpeg'i [buradan] indirin(https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}FFMpegCore, indirilen ffmpeg'in yolunu belirtmenizi gerektirir (örn. "C:\tools\ffmpeg" konumuna çıkarılır): `GlobalFFOptions.Configure(new FFOptions { BinaryFolder = @"c:\tools\ffmpeg\bin",} ); `{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PowerPoint to video kodunu kopyalayın, yapıştırın ve çalıştırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Dönüşümler" subTitle="PowerPoint'i başka biçimlerdeki dosyalara da dönüştürebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-word/" name="PPTX TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
