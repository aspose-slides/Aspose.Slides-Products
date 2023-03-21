---
title: Converter JPG para PDF em C++
url: /pt/cpp/conversion/jpg-to-pdf/
keywords: JPG para PDF, Converter JPG para PDF, API C++, Biblioteca C++, JPG, PDF
description: Converta JPG para PDF em C++. Use a API da biblioteca C++ para converter arquivos JPG em PDFs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter JPG para PDF em C++" h2="Biblioteca C++ de plataforma cruzada e de alta velocidade que ajuda no desenvolvimento de aplicativos com a capacidade de criar, mesclar, inspecionar ou converter arquivos de apresentação do Microsoft PowerPoint e OpenOffice sem o uso de qualquer software como Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converter JPG para PDF em C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/pt/cpp/) é uma poderosa biblioteca C++ para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter JPG em PDF. Usando **Aspose.Slides para C++**, qualquer desenvolvedor ou aplicativo pode converter arquivos JPG em PDF com apenas algumas linhas de código C++.

Como uma API moderna de processamento de documentos, o Aspose.Slides for C++ exporta arquivos JPG para formatos de arquivo PDF rapidamente. A biblioteca Aspose PowerPoint permite converter JPG para PDFs e muitos outros formatos de arquivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converter JPG para PDF usando C++" %}}
Para converter o JPG para PDF, você precisará criar a apresentação do arquivo JPG e salvá-lo como PDF.

{{% blocks/products/pf/agp/code-block title="Código C++ para converter JPG em PDF" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como converter JPG para PDF usando Aspose.Slides para C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para converter JPG em PDF em C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para C++**](https://products.aspose.com/slides/pt/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos de origem JPG em C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado como arquivo PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Conversor Online Gratuito" sectionDescription="[Como converter PPT para HTML em Python](https://products.aspose.com/slides/pt/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converter JPG para outros formatos suportados" subTitle="Você também pode converter JPG e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/conversion/jpg-to-png/" name="JPG TO PNG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}