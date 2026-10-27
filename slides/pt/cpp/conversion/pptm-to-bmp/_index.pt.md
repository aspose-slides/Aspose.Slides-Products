---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter PPTM para BMP via aplicativo C++
weight: 490
url: /pt/cpp/conversion/pptm-to-bmp/ 
description: Exemplo de código de conversão C++ para documento PPTM para formato BMP. Use o código de exemplo para conversão em lote de PPTM para BMP em qualquer aplicativo C++.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converter PPTM para BMP via C++" h2="Conversão de PPTM para BMP de alto desempenho usando biblioteca C++ sem a necessidade de instalação do Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Como converter PPTM para BMP usando C++" %}}

Para converter PPTM para BMP, usaremos
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código-fonte de conversão de PPTM para BMP C++" >}}
```cs
// Load the PPTM
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.pptm");

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

bitmap->Save(u"output.bmp", ImageFormat::get_Bmp());
	
//Iterate through each slide via index and convert

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Etapas para converter PPTM para BMP via C++" intro="Os desenvolvedores de C++ podem facilmente converter arquivos PPTM para BMP em apenas algumas linhas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo PPTM com Aspose.Slides for C++ Presentation Object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Selecione o primeiro slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Defina as dimensões desejadas.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenha a miniatura com as dimensões desejadas.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método Save() com parâmetro de saída BMP .{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra o arquivo BMP em um programa compatível.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos de sistema" intro="Antes de executar o código de exemplo de conversão C++, certifique-se de ter os seguintes pré-requisitos." %}}

- Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.
- Aspose.Slides for C++ DLL referenciado em seu projeto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Criado com Aspose.Slides" title="Converter PPTM para BMP online" description="O aplicativo gratuito Aspose.Slides Conversion é criado com [Aspose.Slides for C++](https://products.aspose.com/slides/pt/cpp/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPTM." button="Abrir Aspose.Slides Conversion" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" upload="Arraste ou envie seu arquivo" saveAs="Salvar como" convert="Converter" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides converte arquivos antes de escrever código.
- Envie arquivos PPTM e salve-os como BMP.
- Baixe o resultado ou converta mais arquivos.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outras conversões compatíveis" subTitle="Você também pode converter PPTM em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-emf/" name="PPTM TO EMF" description="Formato de metarquivo aprimorado" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Formato de intercâmbio gráfico" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-html/" name="PPTM TO HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-jpeg/" name="PPTM TO JPEG" description="Imagem JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Formato de apresentação do OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Formato padrão do OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Formato de Documento Portátil" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-png/" name="PPTM TO PNG" description="Gráficos Portáteis de Rede" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-pot/" name="PPTM TO POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Arquivo de modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Apresentação de slides do PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Apresentação de slides habilitada para macro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Apresentação de slides do PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Formato de apresentação XML aberto" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Gráficos vetoriais escalonáveis" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Formato de imagem marcada" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-xml/" name="PPTM TO XML" description="Extensible Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/cpp/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Especificações do papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
