---
title: POT konvertálása GIF-be Java segítségével
weight: 1940
url: /hu/java/conversion/pot-to-gif/ 
description: Java konverziós kód minta POT formátumhoz GIF fájllá. Ezzel a példakóddal PowerPoint és OpenOffice prezentációkat exportálhat GIF formátumba bármely webes vagy asztali Java alapú alkalmazáson belül.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="POT konvertálása GIF-be Java segítségével" h2="POT-ból GIF Java-konverzió egyetlen vagy több oldal GIF-formátumba konvertálásához a helyszíni Java-könyvtár használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Hogyan lehet POT-ot GIF-be konvertálni Java segítségével" %}}

 A POT GIF formátumban való megjelenítéséhez használjuk
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

{{% blocks/products/pf/agp/feature-section-col title="Lépések a POT GIF formátumba konvertálásához Java segítségével" %}}

{{% blocks/products/pf/agp/text %}}

 A Java fejlesztők könnyedén konvertálhatnak POT fájlt GIF formátumba, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltse be a POT-fájlt a Prezentáció osztály egy példányával
1. Ismételje meg a prezentáció egyes diáit
1. Hozzon létre egy teljes léptékű képet bittérképként minden iterációval
1. Hívja meg a Bitmap.save metódust GIF fájlkiterjesztéssel és ImageFormattal

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Java konverziós mintakód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futási környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.
- Szerezze be az Aspose.Slides for Java legújabb verzióját közvetlenül a Maventől.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="POT GIF Java konvertálási forráskód" offSpacer="" %}}

```cs
// load POT with Aspose.Slides
Presentation presentation = new Presentation("template.pot");
   
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
        extension=""
        sectionTitle="Ingyenes alkalmazás a POT konvertálásához GIF -re" 
        sectionDescription="[Próbálja ki az ingyenes MP4 To MP3 alkalmazást](https://products.aspose.app/slides/video/mp4-to-mp3/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A POT-ot sok más fájlformátumba is konvertálhatja, beleértve az alábbiakban felsorolt ​​néhányat." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-bmp/" name="POT TO BMP" description="Bittérképes kép" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-html/" name="POT TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-jpeg/" name="POT TO JPEG" description="JPEG kép" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-odp/" name="POT TO ODP" description="OpenDocument prezentációs formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-otp/" name="POT TO OTP" description="OpenDocument szabványos formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-pdf/" name="POT TO PDF" description="Hordozható dokumentum formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-png/" name="POT TO PNG" description="Hordozható hálózati grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-potm/" name="POT TO POTM" description="Microsoft PowerPoint sablonfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-potx/" name="POT TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-pps/" name="POT TO PPS" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Makró-képes diavetítés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-ppsx/" name="POT TO PPSX" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-pptm/" name="POT TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-pptx/" name="POT TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-svg/" name="POT TO SVG" description="Skálázható vektorgrafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-swf/" name="POT TO SWF" description="SWF formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-tiff/" name="POT TO TIFF" description="Címkézett képformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pot-to-xps/" name="POT TO XPS" description="XML papírspecifikációk" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}