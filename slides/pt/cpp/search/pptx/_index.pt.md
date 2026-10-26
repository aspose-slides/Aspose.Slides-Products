---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Pesquisar texto em apresentações PPTX usando C++
url: /pt/cpp/search/pptx/
description: Pesquise texto em apresentações PPTX em C++. Use o Aspose.Slides for C++ para localizar texto em arquivos de apresentação.
keywords: pesquisar palavras em PPTX, localizar texto em PPTX, pesquisar texto de apresentação PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Pesquisar texto em PPTX usando C++" h2="Use o Aspose.Slides for C++ para localizar texto em arquivos de apresentação sem o Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Pesquisar texto em uma apresentação PPTX com C++" variant="code" %}}

O Aspose.Slides for C++ permite pesquisar texto em apresentações PPTX. Use `SlideUtil::GetAllTextBoxes` para reunir os quadros de texto de um slide e, em seguida, verifique se o texto deles contém a frase desejada.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Pesquisar texto em uma apresentação PPTX usando C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como pesquisar texto em PPTX com C++" intro="Siga estas etapas para pesquisar texto em uma apresentação PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo PPTX com a classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenha o slide desejado com `Presentation::get_Slides` e recupere os quadros de texto dele com [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Verifique se o texto de cada quadro contém a frase desejada.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Criado com Aspose.Slides" title="Pesquisar texto em arquivos PPTX online" description="O aplicativo gratuito Aspose.Slides Search é criado com [Aspose.Slides for C++](https://products.aspose.com/slides/pt/cpp/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPTX." button="Abrir Aspose.Slides Search" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides localiza texto antes de escrever código.
- Pesquise texto simples ou expressões regulares no seu arquivo PPTX.
- Baixe os resultados como um arquivo de texto.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com pesquisa" subTitle="Com C++, você também pode pesquisar texto nos seguintes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/cpp/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
