---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Převést obrázek na PPT v Javě
url: /cs/java/conversion/image-to-ppt/
keywords: Převést obrázek na PPT, obrázek na PPT, PowerPoint, obrázek, PPT, Java API, Java Library
description: Převést obrázek na PPT v Javě. K převodu obrázku do PowerPointu použijte API knihovny Java
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Převést obrázek na PPT v Javě" h2="Vysokorychlostní a multiplatformní knihovna Java, která pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převést obrázek na PPT v Javě" variant="code" %}}

Pomocí [**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/) můžete převést obrázek na prezentaci PowerPoint pomocí několika řádků kódu:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java kód pro převod obrázku do PPT" >}}
```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.save("presentation.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Převést obrázek na PPT pomocí Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/) je výkonná knihovna Java, která se používá k vytváření, převodu a manipulaci s prezentacemi PowerPoint, PDF, HTML dokumenty a dalšími soubory. Když převedete obrázek na PPT, v podstatě vytváříte prezentaci PowerPoint, která obsahuje snímky založené na těchto obrázcích.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak převést obrázek na PPT pomocí Aspose.Slides pro Java API" intro="Toto jsou kroky k převodu obrázku na PPT v Javě." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte [**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vytvořte instanci třídy Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte obrázek, který chcete převést na PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte výsledný soubor jako prezentaci PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Zdarma online konvertor"
  description="[Jak převést PPT na HTML v Pythonu](https://products.aspose.com/slides/cs/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované převody PowerPoint" subTitle="Můžete také převést soubory v jiných formátech do PowerPointu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
