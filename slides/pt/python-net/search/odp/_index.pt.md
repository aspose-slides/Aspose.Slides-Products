---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Pesquisar texto em apresentações ODP com Python
url: /pt/python-net/search/odp/
description: Pesquise texto em apresentações ODP com Python e Aspose.Slides.
keywords: pesquisar texto em ODP, localizar palavras em ODP, pesquisar apresentação ODP com Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Pesquisar texto em apresentações ODP com Python" h2="Crie aplicativos Python que localizam texto em apresentações OpenDocument com o Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Pesquisar texto em uma apresentação ODP com Python" variant="code" %}}

Com o [Aspose.Slides for Python via .NET](/slides/pt/python-net/), você pode usar [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) para localizar em cada slide os quadros de texto que contêm uma determinada string.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Pesquisar texto em uma apresentação ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como pesquisar texto em ODP com Python" intro="Siga estas etapas para pesquisar texto em uma apresentação ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra o arquivo ODP com `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Percorra os slides e chame [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) para cada um.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Leia a propriedade `text` de cada quadro de texto encontrado.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Criado com Aspose.Slides" title="Pesquisar texto em arquivos ODP online" description="O aplicativo gratuito Aspose.Slides Search é criado com [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pt/python-net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos ODP." button="Abrir Aspose.Slides Search" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides localiza texto antes de escrever código.
- Pesquise texto simples ou expressões regulares no seu arquivo ODP.
- Baixe os resultados como um arquivo de texto.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com pesquisa" subTitle="Use Python para pesquisar texto em outros formatos de apresentação compatíveis." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/python-net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/python-net/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
