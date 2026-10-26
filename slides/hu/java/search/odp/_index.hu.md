---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Szöveg keresése ODP bemutatófájlokban Java használatával
url: /hu/java/search/odp/
description: Szöveg keresése ODP bemutatókban Java nyelven az Aspose.Slides for Java segítségével.
keywords: szavak keresése ODP fájlban, szöveg keresése ODP fájlban, ODP bemutató szövegének keresése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Szöveg keresése ODP fájlban Java használatával" h2="Készítsen Java-alkalmazásokat, amelyek kiszolgálóoldali API-kkal keresnek szöveget bemutatófájlokban." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Szöveg keresése ODP bemutatóban Java segítségével" variant="code" %}}

Az [Aspose.Slides for Java](/slides/hu/java/) segítségével szöveget kereshet ODP bemutatókban. Gyűjtse össze a szövegkereteket a `SlideUtil.getAllTextBoxes` metódussal, majd vizsgálja meg az `ITextFrame`, `IParagraph` és `IPortion` objektumokat.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Szöveg keresése ODP bemutatóban Java használatával" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan kereshet szöveget ODP fájlban Java segítségével" intro="Az alábbi lépésekkel kereshet szöveget egy ODP bemutatóban." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a ODP fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a `SlideUtil.getAllTextBoxes` metódust az egyes diák szövegkereteinek összegyűjtéséhez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vizsgálja meg az `ITextFrame`, `IParagraph` és `IPortion` objektumokat az egyező szöveg megtalálásához.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Az Aspose.Slides segítségével készült" title="Szöveg keresése ODP fájlokban online" description="Az ingyenes Aspose.Slides Search alkalmazás az [Aspose.Slides for Java](https://products.aspose.com/slides/hu/java/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját ODP fájljaival." button="Aspose.Slides Search megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan talál szöveget az Aspose.Slides, mielőtt kódot írna.
- Keressen egyszerű szöveget vagy reguláris kifejezéseket a ODP fájlban.
- Töltse le a találatokat szövegfájlként.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok kereséshez" subTitle="Java használatával a következő formátumokban is kereshet szöveget." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
