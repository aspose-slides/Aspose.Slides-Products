---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sloučit obrázky JPG v Javě
url: /cs/java/merger/jpg-to-jpg/
keywords: Sloučit JPG, JPEG do JPG, připojit JPG, kombinovat JPG, Java API, Java Library
description: Sloučit JPG do JPG v Javě. Ke kombinování souborů JPG použijte API knihovny Java
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sloučit JPG v Javě" h2="Vysokorychlostní a multiplatformní Java knihovna pro slučování obrázků JPG pomocí kódu Java" related="PNG,HTML,IMAGE,JPG,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sloučit JPG do JPG v Javě" variant="code" %}}

Pomocí [**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/) můžete rychle sloučit soubory JPG pomocí několika řádků kódu

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java kód pro sloučení JPG do JPG" >}}
```java

Presentation pres = new Presentation();
try {
    IPPImage image1 = pres.getImages().addImage(Files.readAllBytes("image1.jpg"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image1);

    IPPImage image2 = pres.getImages().addImage(Files.readAllBytes("image2.jpg"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail();
        ImageIO.write(bufferedImage, "JPEG", new File("image_java_" + index + ".jpg"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sloučit JPG do JPG pomocí Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/) je výkonná knihovna Java, která se používá ke slučování a manipulaci s prezentacemi, obrázky a dalšími soubory. Když sloučíte JPG do JPG, efektivně kombinujete dva obrázky a získáte jeden obrázek.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak sloučit JPG v Javě" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte **Aspose.Slides for Java**. Viz [**Instalace**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte knihovnu jako referenci do svého projektu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vytvořte instanci třídy Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubory JPG, které chcete sloučit jako rámečky obrázků.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte výsledný obrázek JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Vytvořeno pomocí Aspose.Slides" title="Sloučení souborů JPG online" description="Bezplatná aplikace Aspose.Slides Merger je vytvořena pomocí [Aspose.Slides for Java](https://products.aspose.com/slides/cs/java/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory JPG." button="Otevřít Aspose.Slides Merger" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides slučuje soubory, ještě než začnete psát kód.
- Nahrajte několik souborů JPG a spojte je do jednoho.
- Stáhněte sloučený výsledek jako jeden soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Sloučit další soubory" subTitle="Můžete také kombinovat soubory v jiných formátech a získat tak jeden soubor" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/cs/java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
