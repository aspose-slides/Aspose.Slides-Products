---
title: Mesclar SVG para PNG em C#
url: /pt/net/merger/svg-to-png/
keywords: Mesclar SVG para PNG, SVG para PNG, Juntar SVG para PNG, Combinar SVG para PNG, C# API, Biblioteca .NET
description: Mesclar SVG para PNG em C#. Use a API da biblioteca .NET para combinar arquivos SVG e PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Mesclar SVG para PNG em C#" h2="Poderosa API .NET de plataforma cruzada para mesclar imagens SVG para PNG usando código C# em plataformas NET Framework, .NET Core, Windows Azure, Mono ou Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Mesclar SVG para PNG usando Aspose.Slides" %}}

[**Aspose.Slides para .NET**](https://products.aspose.com/slides/pt/net/) é uma poderosa biblioteca .NET usada para mesclar e manipular apresentações, imagens e outros arquivos. Ao mesclar SVG com PNG, você está efetivamente combinando imagens SVG para obter uma imagem PNG.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Mesclar SVG para PNG em C#" %}}
Usando [**Aspose.Slides for .NET**](https://products.aspose.com/slides/pt/net/), você pode mesclar arquivos SVG para PNG rapidamente com apenas algumas linhas de código

{{% blocks/products/pf/agp/code-block title="Código C# para mesclar SVG para PNG" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    ISvgImage svgImage = new SvgImage("doc.svg");
    IPPImage image = pres.Images.AddImage(svgImage);
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 540, image);

    ISvgImage svgImage2 = new SvgImage("doc.svg");
    IPPImage image2 = pres.Images.AddImage(svgImage);
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 540, image2);

    pres.Slides[0].GetThumbnail(new Size(960, 720)).Save("MergedFile.png", ImageFormat.Png);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Como mesclar SVG para PNG em C#" >}}


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
Carregue os arquivos SVG que deseja mesclar.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve a imagem PNG resultante.
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}