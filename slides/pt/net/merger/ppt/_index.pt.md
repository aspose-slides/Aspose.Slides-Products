---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Mesclar arquivos PPT via .NET
weight: 7610
url: /pt/net/merger/ppt/ 
description: Código-fonte C# para combinar documentos PPT em plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Mesclar formatos PPT em C#" h2="Fusão de documentos PPT nativos e de alto desempenho usando Aspose.Slides do lado do servidor para APIs .NET, sem o uso de nenhum software como Microsoft ou Open Office, Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Como mesclar arquivo PPT usando C#" %}}

Para mesclar o arquivo PPT, usaremos
 [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net)
 API que é uma API de manipulação e mesclagem de documentos rica em recursos, poderosa e fácil de usar para a plataforma C#. Aberto
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 gerenciador de pacotes, procure
 **Aspose.Slides**
 e instalar. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mesclar arquivos PPT - C#" >}}
```cs
var ps1 = new Presentation("presen1.ppt");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first PPT presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Etapas para mesclar arquivos PPT em C#" intro="Um documento básico mesclando e concatenando com APIs [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net) pode ser feito com apenas algumas linhas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue todos os arquivos PPT com caminho completo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Faça um documento como o arquivo base{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método relevante para concatenar e mesclar arquivos um por um.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método Save() e passe o nome do arquivo (caminho completo) e o formato (PPT) como parâmetro.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Agora você pode abrir e usar o arquivo PPT no Microsoft Office, Adobe PDF ou qualquer outro programa compatível.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos de sistema" intro="Nossas APIs são suportadas em todas as principais plataformas e sistemas operacionais. Antes de executar o código abaixo, verifique se você possui os seguintes pré-requisitos em seu sistema." %}}

- Microsoft Windows ou um sistema operacional compatível com plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin
- Ambiente de desenvolvimento como Microsoft Visual Studio
- Aspose.Slides for .NET DLL referenciado em seu projeto - Instale do NuGet usando o botão Download acima

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Criado com Aspose.Slides" title="Mesclar arquivos PPT online" description="O aplicativo gratuito Aspose.Slides Merger é criado com [Aspose.Slides for .NET](https://products.aspose.com/slides/pt/net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPT." button="Abrir Aspose.Slides Merger" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides mescla arquivos antes de escrever código.
- Envie vários arquivos PPT e combine-os em um só.
- Baixe o resultado mesclado como um único arquivo.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Um arquivo com a extensão .ppt é uma apresentação do PowerPoint que contém um conjunto de slides para uso em uma apresentação de slides. Ele usa o formato de arquivo binário compatível com o Microsoft PowerPoint 97–2003. Um arquivo PPT pode conter vários tipos de conteúdo, como texto, listas com marcadores, imagens, multimídia e outros objetos OLE incorporados. A partir do PowerPoint 2007, a Microsoft introduziu o formato PPTX, mais recente, baseado em Office Open XML em vez desse formato binário. Outros aplicativos, como OpenOffice Impress e Apple Keynote, também podem criar arquivos PPT.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos de mesclagem compatíveis" subTitle="Usando C#, também é possível mesclar muitos outros formatos de arquivo, incluindo." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/merger/odp/" name="ODP" description="Formato de apresentação do OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/merger/otp/" name="OTP" description="Formato padrão do OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/merger/pot/" name="POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/merger/potm/" name="POTM" description="Arquivo de modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/merger/potx/" name="POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/merger/pps/" name="PPS" description="Apresentação de slides do PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/merger/ppsm/" name="PPSM" description="Apresentação de slides habilitada para macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/merger/ppsx/" name="PPSX" description="Apresentação de slides do PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/merger/pptm/" name="PPTM" description="Arquivo de apresentação habilitado para macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/net/merger/pptx/" name="PPTX" description="Formato de apresentação XML aberto" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
