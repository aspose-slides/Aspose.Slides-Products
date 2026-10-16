---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: تحويل PPT إلى فيديو في C#
url: /ar/net/conversion/ppt-to-video/
keywords: تحويل PPT إلى فيديو ، PPT إلى فيديو ، PowerPoint إلى فيديو ، PPT إلى MP4 ، C# API ، مكتبة .NET
description: تحويل PPT إلى فيديو في C#. استخدم .NET Library API لتحويل PowerPoint إلى فيديو
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="تحويل PPT إلى فيديو في C#" h2="واجهة برمجة تطبيقات .NET API قوية ومتعددة الأنظمة لتحويل PowerPoint إلى فيديو باستخدام كود C# على NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PowerPoint إلى فيديو في C#" variant="code" %}}

استخدم هذا الرمز لتحويل PPT إلى فيديو:

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# لتحويل PowerPoint إلى فيديو" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="تحويل PowerPoint إلى فيديو باستخدام Aspose.Slides" %}}

[** Aspose.Slides for .NET **](https://products.aspose.com/slides/ar/net/) هي مكتبة .NET قوية تُستخدم لإنشاء العروض التقديمية وتعديلها ومعالجتها وكذلك تحويل عروض PowerPoint التقديمية إلى مستندات أخرى ومقاطع الفيديو. في هذه الحالة ، لتحويل PowerPoint إلى فيديو ، تحتاج إلى استخدام ** Aspose.Slides ** بجانب ** ffmpeg ** و ** FFMpegCore ** (غلاف NET ffmpeg مجاني).

هذه هي الطريقة التي تعمل بها عملية تحويل PPT إلى فيديو: Aspose.Slides تستخدم لإنشاء مجموعة من الإطارات (من شرائح العرض التقديمي) ثم FFMpegCore (ffmpeg) تُستخدم لإنشاء فيديو على أساس الإطارات.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="كيفية تحويل PPT إلى فيديو" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}قم بتثبيت ** Aspose.Slides for .NET ** و ** FFMpegcore **: قم بتشغيل `dotnet add package Aspose.Slides.NET --version 22.12.0` ثم قم بتشغيل` dotnet add package FFMpegCore --version 4.8.0`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}تنزيل ffmpeg [هنا](https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}يتطلب FFMpegCore تحديد المسار إلى ffmpeg الذي تم تنزيله (على سبيل المثال المستخرج إلى "C: \ tools \ ffmpeg"): GlobalFFOptions.Configure (new FFOptions {BinaryFolder = @ "c: \ tools \ ffmpeg \ bin"،}) ؛ "{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}انسخ والصق ثم قم بتشغيل PowerPoint إلى رمز الفيديو.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل PowerPoint إلى ملفات بتنسيقات أخرى" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ar/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
