---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Přidání vodoznaku do souborů prezentací PPTX v Javě
url: /cs/java/watermark/pptx/
description: Přidávejte textové a obrázkové vodoznaky do prezentací PPTX v Javě pomocí Aspose.Slides for Java.
keywords: přidat vodoznak do PPTX, přidat textový vodoznak do PPTX, přidat obrázkový vodoznak do PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Přidání vodoznaku do prezentace PPTX v Javě" h2="Vytvářejte aplikace v Javě, které pomocí serverových API vkládají textové nebo obrázkové vodoznaky do souborů prezentací." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Přidání vodoznaku do prezentace PPTX pomocí Javy" variant="code" %}}

Pomocí [Aspose.Slides for Java](/slides/cs/java/) můžete do prezentací PPTX přidávat textové a obrázkové vodoznaky. Přidejte tvar vodoznaku na předlohu snímků, aby se vodoznak zobrazil na snímcích, které tuto předlohu používají.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Přidání textového vodoznaku do PPTX v Javě" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Přidání obrázkového vodoznaku do prezentace PPTX v Javě" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak přidat vodoznak do PPTX v Javě" intro="Pomocí těchto kroků přidáte do souborů PPTX textový nebo obrázkový vodoznak." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor `PPTX` pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vyberte předlohu snímků pomocí metody `getMasters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu `addAutoShape` a přidejte tvar vodoznaku.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte metodu `addTextFrame` a přidejte text vodoznaku, nebo pro obrázkový vodoznak použijte `addImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte prezentaci s vodoznakem ve formátu PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Vytvořeno pomocí Aspose.Slides" title="Přidávejte vodoznaky do souborů PPTX online" description="Bezplatná aplikace Aspose.Slides Watermark je vytvořena pomocí [Aspose.Slides for Java](https://products.aspose.com/slides/cs/java/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Watermark" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides přidává vodoznaky, ještě než napíšete kód.
- Přidejte do svého souboru PPTX textový nebo obrázkový vodoznak.
- Stáhněte soubor s vodoznakem.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další formáty podporující vodoznaky" subTitle="V Javě můžete přidávat vodoznaky také do následujících formátů." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
