---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Upravte HTML v Javě
url: /cs/java/editor/html/
keywords: Upravit HTML, HTML, Java API, Java Library
description: Upravte HTML v Javě. K úpravě souboru HTML použijte API knihovny Java
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Upravte HTML v Javě" h2="Vysokorychlostní a multiplatformní Java knihovna pro editaci HTML pomocí Java kódu" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Upravte HTML v Javě" variant="code" %}}

Pomocí [**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/) můžete do dokumentu HTML přidat nový řádek textu pomocí pouhých několika řádků kódu.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java kód pro úpravu HTML" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Upravte HTML pomocí Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/) je výkonná knihovna Java, která se používá k manipulaci a úpravám prezentací, dokumentů HTML a dalších souborů. Dokument HTML můžete upravit přidáním nového řádku textu.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak upravit HTML v Javě" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte **Aspose.Slides for Java**. Viz [**Instalace**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte knihovnu jako referenci do svého projektu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vytvořte instanci třídy Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte dokument HTML, který chcete upravit.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte nový řádek textu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte změněný soubor HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Upravte další soubory" subTitle="Můžete také upravovat soubory v jiných formátech" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
