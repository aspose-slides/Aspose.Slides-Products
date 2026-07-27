---
title: Edit PDF in Python
url: /python-net/editor/pdf/
keywords: Edit PDF, PDF, Python API, Python Library
description: Import PDF pages, add text or shapes, and export the edited result as PDF with Aspose.Slides for Python via .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit PDF in Python" h2="Import PDF pages, add presentation elements, and export the result as PDF with Python" >}}

{{% blocks/products/pf/feature-page-section h2="Edit PDF using Aspose.Slides" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you import PDF pages as slides, add presentation elements such as text and shapes, and export the edited presentation as a new PDF document. This workflow overlays new slide content rather than modifying the original PDF objects.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edit PDF in Python" %}}
The following example imports a PDF file into a `Presentation`, adds a text-bearing shape to the first imported slide, and exports the result as a new PDF document.

{{% blocks/products/pf/agp/code-block title="Python code for editing PDF" offSpacer="true" %}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")

    slide = presentation.slides[0]
    text_shape = slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 10, 10, 300, 50)
    text_shape.text_frame.text = "New text"

    presentation.save("edited-document.pdf", slides.export.SaveFormat.PDF)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to edit PDF in Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install Aspose.Slides for Python via .NET by following the [installation guide](https://docs.aspose.com/slides/python-net/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create an empty `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Remove the default blank slide from the presentation.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Pass the source PDF file to `SlideCollection.add_from_pdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Access the imported slide through a `slide` variable, add an `AutoShape`, and set its text.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save` with `SaveFormat.PDF` to create the edited PDF document.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Edit other files" subTitle="You can also edit files in other formats" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/editor/ppt/" name="Edit PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/editor/html/" name="Edit HTML" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
