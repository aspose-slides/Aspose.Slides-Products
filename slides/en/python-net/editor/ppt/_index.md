---
title: Edit PPT in Python
url: /python-net/editor/ppt/
keywords: Edit PPT, Edit PowerPoint, PPT, PowerPoint, Python API, Python Library
description: Add text and shapes to PPT presentations and save the edited files with Aspose.Slides for Python via .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit PPT in Python" h2="Add text, shapes, and other presentation elements to PPT files with Python" >}}

{{% blocks/products/pf/feature-page-section h2="Edit PPT using Aspose.Slides" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you load PPT presentations, edit their slides, and save the changes without Microsoft PowerPoint. You can modify text and shapes or add new presentation elements programmatically.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edit PPT in Python" %}}
The following example opens a PPT presentation, adds a text-bearing shape to its first slide, and saves the edited presentation as a new PPT file.

{{% blocks/products/pf/agp/code-block title="Python code for editing PPT" offSpacer="true" %}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    slide = presentation.slides[0]
    text_shape = slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 10, 10, 300, 50)
    text_shape.text_frame.text = "New text"

    presentation.save("edited-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to edit PPT in Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install Aspose.Slides for Python via .NET by following the [installation guide](https://docs.aspose.com/slides/python-net/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source PPT file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Access the target slide through a `slide` variable.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `ShapeCollection.add_auto_shape` to add a rectangle to the slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Set the shape's `text_frame.text` value.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save` with `SaveFormat.PPT` to write the edited presentation.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Edit other files" subTitle="You can also edit files in other formats" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/editor/pdf/" name="Edit PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/editor/html/" name="Edit HTML" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
