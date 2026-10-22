---
lastmod: 2026-07-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit HTML in Python
url: /python-net/editor/html/
keywords: Edit HTML, HTML, Python API, Python Library
description: Import HTML content, add text or shapes, and export the edited result as HTML5 with Aspose.Slides for Python via .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edit HTML in Python" h2="Import HTML content, add presentation elements, and export the result as HTML5 with Python" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit HTML in Python" variant="code" %}}

The following example imports an HTML file into a `Presentation`, adds a text-bearing shape to the first imported slide, and exports the result as HTML5.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for editing HTML" >}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)

    with open("page.html", "rb") as html_stream:
        presentation.slides.add_from_html(html_stream)

    slide = presentation.slides[0]
    text_shape = slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 10, 10, 300, 50)
    text_shape.text_frame.text = "New text"

    presentation.save("edited-page.html", slides.export.SaveFormat.HTML5)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit HTML using Aspose.Slides" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you import HTML content into slides, add presentation elements such as text and shapes, and export the edited presentation as HTML5. This workflow changes the imported slide content rather than the original HTML document.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to edit HTML in Python" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install Aspose.Slides for Python via .NET by following the [installation guide](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create an empty `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Remove the default blank slide from the presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the HTML file as a binary stream and pass it to `SlideCollection.add_from_html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access the imported slide through a `slide` variable, add an `AutoShape`, and set its text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Presentation.save` with `SaveFormat.HTML5` to export the edited content.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Edit other files" subTitle="You can also edit files in other formats" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/editor/ppt/" name="Edit PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
