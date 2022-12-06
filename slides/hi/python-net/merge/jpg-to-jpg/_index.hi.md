---
title: जेपीजी छवियों को पायथन में मर्ज करें
url: /hi/python-net/merge/jpg-to-jpg/
keywords: जेपीजी, जेपीईजी को जेपीजी में मर्ज करें, जेपीजी से जुड़ें, जेपीजी, पायथन एपीआई, पायथन लाइब्रेरी को मिलाएं
description: पायथन में जेपीजी को जेपीजी में मर्ज करें। जेपीजी फाइलों को गठबंधन करने के लिए पायथन लाइब्रेरी एपीआई का प्रयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="जेपीजी को पायथन में मर्ज करें" h2="पायथन कोड का उपयोग करके जेपीजी छवियों को मर्ज करने के लिए हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म पायथन लाइब्रेरी" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके JPG को JPG में मर्ज करें" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) एक शक्तिशाली पायथन लाइब्रेरी है जिसका उपयोग प्रस्तुतियों, छवियों और अन्य फ़ाइलों को मर्ज और हेरफेर करने के लिए किया जाता है। जब आप जेपीजी को जेपीजी में मर्ज करते हैं, तो आप प्रभावी रूप से एक तस्वीर प्राप्त करने के लिए दो छवियों को जोड़ रहे हैं।

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="पायथन में जेपीजी को जेपीजी में मर्ज करें" %}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ JPG फ़ाइलों को जल्दी से मर्ज कर सकते हैं

{{% blocks/products/pf/agp/code-block title="जेपीजी को जेपीजी में विलय करने के लिए पायथन कोड" offSpacer="true" %}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image1 = pres.images.add_image(drawing.Bitmap("image1.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 100, 100, image1)

    image2 = pres.images.add_image(drawing.Bitmap("image2.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 200, 100, 100, image2)

    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.jpg".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.jpeg)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="जेपीजी को पायथन में कैसे मर्ज करें" >}}


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
उन जेपीजी फाइलों को लोड करें जिन्हें आप पिक्चर फ्रेम के रूप में मर्ज करना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणामी JPG छवि को सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="अन्य फ़ाइलें मर्ज करें" subTitle="आप एकल फ़ाइल प्राप्त करने के लिए फ़ाइलों को अन्य स्वरूपों में भी संयोजित कर सकते हैं" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}