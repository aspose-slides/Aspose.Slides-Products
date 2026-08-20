---
lastmod: 2026-07-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to Image in Python
url: /python-net/conversion/pdf-to-image/
keywords: PDF to Image, Convert PDF to Image, Python API, Python Library, PDF, Image
description: Convert PDF pages to images in Python. Use the Aspose.Slides Python API to import a PDF and render each page as a PNG image.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PDF to Image in Python" h2="Import PDF pages and render them as images with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to Image in Python" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you convert PDF pages to raster images programmatically. The API provides `SlideCollection.add_from_pdf` for importing PDF content and `Slide.get_image` for rendering each imported page.

The example below saves each PDF page as a separate PNG image. You can select another supported raster format by changing the output extension and the `ImageFormat` value.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to Image using Python" %}}
Create a `Presentation`, remove its default blank slide, import the PDF pages, and render each imported `Slide` as an image.

{{% blocks/products/pf/agp/code-block title="Python code for converting PDF into Image" offSpacer="true" %}}

```python
with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")

    for slide in presentation.slides:
        file_path = f"document_page_{slide.slide_number}.png"
        with slide.get_image() as slide_image:
            slide_image.save(file_path, slides.ImageFormat.PNG)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Convert PDF to Images Using the Aspose.Slides Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PDF pages to images in Python." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and remove its default blank slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the source PDF by using `SlideCollection.add_from_pdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each imported `Slide` with `Slide.get_image` and save it by using `IImage.save`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF documents to other supported formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
