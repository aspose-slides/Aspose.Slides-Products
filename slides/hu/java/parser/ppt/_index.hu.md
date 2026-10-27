---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7140
title: Szöveg kinyerése PPT dokumentumokból Java nyelven
url: /hu/java/parser/ppt/ 
description: Szöveg kinyerése PPT fájlokból Java nyelven az Aspose.Slides for Java segítségével.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPT fájlok elemzése Java nyelven" h2="Szöveg és bemutatótartalom kinyerése PPT dokumentumokból az Aspose.Slides for Java kiszolgálóoldali API-jaival."
  apiHomeLink="/slides/java/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPT fájl elemzése Java nyelven" %}}

Az [Aspose.Slides for Java](/slides/hu/java/) segítségével PPT bemutatókat elemezhet, és szöveget nyerhet ki a diákból. A könyvtárat Maven-projekthez az alábbi tároló- és függőségkonfigurációval adhatja hozzá a `pom.xml` fájlban.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Tároló" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT fájlok elemzése – Java" >}}
```java
Presentation presentation = new Presentation("demo.ppt");
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

    for (ITextFrame textFrame : slideTextFrames) {
        for (IParagraph paragraph : textFrame.getParagraphs()) {
            for (IPortion portion : paragraph.getPortions()) {
                System.out.print(portion.getText());
                System.out.print(portion.getPortionFormat().getFontHeight());
                System.out.print(portion.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPT fájlok elemzése Java nyelven lépésről lépésre" intro="Nyerjen ki szöveget egy PPT bemutatóból az Aspose.Slides for Java segítségével néhány sornyi kóddal." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a `PPT` fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a `SlideUtil.getAllTextBoxes` metódust az első dia szövegkereteinek lekéréséhez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Járja be az összes `ITextFrame`, `IParagraph` és `IPortion` objektumot.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Olvassa ki a szöveget, a betűméretet és a betűtípus nevét minden `IPortion` objektumból.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Rendszerkövetelmények" intro="Az Aspose.Slides for Java a főbb platformokat és operációs rendszereket támogatja. Győződjön meg arról, hogy a környezete megfelel az alábbi előfeltételeknek." %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java Runtime Environmenttel JSP/JSF- és asztali alkalmazásokhoz.
- Az Aspose.Slides for Java legújabb verziója a [Maven](https://releases.aspose.com/java/repo/) tárolóból.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Az Aspose.Slides segítségével készült" title="Szöveg és képek kinyerése online" description="Az ingyenes Aspose.Slides Parser alkalmazás az [Aspose.Slides for Java](https://products.aspose.com/slides/hu/java/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPT fájljaival." button="Aspose.Slides Parser megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan olvassa az Aspose.Slides a fájljait, mielőtt kódot írna.
- Töltsön fel egy PPT fájlt, és kapja meg a szövegét és a képeit.
- Töltsön le mindent egyetlen ZIP-archívumban.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

A PPT-fájl PowerPoint 97-2003 bemutatót tárol bináris fájlformátumban. Szöveget, képeket, diagramokat, multimédiát és beágyazott objektumokat tartalmazó diákat tartalmazhat.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott elemzési formátumok" subTitle="Java nyelven más bemutatóformátumokat is elemezhet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/parser/odp/" name="ODP" description="OpenDocument-bemutató" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/parser/pptx/" name="PPTX" description="PowerPoint Open XML-bemutató" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
