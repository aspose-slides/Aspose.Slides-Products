---
title: Redigir arquivos de apresentação PPT usando C++
url: /pt/cpp/redaction/ppt/
keywords: Redigir PPT, localizar e substituir texto em PPT, atualizar PPT Apresentação
description: Código-fonte C++ para localizar e substituir texto na apresentação PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redigir PPT usando C++" h2="Crie seus próprios aplicativos C++ para localizar e substituir texto em arquivos de apresentação usando APIs do lado do servidor. Saiba como pesquisar e substituir texto em conteúdo, comentários ou metadados de apresentações PPT" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Redigir apresentação PPT via C++" %}}
Uma pesquisa básica de documentos e substituição de texto em conteúdos, comentários, notas de slides ou metadados com Aspose.Slides for C++ APIs pode ser feita com apenas algumas linhas de código. Encontre e substitua texto no PowerPoint e no OpenOffice. Edite texto, comentários e metadados na apresentação por meio da correspondência de dados regexp.
{{% blocks/products/pf/agp/code-block title="Redigir apresentação PPT usando C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.ppt");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.ppt", SaveFormat::Ppt);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como redigir PPT via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para redigir arquivos PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregue PPT com uma instância de Apresentação.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use o método [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) para localizar e substituir o texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado no formato PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de redação PPT on-line" sectionDescription="Pesquise e substitua texto em conteúdos, comentários ou metadados em documentos PPT agora mesmo." >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de edição suportados" subTitle="Usando C++, você também pode redigir os seguintes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}