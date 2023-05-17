---
title: Redactar ODP archivos de presentación usando .NET
url: /es/net/redaction/odp/
keywords: Redactar ODP, buscar y reemplazar texto en ODP, actualizar ODP Presentación
description: Código fuente de C# para buscar y reemplazar texto en la presentación ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redactar ODP usando C#" h2="Cree sus propias aplicaciones .NET para buscar y reemplazar texto en archivos de presentación utilizando las API del lado del servidor. Aprenda a buscar y reemplazar texto en contenido, comentarios o metadatos de presentaciones ODP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Redactar ODP presentación a través de C#" %}}
Se puede realizar una búsqueda básica de documentos y reemplazar texto en contenidos, comentarios, notas de diapositivas o metadatos con las API de Aspose.Slides for .NET con solo unas pocas líneas de código. Busque y reemplace texto en PowerPoint y OpenOffice. Edite texto, comentarios, metadatos en la presentación a través de la coincidencia de datos de expresiones regulares.
{{% blocks/products/pf/agp/code-block title="Redactar la presentación ODP usando C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.odp"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo redactar ODP a través de C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para Redactar archivos ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue ODP con una instancia de Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use el método [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) para buscar y reemplazar texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado en formato ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Demostraciones en vivo de redacción ODP en línea" sectionDescription="Busque y reemplace texto en contenidos, comentarios o metadatos en documentos ODP ahora mismo." >}}

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de redacción admitidos" subTitle="Usando C#, también puede redactar los siguientes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}