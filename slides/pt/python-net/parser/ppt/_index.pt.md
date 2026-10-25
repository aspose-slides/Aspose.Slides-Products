---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Extrair texto de arquivos PPT com Python
url: /pt/python-net/parser/ppt/
description: Extraia texto e detalhes de formatação de texto de apresentações PPT com Python.
keywords: analisar PPT com Python, analisador de PPT em Python, extrair dados de PPT em Python, extrair texto de PPT com Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Extrair texto de apresentações PPT com Python" h2="Crie aplicativos Python que extraem texto e detalhes de formatação de apresentações do PowerPoint com o Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Extrair texto de uma apresentação PPT com Python" variant="code" %}}

O [**Aspose.Slides for Python via .NET**](/slides/pt/python-net/) oferece o método estático [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) em `SlideUtil`. Ele retorna os objetos `TextFrame` de toda a apresentação e pode incluir o texto dos slides mestres. O exemplo a seguir extrai o texto e os detalhes de fonte relacionados de uma apresentação PPT.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Extrair texto de uma apresentação PPT – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.ppt") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como extrair texto de PPT com Python" intro="Siga estas etapas para extrair texto de um arquivo PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra o arquivo PPT com `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame `SlideUtil.get_all_text_frames` e indique se os slides mestres devem ser incluídos.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Percorra os objetos `TextFrame` retornados.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Percorra a coleção `paragraphs` de cada quadro de texto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Percorra a coleção `portions` de cada parágrafo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Leia `text` e as propriedades de formatação da parte atual.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Criado com Aspose.Slides" title="Extraia texto e imagens online" description="O aplicativo gratuito Aspose.Slides Parser é criado com [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pt/python-net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPT." button="Abrir Aspose.Slides Parser" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides lê seus arquivos antes de escrever código.
- Carregue um arquivo PPT e obtenha o texto e as imagens.
- Baixe tudo em um único arquivo ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos de análise compatíveis" subTitle="Com Python, você também pode extrair texto de outros formatos de apresentação compatíveis." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
