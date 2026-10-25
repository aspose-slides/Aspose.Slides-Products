---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1000
title: Szöveg kinyerése PPTX dokumentumokból Java nyelven
url: /hu/java/parser/pptx/ 
description: Szöveg kinyerése PPTX fájlokból Java nyelven az Aspose.Slides for Java segítségével.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX fájlok elemzése Java nyelven" h2="Szöveg és bemutatótartalom kinyerése PPTX dokumentumokból az Aspose.Slides for Java kiszolgálóoldali API-jaival."
  apiHomeLink="/slides/java/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPTX fájl elemzése Java nyelven" %}}

Az [Aspose.Slides for Java](/slides/hu/java/) segítségével PPTX bemutatókat elemezhet, és szöveget nyerhet ki a diákból. A könyvtárat Maven-projekthez az alábbi tároló- és függőségkonfigurációval adhatja hozzá a `pom.xml` fájlban.

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

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX fájlok elemzése – Java" >}}
```java
Presentation presentation = new Presentation("demo.pptx");
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPTX fájlok elemzése Java nyelven lépésről lépésre" intro="Nyerjen ki szöveget egy PPTX bemutatóból az Aspose.Slides for Java segítségével néhány sornyi kóddal." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a `PPTX` fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a `SlideUtil.getAllTextBoxes` metódust az első dia szövegkereteinek lekéréséhez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Járja be az összes `ITextFrame`, `IParagraph` és `IPortion` objektumot.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Olvassa ki a szöveget, a betűméretet és a betűtípus nevét minden `IPortion` objektumból.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Rendszerkövetelmények" intro="Az Aspose.Slides for Java a főbb platformokat és operációs rendszereket támogatja. Győződjön meg arról, hogy a környezete megfelel az alábbi előfeltételeknek." %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java Runtime Environmenttel JSP/JSF- és asztali alkalmazásokhoz.
- Az Aspose.Slides for Java legújabb verziója a [Maven](https://releases.aspose.com/java/repo/) tárolóból.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Az Aspose.Slides segítségével készült" title="Szöveg és képek kinyerése online" description="Az ingyenes Aspose.Slides Parser alkalmazás az [Aspose.Slides for Java](https://products.aspose.com/slides/hu/java/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Parser megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan olvassa az Aspose.Slides a fájljait, mielőtt kódot írna.
- Töltsön fel egy PPTX fájlt, és kapja meg a szövegét és a képeit.
- Töltsön le mindent egyetlen ZIP-archívumban.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

Files with the PPTX extension use the Office Open XML presentation format. A PPTX file stores slides that can contain text, images, formatting, animations, and other presentation content.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott elemzési formátumok" subTitle="Java nyelven más bemutatóformátumokat is elemezhet." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/parser/odp/" name="ODP" description="OpenDocument-bemutató" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/parser/ppt/" name="PPT" description="PowerPoint 97–2003-bemutató" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
