---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PPTX a Word en Java
url: /es/java/conversion/pptx-to-word/
keywords: Convierta PPTX a Word, PPTX a Word, PPTX a DOC, PowerPoint a Word, API de Java, biblioteca de Java
description: Convierta PPTX a Word en Java. Use la API de la biblioteca Java para convertir PowerPoint a Word
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PPTX a Word en Java" h2="Potente API Java multiplataforma para convertir PowerPoint a Word usando código Java sin Microsoft PowerPoint u Office" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PowerPoint a Word en Java" variant="code" %}}

Puede convertir PPTX a Word rápidamente con solo unas pocas líneas de código

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código Java para convertir PowerPoint a Word" >}}
```java
Presentation pres = new Presentation(inputPres);
try {
    Document doc = new Document();
    DocumentBuilder builder = new DocumentBuilder(doc);
    for (ISlide slide : pres.getSlides())
    {
        // generates and inserts slide image
        BufferedImage bitmap = slide.getThumbnail(1, 1);

        builder.insertImage(bitmap);

        // inserts slide's texts
        for (IShape shape : slide.getShapes())
        {
            if (shape instanceof AutoShape)
            {
                builder.writeln(((AutoShape)shape).getTextFrame().getText());
            }
        }

        builder.insertBreak(BreakType.PAGE_BREAK);
    }
    doc.save(outputDoc);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convierta PowerPoint a Word usando Aspose.Slides y Aspose.Words" %}}

[**Aspose.Slides para Java**](https://products.aspose.com/slides/es/java/) y [**Aspose.Words para Java**](https://products.aspose.com/ words/java/) son potentes bibliotecas de Java que se utilizan para manipular y convertir presentaciones de PowerPoint, documentos de Word y otros archivos. Cuando convierte PowerPoint a Word, básicamente está moviendo el contenido de las diapositivas de una presentación a páginas en un documento de Word.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo convertir PPTX a Word" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale **Aspose.Slides para Java** y **Aspose.Words para Java**{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cree una instancia de la clase Presentation y la clase Doc.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue la presentación PPTX que desea convertir a Word.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Genera imágenes y textos a partir del contenido de las diapositivas.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el documento de Word resultante.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Convertidor en línea gratuito"
  description="[Cómo convertir PPT a HTML en Python](https://products.aspose.com/slides/es/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otras conversiones admitidas" subTitle="También puede convertir PowerPoint a archivos en otros formatos" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
