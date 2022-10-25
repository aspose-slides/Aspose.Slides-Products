---
title: Combine PDF, PPT, PPTX y muchos otros formatos de archivo usando C#
url: /es/net/merger/
keywords: Fusionar, Unir, PowerPoint, Presentación, C#, .NET, Aspose
description: Combine varios archivos en C# PPT, PPTX, ODP, PDF, PNG, JPG y muchos más.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Combinar PowerPoint, PDF, PPT u otros documentos en C#" h2="Biblioteca C# de alta velocidad para fusionar PPT, PPTX, PDF, PNG, JPEG y otros formatos." >}}

{{% blocks/products/pf/feature-page-section h2="Combine PPT, PPTX, PDF usando C#" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/es/net/) es una potente biblioteca de C# para crear y manipular archivos de presentación. Además, proporciona formas flexibles de combinar múltiples presentaciones PPT/PPTX. Cuando combina una presentación con otra, está combinando efectivamente sus diapositivas en una sola presentación para obtener un archivo. Aspose.Slides le permite fusionar dos presentaciones de diferentes maneras. Puede fusionar presentaciones con todas sus formas, estilos, textos, formato, comentarios, animaciones, etc. sin tener que preocuparse por la pérdida de calidad o datos.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Combinar presentaciones de PowerPoint en C#" %}}
Para fusionar las presentaciones de PowerPoint, deberá clonar las diapositivas de una presentación a la otra.

{{% blocks/products/pf/agp/code-block title="Combinar archivos PPTX usando C#" offSpacer="true" %}}

```csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        foreach (ISlide slide in presentation2.Slides)
        {
            // Merge slides from source to target 
            presentation1.Slides.AddClone(slide);
        }
    }
    // Save the presentation
    presentation1.Save("merged-presentation.pptx", Export.SaveFormat.Pptx);
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Combinar presentaciones con patrón de diapositivas usando C#" %}}
Este código C# demuestra cómo fusionar varias presentaciones en una y aplicar estilos desde la plantilla de presentación del patrón de diapositivas. Por lo tanto, la presentación de resultados mantendrá el mismo formato de origen y contendrá el formato de la diapositiva maestra de otra presentación.

{{% blocks/products/pf/agp/code-block title="Combinar múltiples PPT en uno solo en C#" offSpacer="true" %}}

``` csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        // Merge first two slides only using slide master
        presentation1.Slides.AddClone(presentation2.Slides[0], presentation1.Masters[0], true);
        presentation1.Slides.AddClone(presentation2.Slides[1], presentation1.Masters[0], true);
    }
    presentation1.Save("merged-presentation-master.pptx", Export.SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo fusionar presentaciones usando Aspose.Slides para .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para fusionar dos archivos PPTX y guardar el resultado como PDF en .NET." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para .NET**](https://docs.aspose.com/slides/net/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto de C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra los archivos PPTX de origen en C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combine archivos PPTX utilizando el método **AddClone**.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde la presentación y obtenga el resultado como un único archivo PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos admitidos para fusionar" subTitle="También puede combinar otros formatos de archivo. Consulte otros formatos admitidos a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}