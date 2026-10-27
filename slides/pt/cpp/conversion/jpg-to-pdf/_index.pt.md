---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter JPG para PDF em C++
url: /pt/cpp/conversion/jpg-to-pdf/
keywords: JPG para PDF, Converter JPG para PDF, API C++, Biblioteca C++, JPG, PDF
description: Converta JPG para PDF em C++. Use a API da biblioteca C++ para converter arquivos JPG em PDFs
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converter JPG para PDF em C++" h2="Biblioteca C++ de plataforma cruzada e de alta velocidade que ajuda no desenvolvimento de aplicativos com a capacidade de criar, mesclar, inspecionar ou converter arquivos de apresentação do Microsoft PowerPoint e OpenOffice sem o uso de qualquer software como Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter JPG para PDF usando C++" variant="code" %}}

Para converter o JPG para PDF, você precisará criar a apresentação do arquivo JPG e salvá-lo como PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código C++ para converter JPG em PDF" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter JPG para PDF em C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/pt/cpp/) é uma poderosa biblioteca C++ para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter JPG em PDF. Usando **Aspose.Slides para C++**, qualquer desenvolvedor ou aplicativo pode converter arquivos JPG em PDF com apenas algumas linhas de código C++.

Como uma API moderna de processamento de documentos, o Aspose.Slides for C++ exporta arquivos JPG para formatos de arquivo PDF rapidamente. A biblioteca Aspose PowerPoint permite converter JPG para PDFs e muitos outros formatos de arquivo

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como converter JPG para PDF usando Aspose.Slides para C++ API" intro="Estas são as etapas para converter JPG em PDF em C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale [**Aspose.Slides para C++**](https://products.aspose.com/slides/pt/cpp/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra os arquivos de origem JPG em C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve o resultado como arquivo PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Criado com Aspose.Slides" title="Converter JPG para PDF online" description="O aplicativo gratuito Aspose.Slides Conversion é criado com [Aspose.Slides for C++](https://products.aspose.com/slides/pt/cpp/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos JPG." button="Abrir Aspose.Slides Conversion" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" upload="Arraste ou envie seu arquivo" saveAs="Salvar como" convert="Converter" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides converte arquivos antes de escrever código.
- Envie arquivos JPG e salve-os como PDF.
- Baixe o resultado ou converta mais arquivos.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Converter JPG para outros formatos suportados" subTitle="Você também pode converter JPG e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
