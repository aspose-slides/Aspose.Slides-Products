---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3630
title: Remover anotações de PPT usando Java
url: /pt/java/annotation/ppt/ 
description: Remova comentários e autores de comentários de apresentações PPT em Java com o Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Remover comentários e autores de comentários de PPT em Java" h2="Use o Aspose.Slides for Java para remover comentários e autores de comentários de arquivos de apresentação." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Remover comentários de PPT com Java" variant="code" %}}

O Aspose.Slides for Java permite remover comentários e autores de comentários de apresentações PPT. Carregue um arquivo com a classe `Presentation`, percorra os objetos `ICommentAuthor` de `getCommentAuthors`, limpe os comentários e salve a apresentação atualizada.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Excluir anotações de PPT – Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como remover comentários de PPT com Java" intro="Siga estas etapas para remover comentários e autores de comentários de uma apresentação PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale o Aspose.Slides for Java. Consulte [Instalação](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo PPT com a classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Percorra os objetos `ICommentAuthor` de `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Limpe os comentários de cada autor com `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Limpe a coleção de autores de comentários e salve o arquivo PPT atualizado.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Criado com Aspose.Slides" title="Remover comentários de PPT online" description="O aplicativo gratuito Aspose.Slides Annotation é criado com [Aspose.Slides for Java](https://products.aspose.com/slides/pt/java/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPT." button="Abrir Aspose.Slides Annotation" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides remove comentários antes de escrever código.
- Remova todos os comentários do seu arquivo PPT.
- Baixe o arquivo limpo.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com anotações" subTitle="Com Java, você também pode remover anotações de outros formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
