---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Pesquisar texto em arquivos de apresentação PPT com .NET
url: /pt/net/search/ppt/
description: Código-fonte C# para pesquisar texto em apresentações PPT.
keywords: Pesquisar texto em PPT, localizar texto em PPT, pesquisar texto de apresentação PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Pesquisar texto em arquivos PPT usando C#" h2="Crie aplicativos .NET que localizam texto em apresentações com APIs do lado do servidor." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Pesquisar texto em uma apresentação PPT usando C#" variant="code" %}}

Com o [Aspose.Slides for .NET](/slides/pt/net/), você pode pesquisar texto em uma apresentação PPT. Obtenha os quadros de texto de um slide com `SlideUtil.GetAllTextBoxes` e verifique os valores `Text` em busca da frase desejada.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Pesquisar texto em uma apresentação PPT usando C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como pesquisar texto em uma apresentação PPT usando C#" intro="Siga estas etapas para pesquisar texto em uma apresentação PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo PPT com `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenha o slide desejado de `Presentation.Slides` e atribua-o a uma variável.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenha os quadros de texto dele com [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Verifique se o valor `Text` de cada quadro contém a frase desejada.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Criado com Aspose.Slides" title="Pesquisar texto em arquivos PPT online" description="O aplicativo gratuito Aspose.Slides Search é criado com [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPT." button="Abrir Aspose.Slides Search" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides localiza texto antes de escrever código.
- Pesquise texto simples ou expressões regulares no seu arquivo PPT.
- Baixe os resultados como um arquivo de texto.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com pesquisa" subTitle="Com C#, você também pode pesquisar texto nos seguintes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
