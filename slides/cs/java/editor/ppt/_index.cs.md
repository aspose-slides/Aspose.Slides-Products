---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Upravit PPT v Javě
url: /cs/java/editor/ppt/
keywords: Upravit PPT, Upravit PowerPoint, PPT, PowerPoint, Java API, Java Library
description: Upravit PPT v Javě. K úpravě prezentace v PowerPointu použijte API knihovny Java
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Upravit PPT v Javě" h2="Vysokorychlostní a multiplatformní Java knihovna pro úpravu PPT pomocí kódu Java" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Upravit PPT v Javě" variant="code" %}}

Pomocí [**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/) můžete do dokumentu PPT přidat nový řádek textu pomocí pouhých několika řádků kódu.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java kód pro úpravu PPT" >}}
```java

Presentation pres = new Presentation("pres.ppt");
try {
    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Upravte PPT pomocí Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/) je výkonná knihovna Java používaná k manipulaci a úpravám prezentací. Prezentaci PPT můžete upravit přidáním nového řádku textu.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak upravit PPT v Javě" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte **Aspose.Slides for Java**. Viz [**Instalace**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte knihovnu jako referenci do svého projektu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vytvořte instanci třídy Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte PPT prezentaci, kterou chcete upravit.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte nový řádek textu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte změněný soubor PowerPoint.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Vytvořeno pomocí Aspose.Slides" title="Upravujte soubory PPTX online" description="Bezplatná aplikace Aspose.Slides Editor je vytvořena pomocí [Aspose.Slides for Java](https://products.aspose.com/slides/cs/java/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Editor" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides zpracuje vaše soubory, ještě než napíšete kód.
- Nahrajte soubory PPTX a okamžitě je upravte.
- Uložte a stáhněte upravený soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Upravte další soubory" subTitle="Můžete také upravovat soubory v jiných formátech" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
