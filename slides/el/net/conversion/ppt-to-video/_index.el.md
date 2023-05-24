---
title: Μετατροπή PPT σε βίντεο σε C#
url: /el/net/conversion/ppt-to-video/
keywords: Μετατροπή PPT σε βίντεο, PPT σε βίντεο, PowerPoint σε βίντεο, PPT σε MP4, C# API, Βιβλιοθήκη .NET
description: Μετατροπή PPT σε βίντεο σε C#. Χρησιμοποιήστε το API βιβλιοθήκης .NET για να μετατρέψετε το PowerPoint σε βίντεο
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Μετατροπή PPT σε βίντεο σε C#" h2="Ισχυρό cross-platform .NET API για μετατροπή PowerPoint σε βίντεο με χρήση κώδικα C# σε πλατφόρμες NET Framework, .NET Core, Windows Azure, Mono ή Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Μετατρέψτε το PowerPoint σε βίντεο χρησιμοποιώντας το Aspose.Slides" %}}

Το [**Aspose.Slides for .NET**](https://products.aspose.com/slides/el/net/) είναι μια ισχυρή βιβλιοθήκη .NET που χρησιμοποιείται για τη δημιουργία, επεξεργασία και χειρισμό παρουσιάσεων και επίσης μετατροπή παρουσιάσεων PowerPoint σε άλλα έγγραφα και βίντεο. Σε αυτήν την περίπτωση, για να μετατρέψετε το PowerPoint σε βίντεο, πρέπει να χρησιμοποιήσετε το **Aspose.Slides** μαζί με το **ffmpeg** και το **FFMpegCore** (ένα δωρεάν περιτύλιγμα NET ffmpeg).

Έτσι λειτουργεί η διαδικασία μετατροπής PPT σε βίντεο: Το Aspose.Slides χρησιμοποιείται για τη δημιουργία ενός συνόλου καρέ (από τις διαφάνειες παρουσίασης) και στη συνέχεια το FFMpegCore (ffmpeg) για τη δημιουργία ενός βίντεο με βάση τα καρέ.

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να μετατρέψετε το PPT σε βίντεο" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το **Aspose.Slides για .NET** και **FFMpegcore**: Εκτελέστε το "dotnet add package Aspose.Slides.NET --version 22.12.0" και, στη συνέχεια, εκτελέστε το "dotnet add package FFMpegCore --έκδοση 4.8.0"
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κατεβάστε το ffmpeg [εδώ.](https://ffmpeg.org/download.html)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Το FFMpegCore απαιτεί να καθορίσετε τη διαδρομή προς το κατεβασμένο ffmpeg (π.χ. εξαγωγή στο "C:\tools\ffmpeg"): `GlobalFFOptions.Configure(new FFOptions { BinaryFolder = @"c:\tools\ffmpeg\bin",} ); `
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αντιγράψτε, επικολλήστε και, στη συνέχεια, εκτελέστε τον κώδικα του PowerPoint σε βίντεο.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PowerPoint σε βίντεο σε C#" %}}
Χρησιμοποιήστε αυτόν τον κωδικό για να μετατρέψετε το PPT σε βίντεο:

{{% blocks/products/pf/agp/code-block title="Κωδικός C# για τη μετατροπή του PowerPoint σε βίντεο" offSpacer="true" %}}
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

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το PowerPoint σε αρχεία σε άλλες μορφές" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppt-to-word/" name="PPT TO WORD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}