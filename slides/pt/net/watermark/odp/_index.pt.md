---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Adicionar marca d'água a apresentações ODP com C#
url: /pt/net/watermark/odp/
description: Adicione marcas d'água de texto e imagem a apresentações ODP em C# com o Aspose.Slides for .NET.
keywords: adicionar marca d'água a ODP, adicionar marca d'água de texto a ODP, adicionar marca d'água de imagem a ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Adicionar marca d'água a uma apresentação ODP com C#" h2="Crie aplicativos .NET que inserem marcas d'água de texto ou imagem em arquivos de apresentação." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Adicionar marca d'água a uma apresentação ODP via C#" variant="code" %}}

Com o [Aspose.Slides for .NET](/slides/pt/net/), você pode adicionar marcas d'água de texto e imagem a apresentações ODP. Adicione uma forma de marca d'água a um slide mestre para que ela apareça nos slides que usam esse mestre.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Adicionar marca d'água de texto a ODP com C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Adicionar marca d'água de imagem a uma apresentação ODP com C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como adicionar marca d'água a ODP com C#" intro="Siga estas etapas para adicionar uma marca d'água de texto ou imagem a arquivos ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo `ODP` com a classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Selecione um slide mestre na coleção `Presentation.Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método `AddAutoShape` para adicionar uma forma de marca d'água.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método `AddTextFrame` para adicionar o texto da marca d'água ou use `AddImage` para uma marca d'água de imagem.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve o arquivo com marca d'água com `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Criado com Aspose.Slides" title="Adicione marcas d'água a arquivos ODP online" description="O aplicativo gratuito Aspose.Slides Watermark é criado com [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos ODP." button="Abrir Aspose.Slides Watermark" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides adiciona marcas d'água antes de escrever código.
- Adicione uma marca d'água de texto ou imagem ao seu arquivo ODP.
- Baixe o arquivo com marca d'água.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com marca d'água" subTitle="Com C#, você também pode adicionar marcas d'água aos seguintes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
