---
lastmod: 2026-10-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Visualizar OTP em C#
keywords: Visualizar OTP, Abrir OTP, Visualizador de OTP, OTP, API C#, Biblioteca .NET
weight: 6830
url: /pt/net/viewer/otp/ 
description: Visualize arquivos OTP em C#. Use o Aspose.Slides for .NET para abrir arquivos de apresentação e salvá-los como HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Visualizar OTP em C#" h2="API C# para abrir arquivos OTP e salvá-los como HTML responsivo."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Visualizar OTP com o Aspose.Slides" %}}

Para visualizar arquivos OTP, use a API [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net/), uma API C# poderosa, completa e fácil de usar. Abra o gerenciador de pacotes [NuGet](https://www.nuget.org/packages/aspose.slides.net), pesquise **Aspose.Slides** e instale-o. Você também pode executar o seguinte comando no Console do Gerenciador de Pacotes.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando do Console do Gerenciador de Pacotes" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Com o [**Aspose.Slides for .NET**](/slides/pt/net/), você pode carregar um arquivo OTP e salvá-lo como HTML responsivo com poucas linhas de código.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código C# para visualizar OTP" >}}
```cs
using var presentation = new Presentation("presentation.otp");

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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como visualizar OTP em C#" intro="O Aspose.Slides permite que desenvolvedores visualizem arquivos OTP com poucas linhas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale o **Aspose.Slides for .NET**. Consulte [**Instalação**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adicione a biblioteca como referência no seu projeto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo `OTP` com a classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crie um objeto `ResponsiveHtmlController` para uma saída HTML responsiva.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crie um objeto `HtmlOptions` e defina a propriedade `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve o arquivo OTP como HTML com `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos do sistema" intro="O Aspose.Slides for .NET é compatível com todos os principais sistemas operacionais. Verifique se você atende aos seguintes pré-requisitos." %}}

- Microsoft Windows ou um sistema operacional compatível com .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin
- Um ambiente de desenvolvimento como o Microsoft Visual Studio
- Uma referência ao Aspose.Slides for .NET no seu projeto

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Criado com Aspose.Slides" title="Visualize arquivos OTP online" description="O aplicativo gratuito Aspose.Slides Viewer é criado com [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos OTP." button="Abrir Aspose.Slides Viewer" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides renderiza seus arquivos antes de escrever código.
- Carregue seu arquivo OTP e veja os slides instantaneamente.
- Funciona no computador e no celular, sem PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" %}}

Files with .OTP extension represent presentation template files created by applications in OASIS OpenDocument standard format. The contents of such a file include presentation information in the form of slides with text, images, shapes, multimedia content, transition effects and other slide elements. These template files are used for creating new presentations quickly based on the styling information stored in the template itself. OTP files can be created and saved with several different applications such as Impress that comes with OpenOffice suite and Microsoft PowerPoint. The OTP file format is similar to Microsoft PowerPoint template files .POT and .POTX.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Visualizar outros arquivos" subTitle="Você também pode abrir e visualizar apresentações em outros formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/odp/" name="ODP" description="Apresentação OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/pot/" name="POT" description="Modelo do PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/potm/" name="POTM" description="Modelo do PowerPoint habilitado para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/potx/" name="POTX" description="Modelo do PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/pps/" name="PPS" description="Apresentação de slides do PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/ppsm/" name="PPSM" description="Apresentação de slides do PowerPoint habilitada para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/ppsx/" name="PPSX" description="Apresentação de slides do PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/ppt/" name="PPT" description="Apresentação do PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/pptm/" name="PPTM" description="Apresentação do PowerPoint habilitada para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/viewer/pptx/" name="PPTX" description="Apresentação do PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
