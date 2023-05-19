---
title: Buscar texto en archivos de presentación PPT usando Java
url: /es/java/search/ppt/
keywords: buscar palabras en PPT, buscar y reemplazar texto en PPT, buscar texto en PPT Presentación
description: Código fuente de Java para buscar texto en la presentación PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Buscar texto PPT usando Java" h2="Cree sus propias aplicaciones Java para buscar y reemplazar texto en archivos de presentación utilizando API del lado del servidor. Aprenda a encontrar todas las entradas de una determinada palabra o frase en los documentos de presentación. Busque texto por coincidencia exacta de datos y coincidencia de expresiones regulares." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Buscar y reemplazar texto PPT Presentación a través de Java" %}}
Se puede realizar una búsqueda básica de documentos y reemplazar texto en contenidos, comentarios, notas de diapositivas o metadatos con las API de Aspose.Slides for Java con solo unas pocas líneas de código. Use coincidencia de expresiones regulares, coincidencia de mayúsculas y minúsculas para buscar texto en la presentación. Busque texto en títulos, contenido, pie de página o encabezado.
{{% blocks/products/pf/agp/code-block title="Buscar texto PPT Presentación usando Java" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Cómo buscar texto en PPT a través de Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para buscar archivos de texto PPT." >}}

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

{{< blocks/products/pf/agp/demobox sectionTitle="En línea PPT Buscar demostraciones en vivo" sectionDescription="Busque y reemplace texto en contenidos, comentarios o metadatos en documentos PPT ahora mismo." >}}

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de búsqueda admitidos" subTitle="Con Java, también puede buscar texto en los siguientes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}