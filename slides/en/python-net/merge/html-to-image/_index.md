---
lastmod: 2026-07-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge HTML Files and Export to Images in Python
url: /python-net/merge/html-to-image/
keywords: Merge HTML to image, HTML to image, Join HTML, Combine HTML, Image, Python API, Python Library
description: Merge multiple HTML files in Python and render the combined content as PNG images.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge HTML Files and Export to Images in Python" h2="Combine HTML documents and render the resulting slides as PNG images with a cross-platform Python API" >}}

{{% blocks/products/pf/feature-page-section h2="Merge HTML Files and Export to Images Using Aspose.Slides" %}}

[*Aspose.Slides for Python via .NET*](/slides/python-net/) lets you import multiple HTML documents into one `Presentation` and render the resulting slides as images. Use `SlideCollection.add_from_html` to import each HTML stream, then call `Slide.get_image` and save each resulting `IImage` with `ImageFormat.PNG`.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge HTML Files to PNG Images in Python" %}}
Create a `Presentation`, import the source HTML files in order, and render each generated `Slide` as a separate PNG image.

{{% blocks/products/pf/agp/code-block title="Python code for merging HTML files and exporting the slides as PNG images" offSpacer="true" %}}

```python
html_file_paths = ["first.html", "second.html"]

with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)

    for file_path in html_file_paths:
        with open(file_path, "rb") as html_stream:
            presentation.slides.add_from_html(html_stream)

    for slide in presentation.slides:
        file_path = f"merged_slide_{slide.slide_number}.png"
        with slide.get_image(1, 1) as slide_image:
            slide_image.save(file_path, slides.ImageFormat.PNG)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to Merge HTML Files and Export Them as Images in Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to combine HTML files and render the resulting slides as PNG images." >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install [*Aspose.Slides for Python via .NET*](/slides/python-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides` module in your Python project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and remove its default blank slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Open each HTML file and pass its stream to `SlideCollection.add_from_html`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each imported `Slide` with `Slide.get_image`, then call `IImage.save` with `ImageFormat.PNG`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}





{{< blocks/products/pf/agp/other-supported-section title="Merge Other Files" subTitle="You can also combine files in other formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/merge/image-to-bmp/" name="IMAGE TO BMP" >}}




{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
