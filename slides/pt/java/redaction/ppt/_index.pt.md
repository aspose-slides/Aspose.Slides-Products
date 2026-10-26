---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tarjar arquivos de apresentação PPT usando Java
url: /pt/java/redaction/ppt/
description: Localize e substitua texto em apresentações PPT em Java com o Aspose.Slides for Java.
keywords: tarjar PPT, localizar e substituir texto em PPT, atualizar apresentação PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tarjar PPT usando Java" h2="Crie aplicativos Java que localizam e substituem texto em arquivos de apresentação com APIs do lado do servidor." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tarjar uma apresentação PPT com Java" variant="code" %}}

Com o [Aspose.Slides for Java](/slides/pt/java/), você pode localizar e substituir texto em apresentações PPT. Use o método `SlideUtil.findAndReplaceText` para pesquisar a apresentação e substituir o texto correspondente por um novo valor.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tarjar uma apresentação PPT usando Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como tarjar PPT com Java" intro="Siga estas etapas para tarjar uma apresentação PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo PPT com a classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método `SlideUtil.findAndReplaceText` para localizar e substituir texto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve a apresentação atualizada com `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Criado com Aspose.Slides" title="Tarjar arquivos PPT online" description="O aplicativo gratuito Aspose.Slides Redaction é criado com [Aspose.Slides for Java](https://products.aspose.com/slides/pt/java/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPT." button="Abrir Aspose.Slides Redaction" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides localiza e substitui texto antes de escrever código.
- Localize e substitua texto no seu arquivo PPT, inclusive com expressões regulares.
- Baixe o arquivo tarjado.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com tarjamento" subTitle="Com Java, você também pode tarjar os seguintes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/java/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
