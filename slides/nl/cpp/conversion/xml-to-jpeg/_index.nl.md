---
title: Converteer XML naar JPEG via de C++-toepassing
weight: 3960
url: /nl/cpp/conversion/xml-to-jpeg/ 
description: Voorbeeld C++-conversiecode voor XML-document naar JPEG-indeling. Gebruik voorbeeldcode voor batch-XML naar JPEG-conversie binnen elke C++-toepassing.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converteer XML naar JPEG via C++" h2="Hoogwaardige XML-naar-JPEG-conversie met behulp van de C++-bibliotheek zonder de noodzaak van Microsoft PowerPoint-installatie." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hoe XML naar JPEG te converteren met C++" %}}

 Om XML naar JPEG te converteren, gebruiken we
 [Aspose.Slides voor C++](https://products.aspose.com/slides/nl/cpp/)
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

{{% blocks/products/pf/agp/feature-section-col title="Stappen om XML naar JPEG te converteren via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++-ontwikkelaars kunnen eenvoudig een XML-bestand converteren naar JPEG in slechts een paar regels code.

{{% /blocks/products/pf/agp/text %}}

1. Laad XML-bestand met Aspose.Slides voor C++ Presentation Object.
1. Selecteer de eerste dia.
1. Stel de gewenste afmetingen in.
1. Verkrijg de miniatuur met de gewenste afmetingen.
1. Roep de methode Save() aan met de JPEG-uitvoerparameter .
1. Open het JPEG-bestand in een compatibel programma.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Voordat u de voorbeeldcode voor C++-conversie uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met C++ Runtime Environment voor Windows 32 bit, Windows 64 bit en Linux 64 bit.
- Aspose.Slides voor C++ DLL waarnaar in uw project wordt verwezen.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XML naar JPEG C++ conversie broncode" offSpacer="" %}}

```cs
// Load the XML
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.xml");

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

bitmap->Save(u"output.jpeg", ImageFormat::get_Jpeg());
	
//Iterate through each slide via index and convert

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Gratis app om XML te converteren naar JPEG" 
        sectionDescription="[Probeer onze gratis Text To Gif app](https://products.aspose.app/slides/text-to-gif/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="U kunt XML ook converteren naar vele andere bestandsindelingen, waaronder enkele die hieronder worden vermeld." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-bmp/" name="XML TO BMP" description="Bitmap afbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-emf/" name="XML TO EMF" description="Verbeterde metabestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-gif/" name="XML TO GIF" description="Grafisch uitwisselingsformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-html/" name="XML TO HTML" description="Hypertekst-opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-odp/" name="XML TO ODP" description="OpenDocument-presentatie-indeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-otp/" name="XML TO OTP" description="Standaardformaat OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-pdf/" name="XML TO PDF" description="Draagbaar documentformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-png/" name="XML TO PNG" description="Draagbare netwerkgrafieken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-pot/" name="XML TO POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-potm/" name="XML TO POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-potx/" name="XML TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-pps/" name="XML TO PPS" description="PowerPoint-diavoorstelling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-ppsm/" name="XML TO PPSM" description="Diavoorstelling met macro's" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-ppsx/" name="XML TO PPSX" description="PowerPoint-diavoorstelling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-ppt/" name="XML TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-pptm/" name="XML TO PPTM" description="Presentatiebestand met macro's" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-pptx/" name="XML TO PPTX" description="Open XML-presentatie-indeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-svg/" name="XML TO SVG" description="Schaalbare vectorafbeeldingen" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-tiff/" name="XML TO TIFF" description="Gelabelde afbeeldingsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/cpp/conversion/xml-to-xps/" name="XML TO XPS" description="XML-papierspecificaties" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}