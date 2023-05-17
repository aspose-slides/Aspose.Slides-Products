---
title: Redigir arquivos de apresentação ODP usando C++
url: /pt/cpp/redaction/odp/
keywords: Redigir ODP, localizar e substituir texto em ODP, atualizar ODP Apresentação
description: Código-fonte C++ para localizar e substituir texto na apresentação ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redigir ODP usando C++" h2="Crie seus próprios aplicativos C++ para localizar e substituir texto em arquivos de apresentação usando APIs do lado do servidor. Saiba como pesquisar e substituir texto em conteúdo, comentários ou metadados de apresentações ODP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Redigir apresentação ODP via C++" %}}
Uma pesquisa básica de documentos e substituição de texto em conteúdos, comentários, notas de slides ou metadados com Aspose.Slides for C++ APIs pode ser feita com apenas algumas linhas de código. Encontre e substitua texto no PowerPoint e no OpenOffice. Edite texto, comentários e metadados na apresentação por meio da correspondência de dados regexp.
{{% blocks/products/pf/agp/code-block title="Redigir apresentação ODP usando C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.odp", SaveFormat::Odp);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como redigir ODP via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para redigir arquivos ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregue ODP com uma instância de Apresentação.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use o método [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) para localizar e substituir o texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado no formato ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de redação ODP on-line" sectionDescription="Pesquise e substitua texto em conteúdos, comentários ou metadados em documentos ODP agora mesmo." >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de edição suportados" subTitle="Usando C++, você também pode redigir os seguintes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}