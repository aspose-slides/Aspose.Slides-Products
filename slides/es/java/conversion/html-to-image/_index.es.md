---
title: Convertir HTML a Image en Java
url: /es/java/conversion/html-to-image/
keywords: HTML a Image, Convertir HTML a Image, API de Java, Biblioteca Java, HTML, Image
description: Convierte HTML a Image en Java. Use la API de la biblioteca Java para convertir archivos HTML a Image
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir HTML a Image en Java" h2="Biblioteca Java de alta velocidad y multiplataforma que ayuda a desarrollar aplicaciones con la capacidad de crear, fusionar, inspeccionar o convertir archivos de presentación de Microsoft PowerPoint y OpenOffice sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir HTML a Image en Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/es/java/) es una poderosa biblioteca de Java para crear y manipular archivos de presentación. Además, proporciona formas flexibles de convertir HTML a Image. Con **Aspose.Slides para Java**, cualquier desarrollador o aplicación puede convertir archivos HTML a Image con solo unas pocas líneas de código Java.

Como una API moderna de procesamiento de documentos, Aspose.Slides para Java exporta archivos HTML a formatos de archivo Image rápidamente. La biblioteca de PowerPoint de Aspose le permite convertir HTML a Images y muchos otros formatos de archivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta HTML a Image usando Java" %}}
Para convertir HTML a Image, deberá crear la presentación desde el archivo HTML y guardarlo como Image.

{{% blocks/products/pf/agp/code-block title="Código Java para convertir HTML en Image" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    TextReader tr = new StreamReader("file.html");
    pres.getSlides().addFromHtml(tr);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo convertir HTML a Image usando Aspose.Slides para la API de Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para convertir HTML a Image en Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para Java**](https://products.aspose.com/slides/es/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra los archivos fuente HTML en Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado como archivo Image.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertidor en línea gratuito" sectionDescription="[Cómo convertir PPT a HTML en Python](https://products.aspose.com/slides/es/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir HTML a otros formatos admitidos" subTitle="También puede convertir HTML y guardar en otros formatos de archivo. Ver todos los formatos admitidos a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}