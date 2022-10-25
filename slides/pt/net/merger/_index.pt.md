---
title: Mesclar PDF, PPT, PPTX e muitos outros formatos de arquivo usando C#
url: /pt/net/merger/
keywords: Mesclar, Juntar, PowerPoint, Apresentação, C#, .NET, Aspose
description: Mescle vários arquivos em C# PPT, PPTX, ODP, PDF, PNG, JPG e muito mais.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Mesclar Powerpoint, PDF, PPT ou outros documentos em C#" h2="Biblioteca C# de alta velocidade para mesclar PPT, PPTX, PDF, PNG, JPEG e outros formatos." >}}

{{% blocks/products/pf/feature-page-section h2="Mesclar PPT, PPTX, PDF usando C#" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/pt/net/) é uma poderosa biblioteca C# para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de combinar várias apresentações PPT/PPTX. Ao mesclar uma apresentação com outra, você está efetivamente combinando seus slides em uma única apresentação para obter um arquivo. Aspose.Slides permite mesclar duas apresentações de maneiras diferentes. Você pode mesclar apresentações com todas as suas formas, estilos, textos, formatação, comentários, animações, etc. sem ter que se preocupar com perda de qualidade ou dados.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mesclar apresentações do PowerPoint em C#" %}}
Para mesclar as apresentações do PowerPoint, você precisará clonar os slides de uma apresentação para outra.

{{% blocks/products/pf/agp/code-block title="Mesclar arquivos PPTX usando C#" offSpacer="true" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Mesclar apresentações com o slide mestre usando C#" %}}
Este código C# demonstra como mesclar várias apresentações em uma e aplicar estilos do modelo de apresentação de slide mestre. Assim, a apresentação do resultado manterá a mesma formatação de origem e conterá a formatação do slide mestre de outra apresentação.

{{% blocks/products/pf/agp/code-block title="Mesclar vários PPT em um único em C #" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Como mesclar apresentações usando Aspose.Slides para .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para mesclar dois arquivos PPTX e salvar o resultado como PDF em .NET." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale o [**Aspose.Slides para .NET**](https://docs.aspose.com/slides/net/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos PPTX de origem em C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combine arquivos PPTX usando o método **AddClone**.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve a apresentação e obtenha o resultado como um único arquivo PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos suportados para mesclar" subTitle="Você também pode combinar outros formatos de arquivo. Veja outros formatos suportados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}