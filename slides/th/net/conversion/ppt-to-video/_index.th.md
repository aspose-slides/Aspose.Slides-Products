---
title: แปลง PPT เป็นวิดีโอใน C#
url: /th/net/conversion/ppt-to-video/
keywords: แปลง PPT เป็นวิดีโอ, PPT เป็นวิดีโอ, PowerPoint เป็นวิดีโอ, PPT เป็น MP4, C# API, .NET Library
description: แปลง PPT เป็นวิดีโอใน C# ใช้ .NET library API เพื่อแปลง PowerPoint เป็นวิดีโอ
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง PPT เป็นวิดีโอใน C#" h2=".NET API ข้ามแพลตฟอร์มที่มีประสิทธิภาพสำหรับการแปลง PowerPoint เป็นวิดีโอโดยใช้โค้ด C# บน NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง PowerPoint เป็นวิดีโอโดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ .NET**](https://products.aspose.com/slides/th/net/) เป็นไลบรารี .NET อันทรงพลังที่ใช้สร้าง แก้ไข และจัดการงานนำเสนอ และยังแปลงงานนำเสนอ PowerPoint เป็นเอกสารอื่นๆ และวิดีโอ ในกรณีนี้ ในการแปลง PowerPoint เป็นวิดีโอ คุณต้องใช้ **Aspose.Slides** ควบคู่ไปกับ **ffmpeg** และ **FFMpegCore** (ตัวตัด FFmpeg NET ฟรี)

นี่เป็นวิธีการทำงานของกระบวนการแปลง PPT เป็นวิดีโอ: Aspose.Slides ใช้เพื่อสร้างชุดของเฟรม (จากสไลด์การนำเสนอ) จากนั้นใช้ FFMpegCore (ffmpeg) เพื่อสร้างวิดีโอตามเฟรม

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง PPT เป็นวิดีโอ" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง **Aspose.Slides สำหรับ .NET** และ **FFMpegcore**: เรียกใช้ `dotnet add package Aspose.Slides.NET --version 22.12.0` จากนั้นเรียกใช้ `dotnet add package FFMpegCore --version 4.8.0`
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ดาวน์โหลด ffmpeg [ที่นี่](https://ffmpeg.org/download.html)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
FFMpegCore ต้องการให้คุณระบุพาธไปยัง ffmpeg ที่ดาวน์โหลดมา (เช่น แยกเป็น “C:\tools\ffmpeg”): `GlobalFFOptions.Configure(new FFOptions { BinaryFolder = @"c:\tools\ffmpeg\bin",} ); `
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
คัดลอก วาง แล้วเรียกใช้โค้ด PowerPoint เป็นวิดีโอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{% blocks/products/pf/feature-page-section  h2="แปลง PowerPoint เป็นวิดีโอใน C#" %}}
ใช้รหัสนี้เพื่อแปลง PPT เป็นวิดีโอ:

{{% blocks/products/pf/agp/code-block title="รหัส C# สำหรับแปลง PowerPoint เป็นวิดีโอ" offSpacer="true" %}}
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

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PowerPoint เป็นไฟล์ในรูปแบบอื่นๆ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}