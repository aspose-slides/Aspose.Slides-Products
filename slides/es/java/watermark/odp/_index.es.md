---
title: Agregar marca de agua a ODP archivos de presentación usando Java
url: /es/java/watermark/odp/
keywords: Añadir marca de agua ODP, Añadir marca de agua de texto ODP, Añadir marca de agua de imagen ODP
description: Código fuente de Java para agregar marca de agua a la presentación ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Agregar marca de agua a la presentación ODP usando Java" h2="Cree sus propias aplicaciones Java para insertar texto o marca de agua de imagen en presentaciones PPT, PPTX u ODP utilizando las API del lado del servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Agregar marca de agua a la presentación ODP a través de Java" %}}
Usando Aspose.Slides for Java, puede agregar una marca de agua a la presentación ODP. Las marcas de agua son una parte esencial de cualquier presentación. Se utilizan para proteger el contenido de la presentación de ser copiado o utilizado sin permiso. Una marca de agua es una imagen o texto visible o invisible que se coloca encima de la presentación. Se puede utilizar para identificar al propietario de la presentación y para evitar el uso no autorizado. Las marcas de agua también se pueden usar para agregar un toque profesional a la presentación y hacer que se vea más pulida. 
{{% blocks/products/pf/agp/code-block title="Agregar marca de agua de texto a ODP usando Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.odp", SaveFormat.Odp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Agregue una marca de agua de imagen a la presentación ODP usando Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.odp", SaveFormat.Odp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo agregar una marca de agua a ODP a través de Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para agregar una marca de agua de texto a los archivos ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue ODP con una instancia de Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Seleccione la presentación maestra
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregar tipo de forma usando el método AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue texto de marca de agua usando el método AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado en formato ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos compatibles" subTitle="Con Java, también puede agregar una marca de agua a los siguientes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}