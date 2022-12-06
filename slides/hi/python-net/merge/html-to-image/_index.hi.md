---
title: Merge HTML to Image in Python
url: /hi/python-net/merge/html-to-image/
keywords: Merge HTML to image, HTML to image, Join HTML, Combine HTML, Image, Python API, Python Library
description: Merge HTML to image in Python. Use Python library API to combine HTML to image
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge image in Python" h2="High-speed and cross-platform Python library for merging HTML to image using Python code" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके HTML को इमेज में मर्ज करें" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) is a powerful Python library used to merge and manipulate presentations, HTML docs, and other files. When you merge HTML to image, you are effectively combining the contents in HTML documents to obtain a single image. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge HTML to image in Python" %}}
Using [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/), you can merge image files quickly with just a few lines of code

{{% blocks/products/pf/agp/code-block title="Python code for merging HTML to image" offSpacer="true" %}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    pres.slides.add_from_html(htmlText1)
    pres.slides.add_from_html(htmlText2)

    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge HTML to image in Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पुस्तकालय को अपनी परियोजना में संदर्भ के रूप में जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रेजेंटेशन क्लास का एक उदाहरण बनाएं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
उन HTML डॉक्स को लोड करें जिन्हें आप मर्ज करना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणामी छवि को सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="अन्य फ़ाइलें मर्ज करें" subTitle="आप एकल फ़ाइल प्राप्त करने के लिए फ़ाइलों को अन्य स्वरूपों में भी संयोजित कर सकते हैं" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/image-to-bmp/" name="IMAGE TO BMP" >}} 
    
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}