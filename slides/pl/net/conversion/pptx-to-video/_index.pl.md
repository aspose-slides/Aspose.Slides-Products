---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konwertuj PPTX na wideo w C#
url: /pl/net/conversion/pptx-to-video/
keywords: Konwertuj PPTX na wideo, PPTX na wideo, PowerPoint na wideo, PPTX na MP4, C# API, .NET Library
description: Konwertuj PPTX na wideo w C#. Użyj interfejsu API biblioteki platformy .NET, aby przekonwertować program PowerPoint na wideo
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konwertuj PPTX na wideo w C#" h2="Potężny, wieloplatformowy interfejs API platformy .NET do konwersji programu PowerPoint na wideo przy użyciu kodu C# w platformach NET Framework, .NET Core, Windows Azure, Mono lub Xamarin" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PowerPoint na wideo w C#" variant="code" %}}

Użyj tego kodu, aby przekonwertować PPTX na wideo:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kod C# do konwersji programu PowerPoint na wideo" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konwertuj PowerPoint na wideo za pomocą Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/pl/net/) to potężna biblioteka .NET używana do tworzenia, edytowania i manipulowania prezentacjami, a także konwertowania prezentacji PowerPoint na inne dokumenty i wideo. W takim przypadku, aby przekonwertować PowerPoint na wideo, musisz użyć **Aspose.Slides** wraz z **ffmpeg** i **FFMpegCore** (bezpłatne opakowanie ffmpeg NET).

Oto jak działa proces konwersji PPTX na wideo: Aspose.Slides służy do generowania zestawu klatek (ze slajdów prezentacji), a następnie FFMpegCore (ffmpeg) jest używany do tworzenia wideo na podstawie klatek.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak przekonwertować PPTX na wideo" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zainstaluj **Aspose.Slides dla .NET** i **FFMpegcore**: Uruchom `dotnet add package Aspose.Slides.NET --version 22.12.0`, a następnie uruchom `dotnet add package FFMpegCore --version 4.8.0`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pobierz ffmpeg [tutaj.](https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}FFMpegCore wymaga podania ścieżki do pobranego ffmpeg (np. wyodrębnionego do „C:\tools\ffmpeg”): `GlobalFFOptions.Configure(new FFOptions { BinaryFolder = @"c:\tools\ffmpeg\bin",} ); `{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skopiuj, wklej, a następnie uruchom kod programu PowerPoint do wideo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane konwersje" subTitle="Możesz także konwertować PowerPoint do plików w innych formatach" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptx-to-word/" name="PPTX TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pl/net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
