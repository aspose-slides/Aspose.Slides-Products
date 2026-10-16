---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter PPSM para PNG via aplicativo C++
weight: 400
url: /pt/cpp/conversion/ppsm-to-png/ 
description: Exemplo de código de conversão C++ para documento PPSM para o formato PNG. Use o código de exemplo para conversão em lote de PPSM para PNG em qualquer aplicativo C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converter PPSM para PNG via C++" h2="Conversão de PPSM para PNG de alto desempenho usando biblioteca C++ sem a necessidade de instalação do Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Como converter PPSM para PNG usando C++" %}}

Para converter PPSM para PNG, usaremos
 [Aspose.Slides for C++](https://products.aspose.com/slides/pt/cpp/)
 API que é uma API de manipulação e conversão de documentos rica em recursos, poderosa e fácil de usar para plataforma C++. Você pode baixar sua versão mais recente diretamente, basta abrir
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 gerenciador de pacotes, procure
 Aspose.Slides.Cpp
 e instalar. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código-fonte de conversão de PPSM para PNG C++" >}}
```cs
// Load the PPSM
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.ppsm");

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

bitmap->Save(u"output.png", ImageFormat::get_Png());
	
//Iterate through each slide via index and convert

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Etapas para converter PPSM para PNG via C++" intro="Os desenvolvedores de C++ podem converter facilmente arquivos PPSM para PNG em apenas algumas linhas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo PPSM com Aspose.Slides for C++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Selecione o primeiro slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Defina as dimensões desejadas.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenha a miniatura com as dimensões desejadas.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método Save() com o parâmetro de saída PNG .{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra o arquivo PNG em um programa compatível.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos de sistema" intro="Antes de executar o código de exemplo de conversão C++, certifique-se de ter os seguintes pré-requisitos." %}}

- Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.
- Aspose.Slides for C++ DLL referenciado em seu projeto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplicativo gratuito para converter PPSM para PNG"
  description="[Experimente nosso aplicativo gratuito para converter PPT para PNG](https://products.aspose.app/slides/conversion/ppt-to-png)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outras conversões compatíveis" subTitle="Você também pode converter PPSM em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Imagem em formato bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="Formato de metarquivo aprimorado" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Formato de intercâmbio gráfico" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-jpeg/" name="PPSM TO JPEG" description="Imagem JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="Formato de apresentação do OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="Formato padrão do OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Formato de Documento Portátil" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Arquivo de modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="Apresentação de slides do PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="Apresentação de slides do PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Arquivo de apresentação habilitado para macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Formato de apresentação XML aberto" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Gráficos vetoriais escalonáveis" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Formato de imagem marcada" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-xml/" name="PPSM TO XML" description="Extensible Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="Especificações do papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
