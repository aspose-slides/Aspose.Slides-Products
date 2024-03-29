---
title: A POTM konvertálása PPS-re Java segítségével
weight: 7190
url: /hu/java/conversion/potm-to-pps/ 
description: Java konverziós kód minta POTM formátumhoz PPS fájlba. Ezzel a példakóddal PowerPoint és OpenOffice prezentációkat exportálhat PPS-be bármely webes vagy asztali Java alapú alkalmazáson belül.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="A POTM konvertálása PPS-re Java segítségével" h2="POTM-ből PPS-be Java-konverzió egyetlen vagy több oldal konvertálásához PPS-vé helyszíni Java-könyvtár használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="A POTM konvertálása PPS-re Java használatával" %}}

 Ahhoz, hogy a POTM-et PPS-re rendereljük, használjuk
 [Aspose.Slides for Java](https://products.aspose.com/slides/hu/java/)
 API, amely egy funkciókban gazdag, hatékony és könnyen használható konverziós API Java platformhoz. A legújabb verziót közvetlenül a webhelyről töltheti le
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 és telepítse a Maven-alapú projekten belül a következő konfigurációk hozzáadásával a pom.xml fájlhoz.

{{% blocks/products/pf/agp/code-block title="Adattár" offSpacer="true" %}}

```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Függőség" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="A POTM PPS-re konvertálásának lépései Java segítségével" %}}

{{% blocks/products/pf/agp/text %}}

 A Java fejlesztők könnyedén konvertálhatják a POTM fájlt PPS-re, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltse be a POTM-fájlt a Prezentáció osztály egy példányával
1. Hívja meg a Presentation.save metódust a kimeneti fájl elérési útja és a SaveFormat megadása közben
1. A PPS fájl a megadott elérési útra kerül mentésre

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Java konverziós mintakód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futási környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.
- Szerezze be az Aspose.Slides for Java legújabb verzióját közvetlenül a Maventől.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="POTM–PPS Java konverziós forráskód" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("template.potm");
// save the presentation as PPS
presentation.save("output.pps", SaveFormat.Pps);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Ingyenes alkalmazás a POTM konvertálásához PPS -re" 
        sectionDescription="[Próbálja ki az ingyenes MP4 To MP3 alkalmazást](https://products.aspose.app/slides/video/mp4-to-mp3/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A POTM-ot sok más fájlformátumra is konvertálhatja, beleértve az alábbiakban felsorolt ​​néhányat." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-bmp/" name="POTM TO BMP" description="Bittérképes kép" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-gif/" name="POTM TO GIF" description="Grafikus csereformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-html/" name="POTM TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-jpeg/" name="POTM TO JPEG" description="JPEG kép" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-odp/" name="POTM TO ODP" description="OpenDocument prezentációs formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-otp/" name="POTM TO OTP" description="OpenDocument szabványos formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-pdf/" name="POTM TO PDF" description="Hordozható dokumentum formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-png/" name="POTM TO PNG" description="Hordozható hálózati grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-pot/" name="POTM TO POT" description="Microsoft PowerPoint sablonfájlok" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-potx/" name="POTM TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Makró-képes diavetítés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-svg/" name="POTM TO SVG" description="Skálázható vektorgrafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-swf/" name="POTM TO SWF" description="SWF formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Címkézett képformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/potm-to-xps/" name="POTM TO XPS" description="XML papírspecifikációk" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}