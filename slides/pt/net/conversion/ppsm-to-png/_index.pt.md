---
title: Converter PPSM para PNG via C#
weight: 6640
url: /pt/net/conversion/ppsm-to-png/ 
description: Código de exemplo para conversão de PPSM para PNG C#. Use o código de exemplo da API para conversão de arquivos PPSM em lote para PNG em VB.NET, Asp.NET ou qualquer aplicativo baseado em .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter PPSM para PNG via C#" h2="Exporte arquivos PPSM do PowerPoint® para PNG em plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como converter PPSM para PNG usando C#" %}}

 Para converter PPSM para PNG, usaremos
 [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net)
 API que é uma API de manipulação e conversão de documentos rica em recursos, poderosa e fácil de usar para a plataforma C#. Aberto
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 gerenciador de pacotes, procure
 Aspose.Slides
 e instalar. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Comando do console do gerenciador de pacotes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Etapas para converter PPSM para PNG via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Os desenvolvedores .NET podem facilmente carregar e converter arquivos PPSM para PNG em apenas algumas linhas de código." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregar arquivo PPSM com uma instância da classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterar em cada slide na apresentação
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crie uma imagem em escala real como um Bitmap com cada iteração
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chame o método Bitmap.Save com extensão de arquivo PNG e ImageFormat.Png como parâmetros
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código-fonte de amostra de conversão .NET, certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou SO compatível com plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
- Ambiente de desenvolvimento como Microsoft Visual Studio.
- Aspose.Slides for .NET DLL referenciado em seu projeto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de exemplo mostra a conversão de PPSM para PNG C#" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.ppsm"))
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

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="ppsm-to-png"
        sectionTitle="Aplicativo gratuito para converter PPSM para PNG" 
        sectionDescription="[Experimente nosso aplicativo gratuito para converter PPT para PNG](https://products.aspose.app/slides/conversion/ppt-to-png)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Você também pode converter PPSM em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Imagem em formato bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="Formato de metarquivo aprimorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Formato de intercâmbio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-jpeg/" name="PPSM TO JPEG" description="Imagem JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="Formato de apresentação do OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="Formato padrão do OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Formato de Documento Portátil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Arquivo de modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="Apresentação de slides do PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="Apresentação de slides do PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Arquivo de apresentação habilitado para macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Formato de apresentação XML aberto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Gráficos vetoriais escalonáveis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="Formato SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Formato de imagem marcada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/net/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="Especificações do papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}