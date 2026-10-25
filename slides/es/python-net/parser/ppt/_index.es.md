---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Extraer texto de archivos PPT con Python
url: /es/python-net/parser/ppt/
description: Extraiga texto y detalles de formato de texto de presentaciones PPT con Python.
keywords: analizar PPT con Python, analizador de PPT en Python, extraer datos de PPT en Python, extraer texto de PPT con Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Extraer texto de presentaciones PPT con Python" h2="Cree aplicaciones Python que extraigan texto y detalles de formato de presentaciones de PowerPoint con Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Extraer texto de una presentación PPT con Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/es/python-net/) ofrece el método estático [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) de `SlideUtil`. Devuelve los objetos `TextFrame` de toda la presentación y puede incluir el texto de las diapositivas maestras. El siguiente ejemplo extrae el texto y los detalles de fuente relacionados de una presentación PPT.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Extraer texto de una presentación PPT – Python" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo extraer texto de PPT con Python" intro="Siga estos pasos para extraer texto de un archivo PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra el archivo PPT con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame a `SlideUtil.get_all_text_frames` e indique si se deben incluir las diapositivas maestras.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recorra los objetos `TextFrame` devueltos.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recorra la colección `paragraphs` de cada marco de texto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recorra la colección `portions` de cada párrafo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lea `text` y las propiedades de formato de la porción actual.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Creado con Aspose.Slides" title="Extraer texto e imágenes en línea" description="La aplicación gratuita Aspose.Slides Parser está creada con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/es/python-net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPT." button="Abrir Aspose.Slides Parser" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides lee sus archivos antes de escribir código.
- Cargue un archivo PPT y obtenga su texto e imágenes.
- Descargue todo en un único archivo ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos de análisis compatibles" subTitle="Con Python, también puede extraer texto de otros formatos de presentación compatibles." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
