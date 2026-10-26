---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Censurar texto en presentaciones PPT con Python
url: /es/python-net/redaction/ppt/
description: Busque y reemplace texto confidencial en presentaciones PPT con Python.
keywords: censurar PPT, buscar y reemplazar texto en PPT, actualizar presentación PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Censurar texto en presentaciones PPT con Python" h2="Cree aplicaciones Python que busquen y reemplacen texto confidencial en presentaciones con Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Censurar texto en una presentación PPT con Python" variant="code" %}}

Con [Aspose.Slides for Python via .NET](/slides/es/python-net/), puede reemplazar texto confidencial en toda una presentación PPT. Use `Presentation.replace_text` con `TextSearchOptions` para controlar la búsqueda y, a continuación, guarde la presentación modificada.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Censurar texto en una presentación PPT – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.ppt") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo censurar texto en una presentación PPT con Python" intro="Siga estos pasos para reemplazar texto confidencial en una presentación PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra el archivo PPT con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) con `TextSearchOptions` para reemplazar el texto necesario.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde la presentación modificada con `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Creado con Aspose.Slides" title="Censurar archivos PPT en línea" description="La aplicación gratuita Aspose.Slides Redaction está creada con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/es/python-net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPT." button="Abrir Aspose.Slides Redaction" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides busca y reemplaza texto antes de escribir código.
- Busque y reemplace texto en su archivo PPT, incluso con expresiones regulares.
- Descargue el archivo censurado.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con la censura" subTitle="Use Python para censurar texto en otros formatos de presentación compatibles." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
