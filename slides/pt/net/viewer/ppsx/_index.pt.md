---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Visualizar PPSX em C#
keywords: Visualizar PPSX, Abrir PPSX, Visualizador de PPSX, PPSX, PowerPoint, API C#, Biblioteca .NET
weight: 2370
url: /pt/net/viewer/ppsx/ 
description: Visualize arquivos PPSX em C#. Use o Aspose.Slides for .NET para abrir arquivos de apresentação e salvá-los como HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Visualizar PPSX em C#" h2="API C# para abrir arquivos PPSX e salvá-los como HTML responsivo."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Visualizar PPSX com o Aspose.Slides" %}}

Para visualizar arquivos PPSX, use a API [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net/), uma API C# poderosa, completa e fácil de usar. Abra o gerenciador de pacotes [NuGet](https://www.nuget.org/packages/aspose.slides.net), pesquise **Aspose.Slides** e instale-o. Você também pode executar o seguinte comando no Console do Gerenciador de Pacotes.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando do Console do Gerenciador de Pacotes" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Com o [**Aspose.Slides for .NET**](/slides/pt/net/), você pode carregar um arquivo PPSX e salvá-lo como HTML responsivo com poucas linhas de código.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código C# para visualizar PPSX" >}}
```cs
using var presentation = new Presentation("presentation.ppsx");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como visualizar PPSX em C#" intro="O Aspose.Slides permite que desenvolvedores visualizem arquivos PPSX com poucas linhas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale o **Aspose.Slides for .NET**. Consulte [**Instalação**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adicione a biblioteca como referência no seu projeto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo `PPSX` com a classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crie um objeto `ResponsiveHtmlController` para uma saída HTML responsiva.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crie um objeto `HtmlOptions` e defina a propriedade `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve o arquivo PPSX como HTML com `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos do sistema" intro="O Aspose.Slides for .NET é compatível com todos os principais sistemas operacionais. Verifique se você atende aos seguintes pré-requisitos." %}}

- Microsoft Windows ou um sistema operacional compatível com .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin
- Um ambiente de desenvolvimento como o Microsoft Visual Studio
- Uma referência ao Aspose.Slides for .NET no seu projeto

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Criado com Aspose.Slides" title="Visualize arquivos PPSX online" description="O aplicativo gratuito Aspose.Slides Viewer é criado com [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPSX." button="Abrir Aspose.Slides Viewer" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides renderiza seus arquivos antes de escrever código.
- Carregue seu arquivo PPSX e veja os slides instantaneamente.
- Funciona no computador e no celular, sem PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" %}}

Um arquivo PPSX é uma apresentação de slides do PowerPoint no formato Open XML criada no Microsoft PowerPoint 2007 ou posterior. É o sucessor em Open XML do formato PPS usado pelo PowerPoint 97–2003. Ao contrário de um arquivo PPTX, que abre no modo de edição por padrão, um arquivo PPSX abre diretamente como apresentação de slides. Ele preserva a ordem dos slides e pode conter imagens, áudio e outras mídias incorporadas.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Visualizar outros arquivos" subTitle="Você também pode abrir e visualizar apresentações em outros formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/odp/" name="ODP" description="Apresentação OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/otp/" name="OTP" description="Modelo de apresentação OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/pot/" name="POT" description="Modelo do PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/potm/" name="POTM" description="Modelo do PowerPoint habilitado para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/potx/" name="POTX" description="Modelo do PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/pps/" name="PPS" description="Apresentação de slides do PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/ppsm/" name="PPSM" description="Apresentação de slides do PowerPoint habilitada para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/ppt/" name="PPT" description="Apresentação do PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/pptm/" name="PPTM" description="Apresentação do PowerPoint habilitada para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/pptx/" name="PPTX" description="Apresentação do PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
