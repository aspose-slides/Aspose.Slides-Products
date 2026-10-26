---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Buscar texto en presentaciones PPTX con Python
url: /es/python-net/search/pptx/
description: Busque texto en presentaciones PPTX con Python y Aspose.Slides.
keywords: buscar texto en PPTX, encontrar palabras en PPTX, buscar en presentación PPTX con Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Buscar texto en presentaciones PPTX con Python" h2="Cree aplicaciones Python que encuentren texto en presentaciones de PowerPoint con Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Buscar texto en una presentación PPTX con Python" variant="code" %}}

Con [Aspose.Slides for Python via .NET](/slides/es/python-net/), puede usar [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) para encontrar en cada diapositiva los marcos de texto que contienen una cadena determinada.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Buscar texto en una presentación PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo buscar texto en PPTX con Python" intro="Siga estos pasos para buscar texto en una presentación PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra el archivo PPTX con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recorra las diapositivas y llame a [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) para cada una.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lea la propiedad `text` de cada marco de texto coincidente.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Creado con Aspose.Slides" title="Buscar texto en archivos PPTX en línea" description="La aplicación gratuita Aspose.Slides Search está creada con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/es/python-net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPTX." button="Abrir Aspose.Slides Search" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides encuentra texto antes de escribir código.
- Busque texto sin formato o expresiones regulares en su archivo PPTX.
- Descargue las coincidencias como archivo de texto.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con la búsqueda" subTitle="Use Python para buscar texto en otros formatos de presentación compatibles." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
