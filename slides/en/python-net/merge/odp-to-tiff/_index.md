---
title:  Merge ODP Files To TIFF Using Python
url: /python-net/merge/odp-to-tiff/
keywords: Merge ODP to TIFF, Join ODP to TIFF, Combine ODP to TIFF, PowerPoint, Presentation, TIFF, Python, Aspose
description: Merge multiple ODP files in Python. 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge ODP files to TIFF together in Python" h2="High-speed and cross-platform Python API that helps in developing applications with the ability to create, merge, inspect, or convert Microsoft PowerPoint and OpenOffice presentation files without the use of any software like Microsoft or Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Merge ODP to TIFF in Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/python-net/) is a powerful Python library for creating and manipulating presentation files. Moreover, it provides flexible ways to combine multiple ODP presentations. When you merge one presentation to another, you are effectively combining their slides in a single presentation to obtain one file. Aspose.Slides allows you merge two presentations in different ways. You get to merge presentations with all their shapes, styles, texts, formatting, comments, animations, etc. without having to worry about loss of quality or data.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge ODP files to TIFF using Python" %}}
To merge the PowerPoint presentations, you will need to clone the slides from one presentation to the other.

{{% blocks/products/pf/agp/code-block title="Python code for merge multiple ODP into single TIFF file" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.odp") as pres1:
    with slides.Presentation("presentation2.odp") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.tiff", slides.export.SaveFormat.TIFF)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge ODP to TIFF using Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to merge two ODP files and save result as TIFF in Python." >}}

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
Open the source ODP files in Python.
```
pres1 = slides.Presentation('pres1.odp')
pres2 = slides.Presentation('pres2.odp')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combine ODP files using [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) method.
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save presentation and get result as single TIFF file.
```
pres1.save("presentation.tiff", slides.export.SaveFormat.TIFF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Export ODP To Other Supported Formats" subTitle="You can also combine ODP and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-pptx/" name="ODP TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-ppt/" name="ODP TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-pdf/" name="ODP TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-html/" name="ODP TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-png/" name="ODP TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-bmp/" name="ODP TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-jpg/" name="ODP TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-fodp/" name="ODP TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-gif/" name="ODP TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-otp/" name="ODP TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-pot/" name="ODP TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-potm/" name="ODP TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-potx/" name="ODP TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-pps/" name="ODP TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-ppsm/" name="ODP TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-ppsx/" name="ODP TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-pptm/" name="ODP TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-svg/" name="ODP TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/merge/odp-to-xps/" name="ODP TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}