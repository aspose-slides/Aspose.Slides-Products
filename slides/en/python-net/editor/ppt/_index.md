---
lastmod: 2026-07-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit PPT in Python
url: /python-net/editor/ppt/
keywords: Edit PPT, Edit PowerPoint, PPT, PowerPoint, Python API, Python Library
description: Add text and shapes to PPT presentations and save the edited files with Aspose.Slides for Python via .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edit PPT in Python" h2="Add text, shapes, and other presentation elements to PPT files with Python" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PPT in Python" variant="code" %}}

The following example opens a PPT presentation, adds a text-bearing shape to its first slide, and saves the edited presentation as a new PPT file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Python code for editing PPT" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    slide = presentation.slides[0]
    text_shape = slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 10, 10, 300, 50)
    text_shape.text_frame.text = "New text"

    presentation.save("edited-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PPT using Aspose.Slides" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you load PPT presentations, edit their slides, and save the changes without Microsoft PowerPoint. You can modify text and shapes or add new presentation elements programmatically.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to edit PPT in Python" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install Aspose.Slides for Python via .NET by following the [installation guide](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source PPT file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access the target slide through a `slide` variable.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `ShapeCollection.add_auto_shape` to add a rectangle to the slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Set the shape's `text_frame.text` value.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `Presentation.save` with `SaveFormat.PPT` to write the edited presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Edit other files" subTitle="You can also edit files in other formats" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/editor/pdf/" name="Edit PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
