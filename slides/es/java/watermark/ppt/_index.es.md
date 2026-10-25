---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Agregar una marca de agua a archivos de presentación PPT con Java
url: /es/java/watermark/ppt/
description: Agregue marcas de agua de texto e imagen a presentaciones PPT en Java con Aspose.Slides for Java.
keywords: agregar marca de agua a PPT, agregar marca de agua de texto a PPT, agregar marca de agua de imagen a PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Agregar una marca de agua a una presentación PPT con Java" h2="Cree aplicaciones Java que inserten marcas de agua de texto o imagen en archivos de presentación con API del lado del servidor." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Agregar una marca de agua a una presentación PPT mediante Java" variant="code" %}}

Con [Aspose.Slides for Java](/slides/es/java/), puede agregar marcas de agua de texto e imagen a presentaciones PPT. Agregue una forma de marca de agua a un patrón de diapositivas para que aparezca en las diapositivas que usan ese patrón.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Agregar una marca de agua de texto a PPT con Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Agregar una marca de agua de imagen a una presentación PPT con Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo agregar una marca de agua a PPT con Java" intro="Siga estos pasos para agregar una marca de agua de texto o imagen a archivos PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo `PPT` con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Seleccione un patrón de diapositivas con el método `getMasters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método `addAutoShape` para agregar una forma de marca de agua.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método `addTextFrame` para agregar el texto de la marca de agua o use `addImage` para una marca de agua de imagen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde la presentación con marca de agua en formato PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Creado con Aspose.Slides" title="Agregue marcas de agua a archivos PPT en línea" description="La aplicación gratuita Aspose.Slides Watermark está creada con [Aspose.Slides for Java](https://products.aspose.com/slides/es/java/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPT." button="Abrir Aspose.Slides Watermark" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides agrega marcas de agua antes de escribir código.
- Agregue una marca de agua de texto o imagen a su archivo PPT.
- Descargue el archivo con marca de agua.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con marcas de agua" subTitle="Con Java, también puede agregar marcas de agua a los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/java/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
