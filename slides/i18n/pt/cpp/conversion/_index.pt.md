---
title: Conversão de apresentação do Microsoft PowerPoint para vários formatos usando C++
url: /pt/cpp/conversion/
description: Converta slides do Microsoft PowerPoint em vários arquivos, incluindo HTML, PDF e formatos de imagem em aplicativos baseados em C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversão de apresentação do Microsoft<sup>®</sup> PowerPoint via C++" h2="Códigos de exemplo C++ para diferentes cenários de conversão para converter slides em imagens, HTML, PDF e outros formatos." >}}

{{% blocks/products/pf/feature-page-summary %}}

O processo de conversão dos formatos do Microsoft<sup>®</sup> PowerPoint é simples e fácil de automatizar os processos usando a biblioteca C++ PowerPoint. Os desenvolvedores podem aprimorar o código-fonte relevante e integrá-lo em seus aplicativos. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Conversão Inter de Formatos do Microsoft PowerPoint" %}}
A interconversão de documentos do Microsoft<sup>®</sup> PowerPoint incluindo PPT, PPTX programaticamente é apenas um código de duas linhas. Carregue o arquivo usando [Classe de apresentação](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) e chamando o [método Salvar](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) tendo o arquivo de saída e SaveFormat.OutputFormats como parâmetros.

{{% blocks/products/pf/feature-page-code h3="Código de conversão C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Converter arquivos do PowerPoint para PDF" %}}

A conversão do Microsoft<sup>®</sup> PowerPoint para PDF é um cenário comum devido ao grande compartilhamento de documentos PDF. Os programadores podem automatizá-lo e definir as configurações de conversão de PDF relevantes usando a [classe PDFOptions](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). Algumas das configurações específicas, como nível de compactação de texto, qualidade JPEG [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), nível de conformidade PDF [Compliance] (https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), convertendo slides ocultos [ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), slides selecionados e geração de [Senha](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab42606dbbf983fe00cc45a19565391a7) arquivos PDF protegidos .

{{% blocks/products/pf/feature-page-code h3="Código de conversão de PowerPoint para PDF em C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Salvar slides do Microsoft PowerPoint como imagens" %}}
sempre que há o caso de exibir conteúdo de apresentação na web, então há necessidade de renderizar arquivos como HTML ou imagens JPG, TIFF, PNG, etc. O processo de conversão de slides como imagens é simples. Obtenha todos os slides usando [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) e percorra cada slide um por um. Durante cada iteração, use [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) para a imagem do slide e salve no formato de imagem necessário. 

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint para conversão de imagem" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}