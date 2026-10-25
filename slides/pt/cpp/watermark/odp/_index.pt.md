---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Adicionar marca d'água a apresentações ODP com C++
url: /pt/cpp/watermark/odp/
description: Adicione marcas d'água de texto ou imagem a apresentações ODP em C++. Use o Aspose.Slides for C++ para colocar marcas d'água nos slides.
keywords: adicionar marca d'água a ODP, adicionar marca d'água de texto a ODP, adicionar marca d'água de imagem a ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Adicionar marca d'água a uma apresentação ODP com C++" h2="Use o Aspose.Slides for C++ para adicionar marcas d'água de texto ou imagem a arquivos de apresentação sem o Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Adicionar marca d'água a uma apresentação ODP via C++" variant="code" %}}

O Aspose.Slides for C++ permite adicionar marcas d'água de texto ou imagem a apresentações ODP. Adicione uma forma de marca d'água ao slide mestre com `AddAutoShape`, adicione texto com `AddTextFrame` ou preencha a forma com uma imagem carregada por meio de `File::ReadAllBytes` e `AddImage`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Adicionar marca d'água de texto a ODP com C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Adicionar marca d'água de imagem a uma apresentação ODP com C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como adicionar marca d'água a ODP com C++" intro="Siga estas etapas para adicionar uma marca d'água de texto ou imagem a arquivos ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo ODP com a classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Selecione o slide mestre na coleção `Presentation::get_Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adicione uma forma de marca d'água com o método `AddAutoShape`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adicione o texto da marca d'água com o método `AddTextFrame` ou defina um preenchimento de imagem com `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve o arquivo com marca d'água com `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Criado com Aspose.Slides" title="Adicione marcas d'água a arquivos ODP online" description="O aplicativo gratuito Aspose.Slides Watermark é criado com [Aspose.Slides for C++](https://products.aspose.com/slides/pt/cpp/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos ODP." button="Abrir Aspose.Slides Watermark" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides adiciona marcas d'água antes de escrever código.
- Adicione uma marca d'água de texto ou imagem ao seu arquivo ODP.
- Baixe o arquivo com marca d'água.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com marca d'água" subTitle="Com C++, você também pode adicionar marcas d'água aos seguintes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/cpp/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
