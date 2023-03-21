---
title: Convertir SVG a PNG en Java
url: /es/java/conversion/svg-to-png/
keywords: SVG a PNG, Convertir SVG a PNG, API de Java, Biblioteca Java, SVG, PNG
description: Convierte SVG a PNG en Java. Use la API de la biblioteca Java para convertir archivos SVG a PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir SVG a PNG en Java" h2="Biblioteca Java de alta velocidad y multiplataforma que ayuda a desarrollar aplicaciones con la capacidad de crear, fusionar, inspeccionar o convertir archivos de presentación de Microsoft PowerPoint y OpenOffice sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir SVG a PNG en Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/es/java/) es una poderosa biblioteca de Java para crear y manipular archivos de presentación. Además, proporciona formas flexibles de convertir SVG a PNG. Con **Aspose.Slides para Java**, cualquier desarrollador o aplicación puede convertir archivos SVG a PNG con solo unas pocas líneas de código Java.

Como una API moderna de procesamiento de documentos, Aspose.Slides para Java exporta archivos SVG a formatos de archivo PNG rápidamente. La biblioteca de PowerPoint de Aspose le permite convertir SVG a PNGs y muchos otros formatos de archivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta SVG a PNG usando Java" %}}
Para convertir SVG a PNG, deberá crear la presentación desde el archivo SVG y guardarlo como PNG.

{{% blocks/products/pf/agp/code-block title="Código Java para convertir SVG en PNG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    String svgContent = new String(Files.readAllBytes(Paths.get("image.svg")));
    ISvgImage svgImage = new SvgImage(svgContent);
    IPPImage ppImage = pres.getImages().addImage(svgImage);
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 
			ppImage.getWidth(), ppImage.getHeight(), ppImage);
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

{{< blocks/products/pf/feature-page-section  h2="Cómo convertir SVG a PNG usando Aspose.Slides para la API de Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para convertir SVG a PNG en Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para Java**](https://products.aspose.com/slides/es/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra los archivos fuente SVG en Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado como archivo PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertidor en línea gratuito" sectionDescription="[Cómo convertir PPT a HTML en Python](https://products.aspose.com/slides/es/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir SVG a otros formatos admitidos" subTitle="También puede convertir SVG y guardar en otros formatos de archivo. Ver todos los formatos admitidos a continuación" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}