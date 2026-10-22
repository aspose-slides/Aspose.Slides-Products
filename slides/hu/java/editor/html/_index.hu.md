---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: HTML szerkesztése Java nyelven
url: /hu/java/editor/html/
keywords: HTML, HTML, Java API, Java Library szerkesztése
description: HTML szerkesztése Java nyelven. Használja a Java könyvtár API-t a HTML-fájl szerkesztéséhez
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="HTML szerkesztése Java nyelven" h2="Nagy sebességű és többplatformos Java könyvtár HTML szerkesztéséhez Java kóddal" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="HTML szerkesztése Java nyelven" variant="code" %}}

Az [**Aspose.Slides for Java**](https://products.aspose.com/slides/hu/java/) használatával mindössze néhány sornyi kóddal új szövegsort adhat hozzá egy HTML-dokumentumhoz.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java kód a HTML szerkesztéséhez" >}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        pres.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("page.html", SaveFormat.Html5);
} catch(IOException e) {
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Szerkessze a HTML-t az Aspose.Slides segítségével" %}}

Az [**Aspose.Slides for Java**](https://products.aspose.com/slides/hu/java/) egy hatékony Java-könyvtár, amely prezentációk, HTML-dokumentumok és egyéb fájlok kezelésére és szerkesztésére szolgál. Egy HTML-dokumentumot szerkeszthet úgy, hogy új szövegsort ad hozzá.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan lehet HTML-t szerkeszteni Java-ban" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az **Aspose.Slides for Java** programot. Lásd: [**Telepítés**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adja hozzá a könyvtárat referenciaként a projekthez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hozzon létre egy példányt a Prezentáció osztályból.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a szerkeszteni kívánt HTML-dokumentumot.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adjon hozzá egy új szövegsort.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse el a módosított HTML-fájlt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Más fájlok szerkesztése" subTitle="Más formátumú fájlokat is szerkeszthet" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
