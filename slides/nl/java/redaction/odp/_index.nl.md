---
title: Zoek en vervang tekst in ODP-document via Java
weight: 240
url: /nl/java/redaction/odp/ 
description: Java-voorbeeldcode om gevoelige informatie in ODP-bestand op Java Runtime Environment voor JSP/JSF-toepassing en desktoptoepassingen te redigeren.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="ODP-indelingen in Java redigeren" h2="Native en hoogwaardige ODP-documentgevoelige redactie-informatie met Aspose.Slides aan de serverzijde voor Java API's, zonder het gebruik van software zoals Microsoft of Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="https://www.nuget.org/packages/aspose.slides.java" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Hoe een ODP-bestand te redigeren met Java" %}}

 Om het ODP-bestand te redigeren, gebruiken we
 [Aspose.Slides voor Java](https://products.aspose.com/slides/nl/java)
 API, een veelzijdige, krachtige en gebruiksvriendelijke redactie-API voor het Java-platform. U kunt de nieuwste versie rechtstreeks downloaden van
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 en installeer het binnen uw op Maven gebaseerde project door de volgende configuraties toe te voegen aan pom.xml.

{{% blocks/products/pf/agp/code-block title="Opslagplaats" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Afhankelijkheid" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-slides</artifactId>
<version>version of aspose-slides API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Stappen om ODP-bestanden in Java te redigeren" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Een basisdocument zoeken en tekst vervangen in inhoud, opmerkingen of metadata met [Aspose.Slides for Java](https://products.aspose.com/slides/nl/java) API's kunnen worden gedaan met slechts enkele regels code. Zoek en vervang tekst in PowerPoint en OpenOffice. Bewerk tekst, opmerkingen, metadata in presentatie via regexp data matching." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP-presentatie laden.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Toegang tot de eerste dia.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Herhaal vormen en stel een verwijzing in naar de gevonden tabel.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
De tekst van elke tijdelijke aanduiding wijzigen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP-bestand opslaan.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides voor Java ondersteunt alle belangrijke platforms en besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.
- Download de nieuwste versie van Aspose.Slides voor Java rechtstreeks van
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides) .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ODP-bestanden redigeren - Java" offSpacer="" %}}

```cs
 //Load ODP file

Presentation pres = new Presentation(dataDir + "sourceFile.odp");

//Access first slide

ISlide slide = pres.getSlides().get_Item(0);

IShape shape= null;

//Iterate through the shapes and set a reference to the table found

for (int i = 0 ; i < slide.getShapes().size() ; i++){

    shape = slide.getShapes().get_Item(i);

    if (shape.getPlaceholder() != null){

        //Change the text of each placeholder

        ((IAutoShape)shape).getTextFrame().setText("This is Placeholder");

    }

}

//Write the ODP to Disk

pres.save(dataDir + "AsposeReplaceTxt.odp",SaveFormat.Odp);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Over Aspose.Slides voor Java API" %}}

 Aspose.Slides API kan worden gebruikt om Microsoft PowerPoint-documenten te lezen, schrijven, manipuleren en converteren naar PDF, XPS, HTML, TIFF, ODP en verschillende andere formaten. Men kan vanaf het begin nieuwe bestanden maken en deze opslaan in de relevante ondersteunde formaten. Aspose.Slides is een zelfstandige API voor het maken, parseren of manipuleren van presentaties, dia's en elementen en is niet afhankelijk van software zoals Microsoft of OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Redaction Live Demos" sectionDescription="Search and replace text in contents, comments or metadata in ODP documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/redaction). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your ODP files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be redacted instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice). 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde redactiedocumenten" subTitle="Met Java kan men gemakkelijk verschillende formaten redigeren, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/redaction/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/redaction/pptx/" name="PPTX" description="Open XML-presentatie-indeling" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}