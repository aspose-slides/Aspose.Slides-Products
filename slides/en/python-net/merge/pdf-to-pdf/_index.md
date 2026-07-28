---
title: Merge PDF Files in Python
url: /python-net/merge/pdf-to-pdf/
keywords: Merge PDF, PDF to PDF, Join PDF, Combine PDF, Python API, Python Library
description: Merge multiple PDF files in Python and save their pages as a single PDF document.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PDF Files in Python" h2="Import pages from multiple PDF files and save the combined content as one PDF document with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Merge PDF to PDF Using Aspose.Slides" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you combine PDF files by importing their pages into a `Presentation`. `SlideCollection.add_from_pdf` converts each PDF page into a slide and appends it to the presentation. After importing all source files, call `Presentation.save` with `SaveFormat.PDF` to export the combined slides as one PDF document.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge PDF to PDF in Python" %}}
Create a presentation without its default blank slide, import the source PDF files in the required order, and save the combined slides as a single PDF document.

{{% blocks/products/pf/agp/code-block title="Python code for merging multiple PDF files into one PDF document" offSpacer="true" %}}
```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document1.pdf")
    presentation.slides.add_from_pdf("document2.pdf")

    presentation.save("merged-document.pdf", slides.export.SaveFormat.PDF)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to Merge PDF Files with Aspose.Slides for Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two PDF files and save their pages as a single PDF document." >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install Aspose.Slides for Python via .NET by following the [installation guide](https://docs.aspose.com/slides/python-net/installation/).
```console
pip install aspose-slides
```
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Make the `aspose.slides` namespace available in your Python project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and remove its default blank slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Pass each source PDF file to [`SlideCollection.add_from_pdf`](https://reference.aspose.com/slides/python-net/aspose.slides/slidecollection/add_from_pdf/) in the required order.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `Presentation.save` with `SaveFormat.PDF` to create the merged PDF document.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}





{{< blocks/products/pf/agp/other-supported-section title="Merge Other Files" subTitle="You can also combine files in other formats into a single output file." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/png-to-pdf/" name="PNG TO PDF" >}}
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
