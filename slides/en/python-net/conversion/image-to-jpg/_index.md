---
title: Convert Image to JPG in Python
url: /python-net/conversion/image-to-jpg/
keywords: Image to JPG, Convert Image to JPG, Python API, Python Library, Image, JPG
description: Convert Image to JPG in Python. Use Python library API to convert Image files to JPGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert Image to JPG in Python" h2="High-speed and cross-platform Python Library that helps in developing applications with the ability to create, merge, inspect, or convert Microsoft PowerPoint and OpenOffice presentation files without the use of any software like Microsoft or Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convert Image to JPG in Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/python-net/) is a powerful Python library for creating and manipulating presentation files. Moreover, it provides flexible ways to convert Image to JPG. Using **Aspose.Slides for Python via .NET**, any developer or application can convert Image to JPG files with just a few lines of Python code.

As a modern document processing API, Aspose.Slides for Python exports Image files to JPG file formats quickly. Aspose PowerPoint library allows you to convert Image to JPGs and many other file formats

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Image to JPG using Python" %}}
To convert the Image to JPG, you will need to create Presentation from Image file and save it as JPG.

{{% blocks/products/pf/agp/code-block title="Python code for converting Image into JPG" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.jpg".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.jpeg)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert Image to JPG using Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert Image to JPG in Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/python-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Python project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source Image files in Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as JPG file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[How to Convert PPT to HTML in Python](https://products.aspose.com/slides/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert Image To Other Supported Formats" subTitle="You can also convert Image and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}