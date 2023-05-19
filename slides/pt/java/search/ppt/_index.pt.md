---
title: Pesquisar texto em arquivos de apresentação PPT usando Java
url: /pt/java/search/ppt/
keywords: pesquisar palavras em PPT, pesquisar e substituir texto em PPT, pesquisar texto PPT Apresentação
description: Código-fonte Java para pesquisar texto na apresentação PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Pesquisar texto PPT usando Java" h2="Crie seus próprios aplicativos Java para pesquisar e substituir texto em arquivos de apresentação usando APIs do lado do servidor. Aprenda a encontrar todas as entradas de uma determinada palavra ou frase em documentos de apresentação. Pesquise texto por correspondência exata de dados e correspondência de expressão regular." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Pesquisar e substituir texto PPT Apresentação via Java" %}}
Uma pesquisa básica de documentos e substituição de texto em conteúdos, comentários, notas de slides ou metadados com Aspose.Slides for Java APIs pode ser feita com apenas algumas linhas de código. Use correspondência de expressão regular, maiúsculas e minúsculas para pesquisar o texto na apresentação. Pesquise texto em títulos, conteúdo, rodapé ou cabeçalho.
{{% blocks/products/pf/agp/code-block title="Pesquisar texto PPT Apresentação usando Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como pesquisar texto em PPT via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para pesquisar arquivos de texto PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregue PPT com uma instância de Apresentação.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use o método [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) para localizar e substituir o texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado no formato PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Pesquisar demonstrações ao vivo" sectionDescription="Pesquise e substitua texto em conteúdos, comentários ou metadados em documentos PPT agora mesmo." >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de pesquisa suportados" subTitle="Usando Java, você também pode pesquisar texto nos seguintes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}