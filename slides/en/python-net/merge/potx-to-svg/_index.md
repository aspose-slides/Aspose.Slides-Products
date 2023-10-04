---
title:  Merge POTX Files To SVG Using Python
url: /python-net/merge/potx-to-svg/
keywords: Merge POTX to SVG, Join POTX to SVG, Combine POTX to SVG, PowerPoint, Presentation, SVG, Python, Aspose
description: Merge multiple POTX files in Python. 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge POTX files to SVG together in Python" h2="High-speed and cross-platform Python API that helps in developing applications with the ability to create, merge, inspect, or convert Microsoft PowerPoint and OpenOffice presentation files without the use of any software like Microsoft or Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Merge POTX to SVG in Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/python-net/) is a powerful Python library for creating and manipulating presentation files. Moreover, it provides flexible ways to combine multiple POTX presentations. When you merge one presentation to another, you are effectively combining their slides in a single presentation to obtain one file. Aspose.Slides allows you merge two presentations in different ways. You get to merge presentations with all their shapes, styles, texts, formatting, comments, animations, etc. without having to worry about loss of quality or data.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge POTX files to SVG using Python" %}}
To merge the PowerPoint presentations, you will need to clone the slides from one presentation to the other.

{{% blocks/products/pf/agp/code-block title="Python code for merge multiple POTX into single SVG file" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.potx") as pres1:
    with slides.Presentation("presentation2.potx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge POTX to SVG using Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to merge two POTX files and save result as SVG in Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Python project.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source POTX files in Python.
```
pres1 = slides.Presentation('pres1.potx')
pres2 = slides.Presentation('pres2.potx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combine POTX files using [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) method.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save presentation and get result as single SVG file.
```
for slide in pres1.slides:
    with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
        slide.write_as_svg(file)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}


{{< blocks/products/pf/agp/other-supported-section title="Export POTX To Other Supported Formats" subTitle="You can also combine POTX and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-pptx/" name="POTX TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-ppt/" name="POTX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-pdf/" name="POTX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-html/" name="POTX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-png/" name="POTX TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-bmp/" name="POTX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-jpg/" name="POTX TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-fodp/" name="POTX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-gif/" name="POTX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-odp/" name="POTX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-otp/" name="POTX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-pot/" name="POTX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-potm/" name="POTX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-pps/" name="POTX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-ppsm/" name="POTX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-ppsx/" name="POTX TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-pptm/" name="POTX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-tiff/" name="POTX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/potx-to-xps/" name="POTX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}