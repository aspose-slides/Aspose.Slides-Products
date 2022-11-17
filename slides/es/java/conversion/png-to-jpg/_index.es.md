---
title: Convertir PNG a JPG en Java
url: /es/java/conversion/png-to-jpg/
keywords: PNG a JPG, Convertir PNG a JPG, API de Java, Biblioteca Java, PNG, JPG
description: Convierte PNG a JPG en Java. Use la API de la biblioteca Java para convertir archivos PNG a JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir PNG a JPG en Java" h2="Biblioteca Java de alta velocidad y multiplataforma que ayuda a desarrollar aplicaciones con la capacidad de crear, fusionar, inspeccionar o convertir archivos de presentación de Microsoft PowerPoint y OpenOffice sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir PNG a JPG en Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/es/java/) es una poderosa biblioteca de Java para crear y manipular archivos de presentación. Además, proporciona formas flexibles de convertir PNG a JPG. Con **Aspose.Slides para Java**, cualquier desarrollador o aplicación puede convertir archivos PNG a JPG con solo unas pocas líneas de código Java.

Como una API moderna de procesamiento de documentos, Aspose.Slides para Java exporta archivos PNG a formatos de archivo JPG rápidamente. La biblioteca de PowerPoint de Aspose le permite convertir PNG a JPGs y muchos otros formatos de archivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta PNG a JPG usando Java" %}}
Para convertir PNG a JPG, deberá crear la presentación desde el archivo PNG y guardarlo como JPG.

{{% blocks/products/pf/agp/code-block title="Código Java para convertir PNG en JPG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "jpeg", new File("image_java_" + index + ".jpg"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo convertir PNG a JPG usando Aspose.Slides para la API de Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para convertir PNG a JPG en Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para Java**](https://products.aspose.com/slides/es/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra los archivos fuente PNG en Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado como archivo JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir PNG a otros formatos admitidos" subTitle="También puede convertir PNG y guardar en otros formatos de archivo. Ver todos los formatos admitidos a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}