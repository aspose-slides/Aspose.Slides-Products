---
title: Converteer OTP naar GIF via Java
weight: 4650
url: /nl/java/conversion/otp-to-gif/ 
description: Voorbeeld Java-conversiecode voor OTP-indeling naar GIF-bestand. Gebruik deze voorbeeldcode om PowerPoint- en OpenOffice-presentaties naar GIF te exporteren binnen elke web- of desktop-Java-toepassing.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converteer OTP naar GIF via Java" h2="OTP naar GIF Java-conversie om enkele of meerdere pagina's naar GIF te converteren met behulp van een lokale Java-bibliotheek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OTP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Hoe OTP naar GIF te converteren met Java" %}}

 Om OTP naar GIF te renderen, gebruiken we
 [Aspose.Slides voor Java](https://products.aspose.com/slides/java)
 API, een veelzijdige, krachtige en gebruiksvriendelijke conversie-API voor het Java-platform. U kunt de nieuwste versie rechtstreeks downloaden van
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

{{% blocks/products/pf/agp/feature-section-col title="Stappen om OTP naar GIF te converteren via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java-ontwikkelaars kunnen het OTP-bestand eenvoudig in slechts een paar regels code naar GIF converteren.

{{% /blocks/products/pf/agp/text %}}

1. Laad OTP-bestand met een instantie van de klasse Presentatie
1. Herhaal elke dia in de presentatie
1. Maak bij elke iteratie een afbeelding op volledige schaal als een bitmap
1. Roep de Bitmap.save-methode aan met de GIF-bestandsextensie & ImageFormat

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Voordat u de voorbeeldcode voor Java-conversie uitvoert, moet u ervoor zorgen dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.
- Download de nieuwste versie van Aspose.Slides voor Java rechtstreeks van Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OTP naar GIF Java-conversiebroncode" offSpacer="" %}}

```cs
// load OTP with Aspose.Slides
Presentation presentation = new Presentation("template.otp");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type GIF for every slide
  File outputfile = new File(sld.getSlideNumber() + ".gif");
  
  // save the slide image to disk
  ImageIO.write(bi, "gif", outputfile);
}   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="otp-to-gif"
        sectionTitle="Gratis app om OTP te converteren naar GIF" 
        sectionDescription="[Probeer onze gratis MP4 To MP3 app](https://products.aspose.app/slides/video/mp4-to-mp3/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="U kunt OTP ook converteren naar vele andere bestandsindelingen, waaronder enkele die hieronder worden vermeld." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-bmp/" name="OTP TO BMP" description="Bitmap afbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-html/" name="OTP TO HTML" description="Hypertekst-opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-jpeg/" name="OTP TO JPEG" description="JPEG-afbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-odp/" name="OTP TO ODP" description="OpenDocument-presentatie-indeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-pdf/" name="OTP TO PDF" description="Draagbaar documentformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-png/" name="OTP TO PNG" description="Draagbare netwerkgrafieken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-pot/" name="OTP TO POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-potm/" name="OTP TO POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-potx/" name="OTP TO POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-pps/" name="OTP TO PPS" description="PowerPoint-diavoorstelling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="Diavoorstelling met macro's" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="PowerPoint-diavoorstelling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-ppt/" name="OTP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-pptm/" name="OTP TO PPTM" description="Presentatiebestand met macro's" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-pptx/" name="OTP TO PPTX" description="Open XML-presentatie-indeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-svg/" name="OTP TO SVG" description="Schaalbare vectorafbeeldingen" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-swf/" name="OTP TO SWF" description="SWF-formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-tiff/" name="OTP TO TIFF" description="Gelabelde afbeeldingsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/otp-to-xps/" name="OTP TO XPS" description="XML-papierspecificaties" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}