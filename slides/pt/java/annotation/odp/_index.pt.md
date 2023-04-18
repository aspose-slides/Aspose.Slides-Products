---
title: Remover anotação ODP usando Java
weight: 1790
url: /pt/java/annotation/odp/ 
description: Código de exemplo Java para excluir anotações de formato ODP no Java Runtime Environment para aplicativos JSP/JSF e aplicativos de desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Remover comentários e autores de comentários do ODP em Java" h2="Crie seus próprios aplicativos Java para manipular comentários e autores em arquivos de documentos usando APIs do lado do servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="Remover comentários do ODP via Java" %}}
Para remover as anotações do arquivo ODP, usaremos a API [Aspose.Slides for Java](https://products.aspose.com/slides/pt/java/) que é uma API rica em recursos, poderosa e fácil de usar API de manipulação de documentos para plataforma Java.
{{% blocks/products/pf/agp/code-block title="Excluir anotações do ODP - Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.odp");
try {
    // Deletes all comments from the presentation
    for (ICommentAuthor author : presentation.getCommentAuthors())
    {
        author.getComments().clear();
    }

    // Deletes all authors
    presentation.getCommentAuthors().clear();

    presentation.save("example_out.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Como remover comentários do ODP via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale **Aspose.Slides para Java**. Consulte [**Instalação**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregar ODP com uma instância da classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterar sobre todos os autores do ODP carregado
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Remover todos os comentários de um autor
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Remova todos os autores no final
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de anotação suportados" subTitle="Usando Java, pode-se facilmente anotar outros formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/java/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}