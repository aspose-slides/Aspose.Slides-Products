---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert HTML to PDF in Python
url: /python-net/conversion/html-to-pdf/
keywords: HTML to PDF, Convert HTML to PDF, Python API, Python Library, HTML, PDF
description: Convert HTML content to PDF in Python. Use the Aspose.Slides Python API to import HTML and export the generated presentation as a PDF document.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert HTML to PDF in Python" h2="Import HTML content and export it as PDF with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Convert HTML to PDF in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you import HTML content into a presentation and export the result as a PDF document. The API provides `SlideCollection.add_from_html` for importing HTML and `Presentation.save` with `SaveFormat.PDF` for creating the output file.

PDF preserves the generated slide layout in a fixed-layout document that is convenient for sharing and printing. This workflow does not require Microsoft PowerPoint or another presentation application.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert HTML to PDF using Python" %}}
Create a `Presentation`, remove its default blank slide, import the HTML file, and save the generated slides as a PDF document.

{{% blocks/products/pf/agp/code-block title="Python code for converting HTML into PDF" offSpacer="true" %}}

```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)

    with open("page.html", "rb") as html_stream:
        presentation.slides.add_from_html(html_stream)

    presentation.save("output.pdf", slides.export.SaveFormat.PDF)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert HTML to PDF using Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert HTML to PDF in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and remove its default blank slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source HTML file and pass its stream to `SlideCollection.add_from_html`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save` with the output file path and `SaveFormat.PDF`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Convert HTML to Other Supported Formats" subTitle="You can also import HTML content and save it in other supported formats." >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
