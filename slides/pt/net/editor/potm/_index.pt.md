---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edite arquivos POTM via .NET
url: /pt/net/editor/potm/ 
description: Código-fonte C# para editar o documento POTM nas plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Editar formatos POTM em C#" h2="Edição de documentos POTM nativa e de alto desempenho usando Aspose.Slides do lado do servidor para APIs .NET, sem o uso de qualquer software como Microsoft ou Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Como editar o arquivo POTM usando C#" %}}

Para editar o arquivo POTM, usaremos a API <a href="https://products.aspose.com/slides/pt/net">Aspose.Slides for .NET</a>, que é uma poderosa e rica em recursos e API fácil de usar para plataforma C# para qualquer editor. Abra o gerenciador de pacotes <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a>, procure por <b>Aspose.Slides</b> e instale. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Editar arquivos POTM - C#" >}}
```cs
using var presentation = new Presentation("document.potm");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.potm", SaveFormat.Potm);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Etapas para editar arquivos POTM em C#" intro="Uma edição básica de documentos com [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net) APIs podem ser feitas com apenas algumas linhas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo POTM com um objeto `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Acesse o slide e a forma de destino por meio de variáveis.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Atualize o texto por meio de `TextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve a apresentação editada com `SaveFormat.Potm`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos de sistema" intro="Nossas APIs são suportadas em todas as principais plataformas e sistemas operacionais. Antes de executar o código abaixo, verifique se você possui os seguintes pré-requisitos em seu sistema." %}}

- Microsoft Windows ou um sistema operacional compatível com plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin
- Ambiente de desenvolvimento como Microsoft Visual Studio
- Aspose.Slides for .NET DLL referenciado em seu projeto - Instale do NuGet usando o botão Download acima

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTM" readMoreLink="https://docs.fileformat.com/presentation/potm/" %}}

Files with POTM extension are Microsoft PowerPoint template files with support for Macros. POTM files are created with PowerPoint 2007 or above and contains default settings that can be used to create further presentation files. These settings can include styles, backgrounds, colour palette, fonts and defaults along with macros that consist of custom functions for doing particular task. They may also be opened by a previous version of PowerPoint with Open XML document support installed. POTM files can be opened in Microsoft PowerPoint for editing like any other PowerPoint file.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
