---
title: पायथन का उपयोग करके PPTX फ़ाइलों को PNG में मर्ज करें
url: /hi/python-net/merge/pptx-to-png/
keywords: PPTX को PNG में मिलाएं, PPTX से PNG में शामिल हों, PPTX से PNG, PowerPoint, प्रेजेंटेशन, PNG, Python, Aspose को मिलाएं
description: पायथन में कई PPTX फ़ाइलें मर्ज करें।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python में PPTX फ़ाइलों को PNG में एक साथ मर्ज करें" h2="हाई-स्पीड और क्रॉस-प्लेटफॉर्म पायथन एपीआई जो माइक्रोसॉफ्ट या ओपन ऑफिस, एडोब पीडीएफ जैसे किसी भी सॉफ्टवेयर के उपयोग के बिना माइक्रोसॉफ्ट पावरपॉइंट और ओपनऑफिस प्रेजेंटेशन फाइलों को बनाने, मर्ज करने, निरीक्षण करने या परिवर्तित करने की क्षमता वाले अनुप्रयोगों को विकसित करने में मदद करता है।" >}}

{{% blocks/products/pf/feature-page-section h2="पायथन में PPTX को PNG में मर्ज करें" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) प्रेजेंटेशन फाइल बनाने और उसमें हेरफेर करने के लिए एक शक्तिशाली पायथन लाइब्रेरी है। इसके अलावा, यह कई PPTX प्रस्तुतियों को संयोजित करने के लचीले तरीके प्रदान करता है। जब आप एक प्रस्तुति को दूसरे में मर्ज करते हैं, तो आप एक फ़ाइल प्राप्त करने के लिए उनकी स्लाइड्स को एक प्रस्तुति में प्रभावी रूप से संयोजित कर रहे हैं। Aspose.Slides आपको दो प्रस्तुतियों को अलग-अलग तरीकों से मर्ज करने की अनुमति देता है। आप गुणवत्ता या डेटा के नुकसान के बारे में चिंता किए बिना प्रस्तुतियों को उनके सभी आकारों, शैलियों, ग्रंथों, स्वरूपण, टिप्पणियों, एनिमेशन आदि के साथ मर्ज कर सकते हैं।

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python का उपयोग करके PPTX फ़ाइलों को PNG में मर्ज करें" %}}
PowerPoint प्रस्तुतियों को मर्ज करने के लिए, आपको स्लाइडों को एक प्रस्तुति से दूसरी प्रस्तुति में क्लोन करना होगा।

{{% blocks/products/pf/agp/code-block title="एकाधिक PPTX को एकल PNG फ़ाइल में मर्ज करने के लिए पायथन कोड" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation1.pptx") as pres1:
    with slides.Presentation("presentation2.pptx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    for slide in pres1.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API का उपयोग करके PPTX को PNG में कैसे मर्ज करें?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये दो PPTX फाइलों को मर्ज करने और परिणाम को पायथन में PNG के रूप में सहेजने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) इंस्टॉल करें।
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने पायथन प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पायथन में स्रोत PPTX फ़ाइलें खोलें।
```
pres1 = slides.Presentation('pres1.pptx')
pres2 = slides.Presentation('pres2.pptx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) पद्धति का उपयोग करके PPTX फाइलों को मिलाएं।
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति सहेजें और परिणाम एकल PNG फ़ाइल के रूप में प्राप्त करें।
```
for slide in pres1.slides:
    slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PPTX अन्य समर्थित प्रारूपों में निर्यात करें" subTitle="आप PPTX को भी जोड़ सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। सभी समर्थित प्रारूप नीचे देखें" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-ppt/" name="PPTX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-pdf/" name="PPTX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-html/" name="PPTX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-bmp/" name="PPTX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-jpg/" name="PPTX TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-fodp/" name="PPTX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-gif/" name="PPTX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-odp/" name="PPTX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-otp/" name="PPTX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-pot/" name="PPTX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-potm/" name="PPTX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-potx/" name="PPTX TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-pps/" name="PPTX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-ppsm/" name="PPTX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-ppsx/" name="PPTX TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-pptm/" name="PPTX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-svg/" name="PPTX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-tiff/" name="PPTX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx-to-xps/" name="PPTX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}