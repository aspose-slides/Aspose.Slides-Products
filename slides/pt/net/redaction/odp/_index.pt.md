---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tarjar arquivos de apresentação ODP com .NET
url: /pt/net/redaction/odp/
description: Código-fonte C# para localizar e substituir texto em apresentações ODP.
keywords: Tarjar ODP, localizar e substituir texto em ODP, atualizar apresentação ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tarjar arquivos ODP usando C#" h2="Crie aplicativos .NET que localizam e substituem texto em apresentações com APIs do lado do servidor." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tarjar uma apresentação ODP usando C#" variant="code" %}}

Com o [Aspose.Slides for .NET](/slides/pt/net/), você pode localizar e substituir texto em uma apresentação ODP. Use `Presentation.ReplaceText` com `TextSearchOptions` para controlar a pesquisa e, em seguida, salve a apresentação modificada.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tarjar uma apresentação ODP usando C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como tarjar uma apresentação ODP usando C#" intro="Siga estas etapas para substituir texto em uma apresentação ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo ODP com `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) com `TextSearchOptions` para substituir o texto necessário.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve a apresentação modificada com `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Criado com Aspose.Slides" title="Tarjar arquivos ODP online" description="O aplicativo gratuito Aspose.Slides Redaction é criado com [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos ODP." button="Abrir Aspose.Slides Redaction" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides localiza e substitui texto antes de escrever código.
- Localize e substitua texto no seu arquivo ODP, inclusive com expressões regulares.
- Baixe o arquivo tarjado.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com tarjamento" subTitle="Com C#, você também pode tarjar os seguintes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
