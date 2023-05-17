---
title: Redactar PPT archivos de presentación usando Java
url: /es/java/redaction/ppt/
keywords: Redactar PPT, buscar y reemplazar texto en PPT, actualizar PPT Presentación
description: Código fuente de Java para buscar y reemplazar texto en la presentación PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redactar PPT usando Java" h2="Cree sus propias aplicaciones Java para buscar y reemplazar texto en archivos de presentación utilizando las API del lado del servidor. Aprenda a buscar y reemplazar texto en contenido, comentarios o metadatos de presentaciones PPT" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Redactar PPT presentación a través de Java" %}}
Se puede realizar una búsqueda básica de documentos y reemplazar texto en contenidos, comentarios, notas de diapositivas o metadatos con las API de Aspose.Slides for Java con solo unas pocas líneas de código. Busque y reemplace texto en PowerPoint y OpenOffice. Edite texto, comentarios, metadatos en la presentación a través de la coincidencia de datos de expresiones regulares.
{{% blocks/products/pf/agp/code-block title="Redactar la presentación PPT usando Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo redactar PPT a través de Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para Redactar archivos PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue PPT con una instancia de Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use el método [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) para buscar y reemplazar texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado en formato PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Demostraciones en vivo de redacción PPT en línea" sectionDescription="Busque y reemplace texto en contenidos, comentarios o metadatos en documentos PPT ahora mismo." >}}

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de redacción admitidos" subTitle="Usando Java, también puede redactar los siguientes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}