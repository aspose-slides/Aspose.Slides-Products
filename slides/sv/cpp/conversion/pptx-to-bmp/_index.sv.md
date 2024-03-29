---
title: Konvertera PPTX till BMP via C++-applikation
weight: 6400
url: /sv/cpp/conversion/pptx-to-bmp/ 
description: Exempel på C++-konverteringskod för PPTX-dokument till BMP-format. Använd exempelkod för batchkonvertering av PPTX till BMP inom valfri C++-applikation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera PPTX till BMP via C++" h2="Högpresterande PPTX till BMP-konvertering med C++-bibliotek utan behov av Microsoft PowerPoint-installation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hur man konverterar PPTX till BMP med C++" %}}

 För att konvertera PPTX till BMP kommer vi att använda
 [Aspose.Slides för C++](https://products.aspose.com/slides/sv/cpp/)
 API som är ett funktionsrikt, kraftfullt och lättanvänt API för dokumentmanipulering och konvertering för C++-plattformen. Du kan ladda ner den senaste versionen direkt, bara öppna
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 pakethanterare, sök efter
 Aspose.Slides.Cpp
 och installera. Du kan också använda följande kommando från Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Kommando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera PPTX till BMP via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++-utvecklare kan enkelt konvertera PPTX-fil till BMP på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda PPTX-fil med Aspose.Slides för C++ Presentation Object.
1. Välj den första bilden.
1. Ställ in önskade mått.
1. Skaffa miniatyrbilden med önskade mått.
1. Anropa metoden Save() med BMP-utgångsparameter .
1. Öppna BMP-filen i ett kompatibelt program.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör C++-konverteringsexempelkoden, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32 bit, Windows 64 bit och Linux 64 bit.
- Aspose.Slides för C++ DLL som refereras till i ditt projekt.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPTX till BMP C++ Källkod för konvertering" offSpacer="" %}}

```cs
// Load the PPTX
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.pptx");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.bmp", ImageFormat::get_Bmp());
	
//Iterate through each slide via index and convert

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="pptx-to-bmp"
        sectionTitle="Gratis app att konvertera PPTX till BMP" 
        sectionDescription="[Prova vår gratis app att konvertera PPT till BMP](https://products.aspose.app/slides/conversion/ppt-to-bmp)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera PPTX till många andra filformat, inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" description="Förbättrat metafilformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Grafiskt utbytesformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="JPEG-bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument presentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument standardformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Portabelt dokumentformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" description="Bärbar nätverksgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-pot/" name="PPTX TO POT" description="Microsoft PowerPoint-mallfiler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Microsoft PowerPoint-mallfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Presentation av Microsoft PowerPoint-mall" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Makroaktiverat bildspel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Makroaktiverad presentationsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-xml/" name="PPTX TO XML" description="Extensible Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML-pappersspecifikationer" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}