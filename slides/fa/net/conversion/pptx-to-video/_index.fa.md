---
title: تبدیل PPTX به ویدیو در سی شارپ
url: /fa/net/conversion/pptx-to-video/
keywords: تبدیل PPTX به ویدئو، PPTX به ویدئو، پاورپوینت به ویدئو، PPTX به MP4، C# API، کتابخانه دات نت
description: تبدیل PPTX به ویدیو در سی شارپ. از .NET library API برای تبدیل پاورپوینت به ویدیو استفاده کنید
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="تبدیل PPTX به ویدیو در سی شارپ" h2="API قدرتمند کراس پلتفرم دات نت برای تبدیل پاورپوینت به ویدیو با استفاده از کد سی شارپ در NET Framework، .NET Core، Windows Azure، Mono یا Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="با استفاده از Aspose.Slides پاورپوینت را به ویدیو تبدیل کنید" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/fa/net/) یک کتابخانه قدرتمند دات نت است که برای ایجاد، ویرایش و دستکاری ارائه ها و همچنین تبدیل ارائه های پاورپوینت به اسناد دیگر استفاده می شود. و فیلم ها در این مورد، برای تبدیل پاورپوینت به ویدیو، باید از **Aspose.Slides** در کنار **ffmpeg** و **FFMpegCore** (یک بسته بندی رایگان NET ffmpeg) استفاده کنید.

فرآیند تبدیل PPTX به ویدیو به این صورت است: Aspose.Slides برای تولید مجموعه ای از فریم ها (از اسلایدهای ارائه) و سپس FFMpegCore (ffmpeg) برای ایجاد یک ویدیو بر اساس فریم ها استفاده می شود.

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="نحوه تبدیل PPTX به ویدیو" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides را برای NET** و **FFMpegcore** نصب کنید: «dotnet add package Aspose.Slides.NET --version 22.12.0» را اجرا کنید و سپس «dotnet add package FFMpegCore --نسخه 4.8.0» را اجرا کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ffmpeg را [از اینجا] دانلود کنید (https://ffmpeg.org/download.html)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
FFMpegCore از شما می‌خواهد که مسیر ffmpeg دانلود شده را مشخص کنید (به عنوان مثال استخراج شده در "C:\tools\ffmpeg"): `GlobalFFOptions.Configure(new FFOptions { BinaryFolder = @"c:\tools\ffmpeg\bin",} ); `
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
پاورپوینت را کپی، پیست و سپس روی کد ویدیو اجرا کنید.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{% blocks/products/pf/feature-page-section  h2="تبدیل پاورپوینت به ویدیو در سی شارپ" %}}
برای تبدیل PPTX به ویدیو از این کد استفاده کنید:

{{% blocks/products/pf/agp/code-block title="کد سی شارپ برای تبدیل پاورپوینت به ویدیو" offSpacer="true" %}}
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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="سایر تبدیل های پشتیبانی شده" subTitle="همچنین می توانید پاورپوینت را به فایل هایی با فرمت های دیگر تبدیل کنید" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/pptx-to-word/" name="PPTX TO WORD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fa/net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}