---
title: Python का उपयोग करके ODP प्रस्तुतिकरण फ़ाइलों में वॉटरमार्क जोड़ें
url: /hi/python-net/watermark/odp/
keywords: वॉटरमार्क जोड़ें ODP, टेक्स्ट वॉटरमार्क जोड़ें ODP, छवि वॉटरमार्क जोड़ें ODP
description: वॉटरमार्क को ODP प्रस्तुतिकरण में जोड़ने के लिए Python स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python का उपयोग करके ODP प्रस्तुतिकरण में वॉटरमार्क जोड़ें" h2="सर्वर-साइड API का उपयोग करके PPT, PPTX, या ODP प्रस्तुति में टेक्स्ट या इमेज वॉटरमार्क डालने के लिए अपना खुद का Python ऐप्लिकेशन बनाएं." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python द्वारा ODP प्रस्तुतिकरण में वॉटरमार्क जोड़ें" %}}
{Product_name} का उपयोग करके, आप वॉटरमार्क को ODP प्रस्तुतिकरण में जोड़ सकते हैं। वॉटरमार्क किसी भी प्रस्तुति का एक अनिवार्य हिस्सा हैं। इनका उपयोग प्रस्तुति की सामग्री को कॉपी किए जाने या अनुमति के बिना उपयोग किए जाने से बचाने के लिए किया जाता है। वॉटरमार्क एक दृश्य या अदृश्य छवि या पाठ है जिसे प्रस्तुति के शीर्ष पर रखा जाता है। इसका उपयोग प्रस्तुति के स्वामी की पहचान करने और अनधिकृत उपयोग को रोकने के लिए किया जा सकता है। वॉटरमार्क का उपयोग प्रस्तुति में एक पेशेवर स्पर्श जोड़ने और इसे और अधिक परिष्कृत दिखाने के लिए भी किया जा सकता है। 
{{% blocks/products/pf/agp/code-block title="Python का उपयोग करके ODP में टेक्स्ट वॉटरमार्क जोड़ें" offSpacer="true" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as draw

with slides.Presentation() as pres:
    master = pres.masters[0]

    watermarkShape = master.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 0, 0, 100, 100)
    watermarkTextFrame = watermarkShape.add_text_frame("Watermark")

    # Lock Watermark from Editing
    watermarkShape.shape_lock.select_locked = True
    watermarkShape.shape_lock.size_locked = True
    watermarkShape.shape_lock.text_locked = True
    watermarkShape.shape_lock.position_locked = True
    watermarkShape.shape_lock.grouping_locked = True
    
    # Set Text Watermark Transparency
    watermarkPortion = watermarkTextFrame.paragraphs[0].portions[0]
    watermarkPortion.portion_format.fill_format.fill_type = slides.FillType.SOLID
    watermarkPortion.portion_format.fill_format.solid_fill_color.color = draw.Color.from_argb(150, 200, 200, 200)
    
    # Set Font Size of Text Watermark
    watermarkPortion.portion_format.font_height = 16

    pres.save("watermark.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python का उपयोग करके ODP प्रस्तुतिकरण में इमेज वॉटरमार्क जोड़ें" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation() as presentation:
    with open("image1.png", "rb") as fs:
        data = fs.read()
    image = presentation.images.add_image(data)

    master = presentation.masters[0]
    watermarkShape = master.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 0, 0, image.width, image.height)
    
    watermarkShape.fill_format.fill_type = slides.FillType.PICTURE
    watermarkShape.fill_format.picture_fill_format.picture.image = image
    watermarkShape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH

    presentation.save("watermark2.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python के द्वारा ODP में वॉटरमार्क कैसे जोड़ें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये ODP फ़ाइलों में टेक्स्ट वॉटरमार्क जोड़ने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति के उदाहरण के साथ ODP लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
मास्टर प्रस्तुति का चयन करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddAutoShape पद्धति का उपयोग करके आकृति प्रकार जोड़ें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddTextFrame पद्धति का उपयोग करके वॉटरमार्क टेक्स्ट जोड़ें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम ODP प्रारूप में सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित प्रारूप" subTitle="Python का उपयोग करके, आप निम्न स्वरूपों में वॉटरमार्क भी जोड़ सकते हैं:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}