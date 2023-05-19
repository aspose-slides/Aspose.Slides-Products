---
title: Buscar texto en archivos de presentación PPTX usando .NET
url: /es/net/search/pptx/
keywords: buscar palabras en PPTX, buscar y reemplazar texto en PPTX, buscar texto en PPTX Presentación
description: Código fuente de C# para buscar texto en la presentación PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Buscar texto PPTX usando C#" h2="Cree sus propias aplicaciones .NET para buscar y reemplazar texto en archivos de presentación utilizando API del lado del servidor. Aprenda a encontrar todas las entradas de una determinada palabra o frase en los documentos de presentación. Busque texto por coincidencia exacta de datos y coincidencia de expresiones regulares." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Buscar y reemplazar texto PPTX Presentación a través de C#" %}}
Se puede realizar una búsqueda básica de documentos y reemplazar texto en contenidos, comentarios, notas de diapositivas o metadatos con las API de Aspose.Slides for .NET con solo unas pocas líneas de código. Use coincidencia de expresiones regulares, coincidencia de mayúsculas y minúsculas para buscar texto en la presentación. Busque texto en títulos, contenido, pie de página o encabezado.
{{% blocks/products/pf/agp/code-block title="Buscar texto PPTX Presentación usando C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.pptx"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo buscar texto en PPTX a través de C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para buscar archivos de texto PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue PPTX con una instancia de Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use el método [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) para buscar y reemplazar texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado en formato PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="En línea PPTX Buscar demostraciones en vivo" sectionDescription="Busque y reemplace texto en contenidos, comentarios o metadatos en documentos PPTX ahora mismo." >}}

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de búsqueda admitidos" subTitle="Con C#, también puede buscar texto en los siguientes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}