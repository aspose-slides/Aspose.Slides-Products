---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertálja az ODP-t SVG-vé Java segítségével
weight: 8550
url: /hu/java/conversion/odp-to-svg/ 
description: Java konverziós kód minta ODP formátumhoz SVG fájlba. Ezzel a példakóddal PowerPoint és OpenOffice prezentációkat exportálhat SVG formátumba bármely webes vagy asztali Java alapú alkalmazáson belül.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertálja az ODP-t SVG-vé Java segítségével" h2="ODP-SVG Java konvertálás egyetlen vagy több oldal konvertálásához SVG-vé helyszíni Java-könyvtár használatával."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hogyan lehet az ODP-t SVG-vé konvertálni Java használatával" %}}

Ahhoz, hogy az ODP-t SVG-be rendereljük, használjuk
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP SVG Java konverziós forráskód" >}}
```cs
// instantiate a Presentation object that represents a ODP file
Presentation pres = new Presentation("template.odp");
try {
    // Access the first slide
    ISlide sld = pres.getSlides().get_Item(0);

    // Create a memory stream object
    FileOutputStream svgStream = new FileOutputStream("output.svg");

    // Create SVG image of slide and save in memory stream
    sld.writeAsSvg(svgStream);

    svgStream.close();
} catch (IOException e) {
} finally {
    pres.dispose();
}   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Lépések az ODP SVG-vé konvertálásához Java segítségével" intro="A Java fejlesztők egyszerűen konvertálhatják az ODP-fájlt SVG-vé, mindössze néhány sornyi kóddal." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be az ODP-fájlt a Presentation osztály egy példányával{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a Presentation.save metódust a kimeneti fájl elérési útja és a SaveFormat megadása közben{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Az SVG fájl a megadott elérési útra kerül mentésre{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="rendszerkövetelmények" intro="A Java konverziós mintakód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel." %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futási környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.
- Szerezze be az Aspose.Slides for Java legújabb verzióját közvetlenül a Maventől.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Az Aspose.Slides segítségével készült" title="ODP konvertálása SVG formátumba online" description="Az ingyenes Aspose.Slides Conversion alkalmazás az [Aspose.Slides for Java](https://products.aspose.com/slides/hu/java/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját ODP fájljaival." button="Aspose.Slides Conversion megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" upload="Húzza ide vagy töltse fel a fájlt" saveAs="Mentés másként" convert="Konvertálás" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan konvertálja a fájlokat az Aspose.Slides, mielőtt kódot írna.
- Töltsön fel ODP fájlokat, és mentse őket SVG formátumban.
- Töltse le az eredményt, vagy konvertáljon további fájlokat.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott konverziók" subTitle="Az ODP-t sok más fájlformátumra is konvertálhatja, beleértve az alábbiakban felsorolt ​​néhányat." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-bmp/" name="ODP TO BMP" description="Bittérképes kép" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-gif/" name="ODP TO GIF" description="Grafikus csereformátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-html/" name="ODP TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="JPEG kép" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-otp/" name="ODP TO OTP" description="OpenDocument szabványos formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-pdf/" name="ODP TO PDF" description="Hordozható dokumentum formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-png/" name="ODP TO PNG" description="Hordozható hálózati grafika" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-pot/" name="ODP TO POT" description="Microsoft PowerPoint sablonfájlok" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-potm/" name="ODP TO POTM" description="Microsoft PowerPoint sablonfájl" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-potx/" name="ODP TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-pps/" name="ODP TO PPS" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Makró-képes diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-swf/" name="ODP TO SWF" description="SWF formátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Címkézett képformátum" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/odp-to-xps/" name="ODP TO XPS" description="XML papírspecifikációk" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
