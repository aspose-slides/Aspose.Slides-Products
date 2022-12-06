---
title: Mesclar PNG para PDF em C#
url: /pt/net/merger/png-to-pdf/
keywords: PNG para PDF, Mesclar PNG para PDF, Juntar PNG para PDF, PDF, PNG, C# API, Biblioteca .NET
description: Mesclar PNG para PDF em C#. Use a API da biblioteca .NET para combinar PNG e PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Mesclar PNG para PDF em C#" h2="Poderosa API .NET multiplataforma para mesclar arquivos PNG para PDF usando código C# em plataformas NET Framework, .NET Core, Windows Azure, Mono ou Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Mesclar PNG para PDF usando Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/pt/net/) é uma poderosa biblioteca .NET usada para criar, converter, mesclar e manipular apresentações, imagens e outros arquivos. Ao mesclar PNG com PDF, você está efetivamente combinando imagens PNG para obter um único arquivo PDF.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Mesclar PNG para PDF em C#" %}}
Usando [**Aspose.Slides for .NET**](https://products.aspose.com/slides/pt/net/), você pode mesclar PNG para PDF rapidamente com apenas algumas linhas de código

{{% blocks/products/pf/agp/code-block title="Código C# para mesclar PNG para PDF" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage png1 = pres.Images.AddImage(File.ReadAllBytes("image1.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, png1);

    IPPImage png2 = pres.Images.AddImage(File.ReadAllBytes("image2.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, png2);

    pres.Save("MergedFile.pdf", SaveFormat.Pdf);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Como mesclar PNG para PDF em C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instale **Aspose.Slides para .NET**. Consulte [**Instalação**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione a biblioteca como referência em seu projeto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crie uma instância da classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregue as imagens PNG que deseja mesclar como molduras.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o PDF resultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Mesclar outros arquivos" subTitle="Você também pode combinar arquivos em outros formatos para obter um único arquivo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}