---
title: Eliminar la anotación ODP usando Java
weight: 1790
url: /es/java/annotation/odp/ 
description: Código de muestra de Java para eliminar anotaciones en formato ODP en Java Runtime Environment para aplicaciones de escritorio y aplicaciones JSP/JSF.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Eliminar comentarios y autores de comentarios de ODP en Java" h2="Cree sus propias aplicaciones Java para manipular comentarios y autores en archivos de documentos utilizando las API del lado del servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="Eliminar comentarios de ODP a través de Java" %}}
Para eliminar las anotaciones del archivo ODP, utilizaremos la API [Aspose.Slides for Java](https://products.aspose.com/slides/es/java/), que es una API rica en funciones, potente y fácil de usar. API de manipulación de documentos para la plataforma Java.
{{% blocks/products/pf/agp/code-block title="Eliminar anotaciones de ODP - Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.odp");
try {
    // Deletes all comments from the presentation
    for (ICommentAuthor author : presentation.getCommentAuthors())
    {
        author.getComments().clear();
    }

    // Deletes all authors
    presentation.getCommentAuthors().clear();

    presentation.save("example_out.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Cómo eliminar comentarios de ODP a través de Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale **Aspose.Slides para Java**. Consulte [**Instalación**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue ODP con una instancia de la clase Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterar sobre todos los autores de ODP cargado
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Eliminar todos los comentarios de un autor
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Eliminar todos los autores al final
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de anotación admitidos" subTitle="Usando Java, uno puede anotar fácilmente otros formatos, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}