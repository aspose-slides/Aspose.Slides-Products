---
title: Pesquisar texto em arquivos de apresentação ODP usando .NET
url: /pt/net/search/odp/
keywords: pesquisar palavras em ODP, pesquisar e substituir texto em ODP, pesquisar texto ODP Apresentação
description: Código-fonte C# para pesquisar texto na apresentação ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Pesquisar texto ODP usando C#" h2="Crie seus próprios aplicativos .NET para pesquisar e substituir texto em arquivos de apresentação usando APIs do lado do servidor. Aprenda a encontrar todas as entradas de uma determinada palavra ou frase em documentos de apresentação. Pesquise texto por correspondência exata de dados e correspondência de expressão regular." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Pesquisar e substituir texto ODP Apresentação via C#" %}}
Uma pesquisa básica de documentos e substituição de texto em conteúdos, comentários, notas de slides ou metadados com Aspose.Slides for .NET APIs pode ser feita com apenas algumas linhas de código. Use correspondência de expressão regular, maiúsculas e minúsculas para pesquisar o texto na apresentação. Pesquise texto em títulos, conteúdo, rodapé ou cabeçalho.
{{% blocks/products/pf/agp/code-block title="Pesquisar texto ODP Apresentação usando C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.odp"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como pesquisar texto em ODP via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para pesquisar arquivos de texto ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregue ODP com uma instância de Apresentação.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use o método [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) para localizar e substituir o texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado no formato ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Pesquisar demonstrações ao vivo" sectionDescription="Pesquise e substitua texto em conteúdos, comentários ou metadados em documentos ODP agora mesmo." >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de pesquisa suportados" subTitle="Usando C#, você também pode pesquisar texto nos seguintes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}