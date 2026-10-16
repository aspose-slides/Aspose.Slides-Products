---
lastmod: 2023-05-24
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: सी # में पीपीटी को वीडियो में कनवर्ट करें
url: /hi/net/conversion/ppt-to-video/
keywords: PPT को वीडियो में, PPT को वीडियो में, PowerPoint को वीडियो में, PPT को MP4 में, C# API, .NET लाइब्रेरी में कन्वर्ट करें
description: पीपीटी को सी # में वीडियो में कनवर्ट करें। PowerPoint को वीडियो में बदलने के लिए .NET लाइब्रेरी API का उपयोग करें
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="सी # में पीपीटी को वीडियो में कनवर्ट करें" h2="शक्तिशाली क्रॉस-प्लेटफ़ॉर्म .NET API, NET फ्रेमवर्क, .NET Core, Windows Azure, Mono या Xamarin प्लेटफ़ॉर्म पर C# कोड का उपयोग करके PowerPoint को वीडियो में बदलने के लिए" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PowerPoint को C# में वीडियो में कनवर्ट करें" variant="code" %}}

पीपीटी को वीडियो में बदलने के लिए इस कोड का प्रयोग करें:

{{< blocks/products/pf/slides-design-update-10-2026/code title="PowerPoint को वीडियो में बदलने के लिए C# कोड" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides का उपयोग करके PowerPoint को वीडियो में बदलें" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/hi/net/) एक शक्तिशाली .NET लाइब्रेरी है जिसका उपयोग प्रस्तुतियों को बनाने, संपादित करने और हेरफेर करने और PowerPoint प्रस्तुतियों को अन्य दस्तावेज़ों में बदलने के लिए भी किया जाता है और वीडियो। इस स्थिति में, PowerPoint को वीडियो में बदलने के लिए, आपको **Aspose.Slides** का उपयोग **ffmpeg** और **FFMpegCore** (एक निःशुल्क NET ffmpeg आवरण) के साथ करना होगा।

पीपीटी से वीडियो रूपांतरण प्रक्रिया इस प्रकार काम करती है: Aspose.Slides का उपयोग फ्रेम का एक सेट (प्रस्तुति स्लाइड से) उत्पन्न करने के लिए किया जाता है और फिर FFMpegCore (ffmpeg) का उपयोग फ्रेम के आधार पर वीडियो बनाने के लिए किया जाता है।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="पीपीटी को वीडियो में कैसे बदलें" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET** और **FFMPegcore** इंस्टॉल करें: `dotnet add package Aspose.Slides.NET --version 22.12.0` चलाएं और फिर `dotnet add package FFMpegCore --version 4.8.0` चलाएं{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ffmpeg डाउनलोड करें [यहाँ।](https://ffmpeg.org/download.html){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}FFMpegCore के लिए आपको डाउनलोड किए गए ffmpeg का पथ निर्दिष्ट करना आवश्यक है (उदाहरण के लिए "C:\tools\ffmpeg" से निकाला गया): `GlobalFFOptions.Configure(new FFOptions { BinaryFolder = @"c:\tools\ffmpeg\bin",} ); `{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रतिलिपि बनाएँ, चिपकाएँ, और फिर PowerPoint को वीडियो कोड पर चलाएँ।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित रूपांतरण" subTitle="आप PowerPoint को अन्य स्वरूपों में फ़ाइलों में भी रूपांतरित कर सकते हैं" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
