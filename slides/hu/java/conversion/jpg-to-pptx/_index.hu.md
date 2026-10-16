---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: JPG konvertálása PPTX-re Java nyelven
url: /hu/java/conversion/jpg-to-pptx/
keywords: JPG konvertálása PPTX-re, JPG konvertálása PPTX-re, PowerPoint, JPG, PPTX, Java API, Java Library
description: JPG konvertálása PPTX-re Java nyelven. Használja a Java könyvtár API-t a JPG képek PowerPoint formátumba konvertálásához
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="JPG konvertálása PPTX-re Java nyelven" h2="Hatékony, többplatformos Java API JPG-nek PPTX-vé konvertálásához Java kód használatával" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="JPG konvertálása PPTX-re Java nyelven" variant="code" %}}

Az [**Aspose.Slides for Java**](https://products.aspose.com/slides/hu/java/) segítségével néhány sornyi kóddal JPG-képet PowerPoint prezentációvá alakíthat át:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java kód a JPG PPTX formátumba konvertálásához" >}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

	pres.save("pres.pptx", SaveFormat.Pptx);
} finally {
	if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="JPG konvertálása PPTX-re az Aspose.Slides segítségével" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hu/java/) egy hatékony Java-könyvtár, amellyel PowerPoint-prezentációkat, PDF-eket, HTML-dokumentumokat és egyebeket hozhatnak létre, konvertálhatnak és kezelhetnek. fájlokat. Amikor JPG-t PPTX-re konvertál, lényegében egy PowerPoint-prezentációt hoz létre, amely JPG-képeken alapuló diákat tartalmaz.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan lehet JPG-t PPTX-re konvertálni Java-ban" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az **Aspose.Slides for Java** programot. Lásd: [**Telepítés**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adja hozzá a könyvtárat referenciaként a projekthez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hozzon létre egy példányt a Prezentáció osztályból.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPTX formátumba konvertálni kívánt JPG képet.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse el a kapott fájlt PPTX-prezentációként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ingyenes online konverter"
  description="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Egyéb támogatott PowerPoint-konverziók" subTitle="Más formátumú fájlokat is konvertálhat PowerPointba" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
