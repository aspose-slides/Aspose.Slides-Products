---
title: Converter PPSX para GIF via aplicativo C++
weight: 3940
url: /pt/cpp/conversion/ppsx-to-gif/ 
description: Exemplo de código de conversão C++ para documento PPSX para formato GIF. Use o código de exemplo para conversão em lote de PPSX para GIF em qualquer aplicativo C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter PPSX para GIF via C++" h2="Conversão de PPSX para GIF de alto desempenho usando biblioteca C++ sem a necessidade de instalação do Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como converter PPSX para GIF usando C++" %}}

 Para converter PPSX para GIF, usaremos
 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp)
 API que é uma API de manipulação e conversão de documentos rica em recursos, poderosa e fácil de usar para plataforma C++. Você pode baixar sua versão mais recente diretamente, basta abrir
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 gerenciador de pacotes, procure
 Aspose.Slides.Cpp
 e instalar. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passos para converter PPSX para GIF via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Os desenvolvedores de C++ podem converter facilmente arquivos PPSX para GIF em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregue o arquivo PPSX com Aspose.Slides for C++ Presentation Object.
1. Selecione o primeiro slide.
1. Defina as dimensões desejadas.
1. Obtenha a miniatura com as dimensões desejadas.
1. Chame o método Save() com o parâmetro de saída GIF .
1. Abra o arquivo GIF em um programa compatível.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código de exemplo de conversão C++, certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.
- Aspose.Slides for C++ DLL referenciado em seu projeto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código-fonte de conversão de PPSX para GIF C++" offSpacer="" %}}

```cs
// Load the PPSX
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.ppsx");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.gif", ImageFormat::get_Gif());
	
//Iterate through each slide via index and convert

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PPSX to GIF Conversion Live Demos" sectionDescription="[Convert PPSX to GIF](https://products.aspose.app/slides/conversion/ppsx-to-gif) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPSX file, it will be converted instantly to GIF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="Biblioteca de manipulação de apresentação C++" %}}

 A API de Slides e Apresentação pode ser usada para ler, escrever, manipular e converter documentos do Microsoft PowerPoint para PDF, XPS, HTML, TIFF, ODP e vários outros formatos. Pode-se criar novos arquivos do zero e salvá-los nos formatos suportados relevantes. Aspose.Slides é uma API independente para criar, analisar ou manipular apresentações, slides e elementos e não depende de nenhum software como Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" >}}

PPSX, Power Point Slide Show, file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. It is an update to the PPS file format that was supported by Microsoft PowerPoint 97-2003 versions. When a PPSX file is shared with another user and opened, it starts as PowerPoint show unlike PPTX file that opens in editable mode. The sequence of slide show is the same as in the original presentation. All the slides accompany the images, sounds and other embedded media accompany the presentation slides to the PPSX during the slideshow.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

A GIF or Graphical Interchange Format is a type of highly compressed image. Owned by Unisys, GIF uses the LZW compression algorithm that does not degrade the image quality. For each image GIF typically allow up to 8 bits per pixel and up to 256 colours are allowed across the image. In contrast to a JPEG image, which can display up to 16 million colours and fairly touches the limits of the human eye. Back when the internet emerged, GIFs remained the best choice because they required low bandwidth and compatible for the graphics that consume solid areas of colour. An animated GIF combines numerous images or frames into a single file and displays them in a sequence to generate an animated clip or a short video. The colour limitations are up to 256 for each frame and are likely to be the least suitable for reproducing other images and photographs with colour gradient.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Você também pode converter PPSX em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Imagem em formato bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="Formato de metarquivo aprimorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="Imagem JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="Formato de apresentação do OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Formato padrão do OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Formato de Documento Portátil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Gráficos Portáteis de Rede" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Arquivo de modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="Apresentação de slides do PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Apresentação de slides habilitada para macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Arquivo de apresentação habilitado para macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Formato de apresentação XML aberto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Gráficos vetoriais escalonáveis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Formato de imagem marcada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-xml/" name="PPSX TO XML" description="Extensible Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Especificações do papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}