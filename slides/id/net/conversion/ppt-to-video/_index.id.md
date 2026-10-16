---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversikan PPT ke Video dalam C#
url: /id/net/conversion/ppt-to-video/
keywords: Konversikan PPT ke video, PPT ke video, PowerPoint ke video, PPT ke MP4, C# API, .NET Library
description: Konversikan PPT ke video dalam C#. Gunakan .NET library API untuk mengonversi PowerPoint ke video
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversikan PPT ke video dalam C#" h2=".NET API lintas platform yang kuat untuk mengonversi PowerPoint ke video menggunakan kode C# pada Platform NET Framework, .NET Core, Windows Azure, Mono atau Xamarin" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ubah PowerPoint menjadi video dalam C#" variant="code" %}}

Gunakan kode ini untuk mengonversi PPT ke video:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode C# untuk mengonversi PowerPoint ke video" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan PowerPoint ke video menggunakan Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/id/net/) adalah pustaka .NET andal yang digunakan untuk membuat, mengedit, dan memanipulasi presentasi serta mengonversi presentasi PowerPoint ke dokumen lain dan video. Dalam hal ini, untuk mengonversi PowerPoint ke video, Anda perlu menggunakan **Aspose.Slides** bersama **ffmpeg** dan **FFMpegCore** (pembungkus NET ffmpeg gratis).

Beginilah cara kerja proses konversi PPT ke video: Aspose.Slides digunakan untuk menghasilkan serangkaian bingkai (dari slide presentasi) dan kemudian FFMpegCore (ffmpeg) digunakan untuk membuat video berdasarkan bingkai tersebut.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Bagaimana mengkonversi PPT ke video" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal **Aspose.Slides untuk .NET** dan **FFMpegcore**: Jalankan `dotnet add package Aspose.Slides.NET --version 22.12.0` lalu jalankan `dotnet add package FFMpegCore --version 4.8.0`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Unduh ffmpeg [di sini.](https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}FFMpegCore mengharuskan Anda menentukan jalur ke ffmpeg yang diunduh (mis. diekstrak ke “C:\tools\ffmpeg”): `GlobalFFOptions.Configure(new FFOptions { BinaryFolder = @"c:\tools\ffmpeg\bin",} ); `{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salin, tempel, lalu jalankan PowerPoint ke kode video.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi PowerPoint ke file dalam format lain" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
