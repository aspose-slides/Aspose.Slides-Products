---
lastmod: 2026-07-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit HTML in Python
url: /python-net/editor/html/
keywords: Edit HTML, HTML, Python API, Python Library
description: Import HTML content, add text or shapes, and export the edited result as HTML5 with Aspose.Slides for Python via .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit HTML in Python" h2="Import HTML content, add presentation elements, and export the result as HTML5 with Python" >}}

{{% blocks/products/pf/feature-page-section h2="Edit HTML using Aspose.Slides" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you import HTML content into slides, add presentation elements such as text and shapes, and export the edited presentation as HTML5. This workflow changes the imported slide content rather than the original HTML document.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edit HTML in Python" %}}
The following example imports an HTML file into a `Presentation`, adds a text-bearing shape to the first imported slide, and exports the result as HTML5.

{{% blocks/products/pf/agp/code-block title="Python code for editing HTML" offSpacer="true" %}}
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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to edit HTML in Python" >}}


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
Open the HTML file as a binary stream and pass it to `SlideCollection.add_from_html`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Access the imported slide through a `slide` variable, add an `AutoShape`, and set its text.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save` with `SaveFormat.HTML5` to export the edited content.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Edit other files" subTitle="You can also edit files in other formats" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/editor/ppt/" name="Edit PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/editor/pdf/" name="Edit PDF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
