---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Eliminar comentarios de PPTX en Python
url: /es/python-net/annotation/pptx/ 
description: Elimine comentarios y autores de comentarios de presentaciones PPTX en Python con Aspose.Slides for Python via .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Eliminar comentarios y autores de comentarios de PPTX en Python" h2="Use Aspose.Slides for Python via .NET para eliminar los comentarios de una presentación y sus autores." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Eliminar comentarios de PPTX mediante Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/es/python-net/) proporciona acceso a los comentarios y autores de comentarios almacenados en una presentación PPTX. Cargue el archivo con `Presentation`, vacíe la colección `comments` de cada autor, vacíe `comment_authors` y guarde el resultado en formato PPTX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Eliminar comentarios de PPTX en Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo eliminar comentarios de PPTX mediante Python" intro="Siga estos pasos para eliminar todos los comentarios y autores de comentarios de una presentación PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale [Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra el archivo PPTX con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Recorra `comment_authors` y vacíe la colección `comments` de cada autor.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vacíe la colección `comment_authors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame a `save` con `SaveFormat.PPTX` para escribir la presentación PPTX actualizada.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Creado con Aspose.Slides" title="Eliminar comentarios de PPTX en línea" description="La aplicación gratuita Aspose.Slides Annotation está creada con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/es/python-net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPTX." button="Abrir Aspose.Slides Annotation" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides elimina comentarios antes de escribir código.
- Elimine todos los comentarios de su archivo PPTX.
- Descargue el archivo limpio.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con anotaciones" subTitle="Con Python, también puede eliminar anotaciones de otros formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
