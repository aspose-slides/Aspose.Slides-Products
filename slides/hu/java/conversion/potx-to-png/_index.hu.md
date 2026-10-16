---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: A POTX konvertálása PNG-re Java segítségével
weight: 5620
url: /hu/java/conversion/potx-to-png/ 
description: Java konverziós kód minta POTX formátumhoz PNG fájlba. Ezzel a példakóddal PowerPoint és OpenOffice prezentációkat exportálhat PNG formátumba bármely webes vagy asztali Java alapú alkalmazáson belül.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="A POTX konvertálása PNG-re Java segítségével" h2="POTX-PNG Java konvertálás egyetlen vagy több oldal konvertálásához PNG formátumba a helyszíni Java könyvtár használatával."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hogyan lehet POTX-et PNG-re konvertálni Java segítségével" %}}

Ahhoz, hogy a POTX-et PNG-be rendereljük, használjuk
 [Aspose.Slides for Java](https://products.aspose.com/slides/hu/java/)
 API, amely egy funkciókban gazdag, hatékony és könnyen használható konverziós API Java platformhoz. A legújabb verziót közvetlenül a webhelyről töltheti le
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 és telepítse a Maven-alapú projekten belül a következő konfigurációk hozzáadásával a pom.xml fájlhoz.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Adattár" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Függőség" >}}
```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTX-ből PNG-be konvertáló Java-forráskód" >}}
```cs
// load POTX with Aspose.Slides
Presentation presentation = new Presentation("template.potx");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type PNG for every slide
  File outputfile = new File(sld.getSlideNumber() + ".png");
  
  // save the slide image to disk
  ImageIO.write(bi, "png", outputfile);
}   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Lépések a POTX konvertálásához PNG-be Java segítségével" intro="A Java fejlesztők könnyedén konvertálhatják a POTX fájlt PNG formátumba, mindössze néhány sornyi kóddal." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a POTX fájlt a Presentation osztály egy példányával{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ismételje meg a prezentáció egyes diáit{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hozzon létre egy teljes léptékű képet bittérképként minden iterációval{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a Bitmap.save metódust PNG fájlkiterjesztéssel és ImageFormattal{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="rendszerkövetelmények" intro="A Java konverziós mintakód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel." %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futási környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.
- Szerezze be az Aspose.Slides for Java legújabb verzióját közvetlenül a Maventől.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ingyenes alkalmazás a POTX konvertálásához PNG -re"
  description="[Próbálja ki az ingyenes alkalmazást a PPT konvertálásához PNG -re](https://products.aspose.app/slides/conversion/ppt-to-png)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott konverziók" subTitle="A POTX-et számos más fájlformátumra is konvertálhatja, köztük néhány alább felsorolt ​​fájlformátumba." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-bmp/" name="POTX TO BMP" description="Bittérképes kép" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-gif/" name="POTX TO GIF" description="Grafikus csereformátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-html/" name="POTX TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-jpeg/" name="POTX TO JPEG" description="JPEG kép" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-odp/" name="POTX TO ODP" description="OpenDocument prezentációs formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-otp/" name="POTX TO OTP" description="OpenDocument szabványos formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-pdf/" name="POTX TO PDF" description="Hordozható dokumentum formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-pot/" name="POTX TO POT" description="Microsoft PowerPoint sablonfájlok" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-potm/" name="POTX TO POTM" description="Microsoft PowerPoint sablonfájl" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-pps/" name="POTX TO PPS" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="Makró-képes diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-ppt/" name="POTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-pptm/" name="POTX TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-pptx/" name="POTX TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-svg/" name="POTX TO SVG" description="Skálázható vektorgrafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-swf/" name="POTX TO SWF" description="SWF formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-tiff/" name="POTX TO TIFF" description="Címkézett képformátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/potx-to-xps/" name="POTX TO XPS" description="XML papírspecifikációk" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
