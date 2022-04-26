---
title: Konvertálja a PPT-t POTX-re Java-n keresztül
weight: 2990
url: /hu/java/conversion/ppt-to-potx/ 
description: Java konverziós kód minta PPT formátumhoz POTX fájlba. Ezzel a példakóddal PowerPoint és OpenOffice prezentációkat exportálhat POTX-be bármely webes vagy asztali Java alapú alkalmazáson belül.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertálja a PPT-t POTX-re Java-n keresztül" h2="PPT-POTX Java-konverzió egyetlen vagy több oldal konvertálásához POTX-vé helyszíni Java-könyvtár használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Hogyan lehet PPT-t POTX-re konvertálni Java használatával" %}}

 Ahhoz, hogy a PPT-t POTX-re rendereljük, használjuk
 [Aspose.Slides for Java](https://products.aspose.com/slides/java)
 API, amely egy funkciókban gazdag, hatékony és könnyen használható konverziós API Java platformhoz. A legújabb verziót közvetlenül a webhelyről töltheti le
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 és telepítse a Maven-alapú projekten belül a következő konfigurációk hozzáadásával a pom.xml fájlhoz.

{{% blocks/products/pf/agp/code-block title="Adattár" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Függőség" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Lépések a PPT konvertálásához POTX-re Java segítségével" %}}

{{% blocks/products/pf/agp/text %}}

 A Java fejlesztők könnyedén konvertálhatják a PPT fájlt POTX-re, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltse be a PPT-fájlt a Prezentáció osztály egy példányával
1. Hívja meg a Presentation.save metódust a kimeneti fájl elérési útja és a SaveFormat megadása közben
1. A POTX fájl a megadott elérési úton kerül mentésre

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Java konverziós mintakód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futási környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.
- Szerezze be az Aspose.Slides for Java legújabb verzióját közvetlenül a Maventől.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPT–POTX Java konverziós forráskód" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("template.ppt");
// save the presentation as POTX
presentation.save("output.potx", SaveFormat.Potx);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="ppt-to-potx"
        sectionTitle="Ingyenes alkalmazás a PPT konvertálásához POTX -re" 
        sectionDescription="[Próbálja ki az ingyenes MP4 To MP3 alkalmazást](https://products.aspose.app/slides/video/mp4-to-mp3/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A PPT-t sok más fájlformátumra is konvertálhatja, köztük néhány alább felsorolt ​​fájlformátumra." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Bittérképes kép" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-gif/" name="PPT TO GIF" description="Grafikus csereformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-html/" name="PPT TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-jpeg/" name="PPT TO JPEG" description="JPEG kép" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-odp/" name="PPT TO ODP" description="OpenDocument prezentációs formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-otp/" name="PPT TO OTP" description="OpenDocument szabványos formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-pdf/" name="PPT TO PDF" description="Hordozható dokumentum formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-png/" name="PPT TO PNG" description="Hordozható hálózati grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-pot/" name="PPT TO POT" description="Microsoft PowerPoint sablonfájlok" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-potm/" name="PPT TO POTM" description="Microsoft PowerPoint sablonfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-pps/" name="PPT TO PPS" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Makró-képes diavetítés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-svg/" name="PPT TO SVG" description="Skálázható vektorgrafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-swf/" name="PPT TO SWF" description="SWF formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Címkézett képformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/ppt-to-xps/" name="PPT TO XPS" description="XML papírspecifikációk" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}