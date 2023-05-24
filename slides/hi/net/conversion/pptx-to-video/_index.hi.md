---
title: पीपीटीएक्स को सी # में वीडियो में कनवर्ट करें
url: /hi/net/conversion/pptx-to-video/
keywords: PPTX को वीडियो में, PPTX को वीडियो में, PowerPoint को वीडियो में, PPTX को MP4 में, C# API, .NET लाइब्रेरी में बदलें
description: पीपीटीएक्स को सी # में वीडियो में कनवर्ट करें। PowerPoint को वीडियो में बदलने के लिए .NET लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="पीपीटीएक्स को सी # में वीडियो में कनवर्ट करें" h2="शक्तिशाली क्रॉस-प्लेटफ़ॉर्म .NET API, NET फ्रेमवर्क, .NET Core, Windows Azure, Mono या Xamarin प्लेटफ़ॉर्म पर C# कोड का उपयोग करके PowerPoint को वीडियो में बदलने के लिए" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके PowerPoint को वीडियो में बदलें" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hi/net/) एक शक्तिशाली .NET लाइब्रेरी है जिसका उपयोग प्रस्तुतियों को बनाने, संपादित करने और हेरफेर करने और PowerPoint प्रस्तुतियों को अन्य दस्तावेज़ों में बदलने के लिए भी किया जाता है और वीडियो। इस स्थिति में, PowerPoint को वीडियो में बदलने के लिए, आपको **Aspose.Slides** का उपयोग **ffmpeg** और **FFMpegCore** (एक निःशुल्क NET ffmpeg आवरण) के साथ करना होगा।

PPTX से वीडियो रूपांतरण प्रक्रिया इस प्रकार काम करती है: Aspose.Slides का उपयोग फ़्रेम का एक सेट (प्रस्तुति स्लाइड से) उत्पन्न करने के लिए किया जाता है और फिर FFMpegCore (ffmpeg) का उपयोग फ़्रेम के आधार पर वीडियो बनाने के लिए किया जाता है।

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="पीपीटीएक्स को वीडियो में कैसे बदलें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET** और **FFMPegcore** इंस्टॉल करें: `dotnet add package Aspose.Slides.NET --version 22.12.0` चलाएं और फिर `dotnet add package FFMpegCore --version 4.8.0` चलाएं
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ffmpeg डाउनलोड करें [यहाँ।](https://ffmpeg.org/download.html)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
FFMpegCore के लिए आपको डाउनलोड किए गए ffmpeg का पथ निर्दिष्ट करना आवश्यक है (उदाहरण के लिए "C:\tools\ffmpeg" से निकाला गया): `GlobalFFOptions.Configure(new FFOptions { BinaryFolder = @"c:\tools\ffmpeg\bin",} ); `
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रतिलिपि बनाएँ, चिपकाएँ, और फिर PowerPoint को वीडियो कोड पर चलाएँ।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint को C# में वीडियो में कनवर्ट करें" %}}
PPTX को वीडियो में बदलने के लिए इस कोड का उपयोग करें:

{{% blocks/products/pf/agp/code-block title="PowerPoint को वीडियो में बदलने के लिए C# कोड" offSpacer="true" %}}
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

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप PowerPoint को अन्य स्वरूपों में फ़ाइलों में भी रूपांतरित कर सकते हैं" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptx-to-word/" name="PPTX TO WORD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}