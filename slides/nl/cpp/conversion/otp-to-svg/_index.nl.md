---
title: Converteer OTP naar SVG via de C++-toepassing
weight: 6380
url: /nl/cpp/conversion/otp-to-svg/ 
description: Voorbeeld van C++-conversiecode voor OTP-document naar SVG-indeling. Gebruik voorbeeldcode voor batch-OTP naar SVG-conversie binnen elke C++-toepassing.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converteer OTP naar SVG via C++" h2="Hoogwaardige OTP naar SVG-conversie met behulp van de C++-bibliotheek zonder de noodzaak van Microsoft PowerPoint-installatie." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OTP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hoe OTP naar SVG te converteren met C++" %}}

 Om OTP naar SVG te converteren, gebruiken we
 [Aspose.Slides voor C++](https://products.aspose.com/slides/cpp/)
 API, een veelzijdige, krachtige en gebruiksvriendelijke API voor documentmanipulatie en -conversie voor het C++-platform. Je kunt de nieuwste versie direct downloaden, open gewoon
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 pakketbeheerder, zoek naar
 Aspose.Slides.Cpp
 en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Opdracht" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om OTP naar SVG te converteren via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++-ontwikkelaars kunnen het OTP-bestand eenvoudig in slechts een paar regels code naar SVG converteren.

{{% /blocks/products/pf/agp/text %}}

1. Laad het OTP-bestand met Aspose.Slides voor C++ Presentation Object.
1. Roep de methode Save() aan.
1. Geef het uitvoerbestandspad door met de (SVG) bestandsextensie.
1. SVG-bestand wordt opgeslagen op het opgegeven pad.
1. Open het SVG-bestand in een compatibel programma.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Voordat u de voorbeeldcode voor C++-conversie uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met C++ Runtime Environment voor Windows 32 bit, Windows 64 bit en Linux 64 bit.
- Aspose.Slides voor C++ DLL waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OTP naar SVG C++ conversiebroncode" offSpacer="" %}}

```cs
// Load the OTP.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.otp");
// Save in SVG format.
for (int32_t index = 0; index < prs->get_Slides()->get_Count(); index++)
{
    auto fileName = String::Format(u"slide-{0}.svg", index);
    auto fileStream = System::MakeObject<FileStream>(fileName, FileMode::Create, FileAccess::Write);

    auto slide = prs->get_Slides()->idx_get(index);
    slide->WriteAsSvg(fileStream);
}

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Gratis app om OTP te converteren naar SVG" 
        sectionDescription="[Probeer onze gratis MP4 To MP3 app](https://products.aspose.app/slides/video/mp4-to-mp3/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="U kunt OTP ook converteren naar vele andere bestandsindelingen, waaronder enkele die hieronder worden vermeld." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-bmp/" name="OTP TO BMP" description="Bitmap afbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-emf/" name="OTP TO EMF" description="Verbeterde metabestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-gif/" name="OTP TO GIF" description="Grafisch uitwisselingsformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-html/" name="OTP TO HTML" description="Hypertekst-opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-jpeg/" name="OTP TO JPEG" description="JPEG-afbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-odp/" name="OTP TO ODP" description="OpenDocument-presentatie-indeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-pdf/" name="OTP TO PDF" description="Draagbaar documentformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-png/" name="OTP TO PNG" description="Draagbare netwerkgrafieken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-pot/" name="OTP TO POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-potm/" name="OTP TO POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-potx/" name="OTP TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-pps/" name="OTP TO PPS" description="PowerPoint-diavoorstelling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="Diavoorstelling met macro's" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="PowerPoint-diavoorstelling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-ppt/" name="OTP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-pptm/" name="OTP TO PPTM" description="Presentatiebestand met macro's" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-pptx/" name="OTP TO PPTX" description="Open XML-presentatie-indeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-tiff/" name="OTP TO TIFF" description="Gelabelde afbeeldingsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-xml/" name="OTP TO XML" description="Uitbreidbare opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/otp-to-xps/" name="OTP TO XPS" description="XML-papierspecificaties" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}