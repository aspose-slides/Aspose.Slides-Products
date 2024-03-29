---
title: Konvertera ODP till PPSX via Java
weight: 2850
url: /sv/java/conversion/odp-to-ppsx/ 
description: Exempel på Java-konverteringskod för ODP-format till PPSX-fil. Använd den här exempelkoden för att exportera PowerPoint- och OpenOffice-presentationer till PPSX inom alla Java-baserade webb- eller skrivbordsapplikationer.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera ODP till PPSX via Java" h2="ODP till PPSX Java-konvertering för att konvertera enstaka eller flera sidor till PPSX med hjälp av On-premise Java-bibliotek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Hur man konverterar ODP till PPSX med Java" %}}

 För att rendera ODP till PPSX kommer vi att använda
 [Aspose.Slides för Java](https://products.aspose.com/slides/sv/java/)
 API som är ett funktionsrikt, kraftfullt och lättanvänt konverterings-API för Java-plattformen. Du kan ladda ner den senaste versionen direkt från
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 och installera det i ditt Maven-baserade projekt genom att lägga till följande konfigurationer till pom.xml.

{{% blocks/products/pf/agp/code-block title="Förvar" offSpacer="true" %}}

```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Beroende" offSpacer="true" %}}

```xml

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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera ODP till PPSX via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java-utvecklare kan enkelt konvertera ODP-fil till PPSX på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda ODP-fil med en instans av klassen Presentation
1. Anropa metoden Presentation.save medan du anger sökvägen till utdatafilen och SaveFormat
1. PPSX-filen kommer att sparas på den angivna sökvägen

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör exempelkoden för Java-konvertering, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF Application och Desktop Applications.
- Hämta senaste versionen av Aspose.Slides för Java direkt från Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ODP till PPSX Java-konverteringskällkod" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a ODP file
Presentation presentation = new Presentation("template.odp");
// save the presentation as PPSX
presentation.save("output.ppsx", SaveFormat.Ppsx);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Gratis app att konvertera ODP till PPSX" 
        sectionDescription="[Prova vår gratis Collage -app](https://products.aspose.app/slides/collage/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera ODP till många andra filformat inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-bmp/" name="ODP TO BMP" description="Bitmappsbild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-gif/" name="ODP TO GIF" description="Grafiskt utbytesformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-html/" name="ODP TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="JPEG-bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-otp/" name="ODP TO OTP" description="OpenDocument standardformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-pdf/" name="ODP TO PDF" description="Portabelt dokumentformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-png/" name="ODP TO PNG" description="Bärbar nätverksgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-pot/" name="ODP TO POT" description="Microsoft PowerPoint-mallfiler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-potm/" name="ODP TO POTM" description="Microsoft PowerPoint-mallfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-potx/" name="ODP TO POTX" description="Presentation av Microsoft PowerPoint-mall" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-pps/" name="ODP TO PPS" description="PowerPoint-bildspel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Makroaktiverat bildspel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Makroaktiverad presentationsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Öppna XML-presentationsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-svg/" name="ODP TO SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-swf/" name="ODP TO SWF" description="SWF-format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/odp-to-xps/" name="ODP TO XPS" description="XML-pappersspecifikationer" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}