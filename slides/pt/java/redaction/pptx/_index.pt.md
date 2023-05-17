---
title: Redigir arquivos de apresentação PPTX usando Java
url: /pt/java/redaction/pptx/
keywords: Redigir PPTX, localizar e substituir texto em PPTX, atualizar PPTX Apresentação
description: Código-fonte Java para localizar e substituir texto na apresentação PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redigir PPTX usando Java" h2="Crie seus próprios aplicativos Java para localizar e substituir texto em arquivos de apresentação usando APIs do lado do servidor. Saiba como pesquisar e substituir texto em conteúdo, comentários ou metadados de apresentações PPTX" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Redigir apresentação PPTX via Java" %}}
Uma pesquisa básica de documentos e substituição de texto em conteúdos, comentários, notas de slides ou metadados com Aspose.Slides for Java APIs pode ser feita com apenas algumas linhas de código. Encontre e substitua texto no PowerPoint e no OpenOffice. Edite texto, comentários e metadados na apresentação por meio da correspondência de dados regexp.
{{% blocks/products/pf/agp/code-block title="Redigir apresentação PPTX usando Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Como redigir PPTX via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para redigir arquivos PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregue PPTX com uma instância de Apresentação.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use o método [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) para localizar e substituir o texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado no formato PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de redação PPTX on-line" sectionDescription="Pesquise e substitua texto em conteúdos, comentários ou metadados em documentos PPTX agora mesmo." >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de edição suportados" subTitle="Usando Java, você também pode redigir os seguintes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}