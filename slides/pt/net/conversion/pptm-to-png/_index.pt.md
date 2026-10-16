---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter PPTM para PNG via C#
weight: 1360
url: /pt/net/conversion/pptm-to-png/ 
description: Código de exemplo para conversão de PPTM para PNG C#. Use o código de exemplo da API para conversão de arquivos PPTM em lote para PNG em VB.NET, Asp.NET ou qualquer aplicativo baseado em .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converter PPTM para PNG via C#" h2="Exporte arquivos PPTM do PowerPoint® para PNG em plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Como converter PPTM para PNG usando C#" %}}

Para converter PPTM para PNG, usaremos
 [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net)
 API que é uma API de manipulação e conversão de documentos rica em recursos, poderosa e fácil de usar para a plataforma C#. Aberto
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 gerenciador de pacotes, procure
 Aspose.Slides
 e instalar. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando do console do gerenciador de pacotes" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Este código de exemplo mostra a conversão de PPTM para PNG C#" >}}
```cs
using (var presentation = new Presentation("template.pptm"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in PNG format
        bitmap.Save(string.Format("Slide_{0}.png", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Png);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Etapas para converter PPTM para PNG via C#" intro="Os desenvolvedores .NET podem facilmente carregar e converter arquivos PPTM para PNG em apenas algumas linhas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregar arquivo PPTM com uma instância da classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterar em cada slide na apresentação{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crie uma imagem em escala real como um Bitmap com cada iteração{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método Bitmap.Save com extensão de arquivo PNG e ImageFormat.Png como parâmetros{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos de sistema" intro="Antes de executar o código-fonte de amostra de conversão .NET, certifique-se de ter os seguintes pré-requisitos." %}}

- Microsoft Windows ou SO compatível com plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
- Ambiente de desenvolvimento como Microsoft Visual Studio.
- Aspose.Slides for .NET DLL referenciado em seu projeto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplicativo gratuito para converter PPTM para PNG"
  description="[Experimente nosso aplicativo gratuito para converter PPT para PNG](https://products.aspose.app/slides/conversion/ppt-to-png)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outras conversões compatíveis" subTitle="Você também pode converter PPTM em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Imagem em formato bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-emf/" name="PPTM TO EMF" description="Formato de metarquivo aprimorado" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Formato de intercâmbio gráfico" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-html/" name="PPTM TO HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-jpeg/" name="PPTM TO JPEG" description="Imagem JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Formato de apresentação do OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Formato padrão do OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Formato de Documento Portátil" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-pot/" name="PPTM TO POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Arquivo de modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Apresentação de slides do PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Apresentação de slides habilitada para macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Apresentação de slides do PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Formato de apresentação XML aberto" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Gráficos vetoriais escalonáveis" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-swf/" name="PPTM TO SWF" description="Formato SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Formato de imagem marcada" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Especificações do papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
