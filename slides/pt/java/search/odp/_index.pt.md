---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Pesquisar texto em arquivos de apresentação ODP usando Java
url: /pt/java/search/odp/
description: Pesquise texto em apresentações ODP em Java com o Aspose.Slides for Java.
keywords: pesquisar palavras em ODP, pesquisar texto em ODP, pesquisar texto de apresentação ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Pesquisar texto em ODP usando Java" h2="Crie aplicativos Java que pesquisam texto em arquivos de apresentação com APIs do lado do servidor." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Pesquisar texto em uma apresentação ODP com Java" variant="code" %}}

Com o [Aspose.Slides for Java](/slides/pt/java/), você pode pesquisar texto em apresentações ODP. Use o método `SlideUtil.getAllTextBoxes` para reunir os quadros de texto e, em seguida, examine os objetos `ITextFrame`, `IParagraph` e `IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Pesquisar texto em uma apresentação ODP usando Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como pesquisar texto em ODP com Java" intro="Siga estas etapas para pesquisar texto em uma apresentação ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo ODP com a classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método `SlideUtil.getAllTextBoxes` para reunir os quadros de texto de cada slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Examine os objetos `ITextFrame`, `IParagraph` e `IPortion` para encontrar o texto correspondente.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Criado com Aspose.Slides" title="Pesquisar texto em arquivos ODP online" description="O aplicativo gratuito Aspose.Slides Search é criado com [Aspose.Slides for Java](https://products.aspose.com/slides/pt/java/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos ODP." button="Abrir Aspose.Slides Search" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides localiza texto antes de escrever código.
- Pesquise texto simples ou expressões regulares no seu arquivo ODP.
- Baixe os resultados como um arquivo de texto.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com pesquisa" subTitle="Com Java, você também pode pesquisar texto nos seguintes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
