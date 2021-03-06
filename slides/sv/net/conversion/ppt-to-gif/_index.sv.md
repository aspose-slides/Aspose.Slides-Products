---
title: Konvertera PPT till GIF via C#
weight: 1290
url: /sv/net/conversion/ppt-to-gif/ 
description: Exempelkod för konvertering av PPT till GIF C#. Använd API-exempelkod för batch-PPT-filer till GIF-konvertering inom VB.NET, Asp.NET eller någon .NET-baserad applikation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera PPT till GIF via C#" h2="Exportera PowerPoint® PPT-filer till GIF på .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hur man konverterar PPT till GIF med C#" %}}

 För att konvertera PPT till GIF kommer vi att använda
 [Aspose.Slides för .NET](https://products.aspose.com/slides/sv/net)
 API som är ett funktionsrikt, kraftfullt och lättanvänt API för dokumentmanipulation och konvertering för C#-plattformen. Öppen
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 pakethanterare, sök efter
 Aspose.Slides
 och installera. Du kan också använda följande kommando från Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Pakethanterarens konsolkommando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Steg för att konvertera PPT till GIF via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name=".NET-utvecklare kan enkelt ladda och konvertera PPT-filer till GIF på bara några rader kod." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPT-fil med en instans av presentationsklassen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterera genom varje bild i presentationen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skapa en fullskalig bild som en bitmapp med varje iteration
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ring Bitmap.Save-metoden med GIF-filtillägg & ImageFormat.Gif som parametrar
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör källkoden för .NET-omvandlingen, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar.
- Utvecklingsmiljö som Microsoft Visual Studio.
- Aspose.Slides för .NET DLL som refereras till i ditt projekt.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Denna exempelkod visar PPT till GIF C#-konvertering" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.ppt"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in GIF format
        bitmap.Save(string.Format("Slide_{0}.gif", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Gif);
    }
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="ppt-to-gif"
        sectionTitle="Gratis app att konvertera PPT till GIF" 
        sectionDescription="[Prova vår gratis Video -app](https://products.aspose.app/slides/video/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera PPT till många andra filformat inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Bitmappsbild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-emf/" name="PPT TO EMF" description="Förbättrat metafilformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-html/" name="PPT TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" description="JPEG-bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-odp/" name="PPT TO ODP" description="OpenDocument presentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-otp/" name="PPT TO OTP" description="OpenDocument standardformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-pdf/" name="PPT TO PDF" description="Portabelt dokumentformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-png/" name="PPT TO PNG" description="Bärbar nätverksgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-pot/" name="PPT TO POT" description="Microsoft PowerPoint-mallfiler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-potm/" name="PPT TO POTM" description="Microsoft PowerPoint-mallfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-potx/" name="PPT TO POTX" description="Presentation av Microsoft PowerPoint-mall" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-pps/" name="PPT TO PPS" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Makroaktiverat bildspel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Makroaktiverad presentationsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Öppna XML-presentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-svg/" name="PPT TO SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-swf/" name="PPT TO SWF" description="SWF-format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/conversion/ppt-to-xps/" name="PPT TO XPS" description="XML-pappersspecifikationer" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}