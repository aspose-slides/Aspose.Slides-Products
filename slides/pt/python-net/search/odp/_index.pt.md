---
title: Pesquisar texto em arquivos de apresentação ODP usando Python
url: /pt/python-net/search/odp/
keywords: pesquisar palavras em ODP, pesquisar e substituir texto em ODP, pesquisar texto ODP Apresentação
description: Código-fonte Python para pesquisar texto na apresentação ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Pesquisar texto ODP usando Python" h2="Crie seus próprios aplicativos Python para pesquisar e substituir texto em arquivos de apresentação usando APIs do lado do servidor. Aprenda a encontrar todas as entradas de uma determinada palavra ou frase em documentos de apresentação. Pesquise texto por correspondência exata de dados e correspondência de expressão regular." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Pesquisar e substituir texto ODP Apresentação via Python" %}}
Uma pesquisa básica de documentos e substituição de texto em conteúdos, comentários, notas de slides ou metadados com Aspose.Slides for Python via .NET APIs pode ser feita com apenas algumas linhas de código. Use correspondência de expressão regular, maiúsculas e minúsculas para pesquisar o texto na apresentação. Pesquise texto em títulos, conteúdo, rodapé ou cabeçalho.
{{% blocks/products/pf/agp/code-block title="Pesquisar texto ODP Apresentação usando Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.odp") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como pesquisar texto em ODP via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para pesquisar arquivos de texto ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregue ODP com uma instância de Apresentação.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use o método [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) para localizar e substituir o texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado no formato ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Pesquisar demonstrações ao vivo" sectionDescription="Pesquise e substitua texto em conteúdos, comentários ou metadados em documentos ODP agora mesmo." >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de pesquisa suportados" subTitle="Usando Python, você também pode pesquisar texto nos seguintes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}