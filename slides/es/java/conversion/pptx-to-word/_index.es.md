---
title: Convertir PPTX a Word en Java
url: /es/java/conversion/pptx-to-word/
keywords: Convierta PPTX a Word, PPTX a Word, PPTX a DOC, PowerPoint a Word, API de Java, biblioteca de Java
description: Convierta PPTX a Word en Java. Use la API de la biblioteca Java para convertir PowerPoint a Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir PPTX a Word en Java" h2="Potente API Java multiplataforma para convertir PowerPoint a Word usando código Java sin Microsoft PowerPoint u Office" >}}

{{% blocks/products/pf/feature-page-section h2="Convierta PowerPoint a Word usando Aspose.Slides y Aspose.Words" %}}

[**Aspose.Slides para Java**](https://products.aspose.com/slides/es/java/) y [**Aspose.Words para Java**](https://products.aspose.com/ words/java/) son potentes bibliotecas de Java que se utilizan para manipular y convertir presentaciones de PowerPoint, documentos de Word y otros archivos. Cuando convierte PowerPoint a Word, básicamente está moviendo el contenido de las diapositivas de una presentación a páginas en un documento de Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Convertir PowerPoint a Word en Java" %}}
Puede convertir PPTX a Word rápidamente con solo unas pocas líneas de código

{{% blocks/products/pf/agp/code-block title="Código Java para convertir PowerPoint a Word" offSpacer="true" %}}
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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cómo convertir PPTX a Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instale **Aspose.Slides para Java** y **Aspose.Words para Java** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cree una instancia de la clase Presentation y la clase Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue la presentación PPTX que desea convertir a Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Genera imágenes y textos a partir del contenido de las diapositivas.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde el documento de Word resultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertidor en línea gratuito" sectionDescription="[Cómo convertir PPT a HTML en Python](https://products.aspose.com/slides/es/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir PowerPoint a archivos en otros formatos" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}