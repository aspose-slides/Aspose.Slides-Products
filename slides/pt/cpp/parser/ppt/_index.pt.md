---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 2780
title: Extrair texto de apresentações PPT com C++
url: /pt/cpp/parser/ppt/ 
description: Extraia texto de apresentações PPT em C++. Use o Aspose.Slides for C++ para analisar slides, quadros de texto, parágrafos e partes.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Analisar apresentações PPT em C++" h2="Use o Aspose.Slides for C++ para extrair texto dos slides sem o Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Analisar um arquivo PPT com C++" %}}

Use o Aspose.Slides for C++ para analisar arquivos de apresentação PPT e extrair texto dos slides. A API expõe o texto dos slides por meio de `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph` e `IPortion`, para que você leia o conteúdo de texto sem automatizar o Microsoft PowerPoint. Instale o pacote [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) pelo NuGet ou use o comando abaixo no Console do Gerenciador de Pacotes.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Analisar arquivos PPT – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como analisar arquivos PPT em C++" intro="Extraia texto de arquivos PPT com o Aspose.Slides for C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo PPT com a classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenha os objetos `ITextFrame` do primeiro slide com `SlideUtil::GetAllTextBoxes`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Percorra os objetos `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Percorra os objetos `IParagraph` de cada `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Percorra os objetos `IPortion` de cada `IParagraph`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Leia o texto com `get_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos do sistema" intro="O Aspose.Slides for C++ é compatível com as principais plataformas de desktop e servidor. Verifique se o seu projeto atende aos seguintes pré-requisitos." %}}

-  Microsoft Windows, Linux, macOS ou outro sistema operacional compatível com o runtime C++ suportado.
-  A biblioteca Aspose.Slides for C++ referenciada no seu projeto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Criado com Aspose.Slides" title="Extraia texto e imagens online" description="O aplicativo gratuito Aspose.Slides Parser é criado com [Aspose.Slides for C++](https://products.aspose.com/slides/pt/cpp/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPT." button="Abrir Aspose.Slides Parser" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides lê seus arquivos antes de escrever código.
- Carregue um arquivo PPT e obtenha o texto e as imagens.
- Baixe tudo em um único arquivo ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Um arquivo PPT é um arquivo de apresentação do Microsoft PowerPoint 97-2003. Ele armazena slides, texto, imagens, multimídia e objetos incorporados no formato de arquivo binário do PowerPoint usado antes do formato Open XML PPTX.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos de análise compatíveis" subTitle="Com C++, você também pode analisar outros formatos de apresentação." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/cpp/parser/odp/" name="ODP" description="Apresentação OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/cpp/parser/pptx/" name="PPTX" description="Apresentação PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
