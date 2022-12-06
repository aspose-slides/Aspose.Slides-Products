---
title: Mesclar imagens JPG em C#
url: /pt/net/merger/jpg-to-jpg/
keywords: Mesclar JPG, JPEG para JPG, Juntar JPG, Combinar JPG, C# API, Biblioteca .NET
description: Mesclar JPG para JPG em C#. Use a API da biblioteca .NET para combinar arquivos JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Mesclar JPG em C#" h2="Poderosa API .NET de plataforma cruzada para mesclar imagens JPG usando código C# em plataformas NET Framework, .NET Core, Windows Azure, Mono ou Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Mesclar JPG para JPG usando Aspose.Slides" %}}

[**Aspose.Slides para .NET**](https://products.aspose.com/slides/pt/net/) é uma poderosa biblioteca .NET usada para mesclar e manipular apresentações, imagens e outros arquivos. Ao mesclar JPG com JPG, você está efetivamente combinando duas imagens para obter uma imagem.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Mesclar JPG para JPG em C#" %}}
Usando [**Aspose.Slides for .NET**](https://products.aspose.com/slides/pt/net/), você pode mesclar arquivos JPG rapidamente com apenas algumas linhas de código

{{% blocks/products/pf/agp/code-block title="Código C# para mesclar JPG para JPG" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image1.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 540, image);

    IPPImage image2 = pres.Images.AddImage(File.ReadAllBytes("image2.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 540, image2);

    pres.Slides[0].GetThumbnail(new Size(960, 720)).Save($"merged-image.jpg", ImageFormat.Jpeg);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Como mesclar JPG em C#" >}}


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
Carregue os arquivos JPG que deseja mesclar como molduras.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve a imagem JPG resultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Mesclar outros arquivos" subTitle="Você também pode combinar arquivos em outros formatos para obter um único arquivo" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}