---
title: पायथन का उपयोग करके FODP फ़ाइलों को TIFF में मर्ज करें
url: /hi/python-net/merge/fodp-to-tiff/
keywords: FODP को TIFF में मिलाएं, FODP से TIFF में शामिल हों, FODP से TIFF, PowerPoint, प्रेजेंटेशन, TIFF, Python, Aspose को मिलाएं
description: पायथन में कई FODP फ़ाइलें मर्ज करें।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Python में FODP फ़ाइलों को TIFF में एक साथ मर्ज करें" h2="हाई-स्पीड और क्रॉस-प्लेटफॉर्म पायथन एपीआई जो माइक्रोसॉफ्ट या ओपन ऑफिस, एडोब पीडीएफ जैसे किसी भी सॉफ्टवेयर के उपयोग के बिना माइक्रोसॉफ्ट पावरपॉइंट और ओपनऑफिस प्रेजेंटेशन फाइलों को बनाने, मर्ज करने, निरीक्षण करने या परिवर्तित करने की क्षमता वाले अनुप्रयोगों को विकसित करने में मदद करता है।" >}}

{{% blocks/products/pf/feature-page-section h2="पायथन में FODP को TIFF में मर्ज करें" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) प्रेजेंटेशन फाइल बनाने और उसमें हेरफेर करने के लिए एक शक्तिशाली पायथन लाइब्रेरी है। इसके अलावा, यह कई FODP प्रस्तुतियों को संयोजित करने के लचीले तरीके प्रदान करता है। जब आप एक प्रस्तुति को दूसरे में मर्ज करते हैं, तो आप एक फ़ाइल प्राप्त करने के लिए उनकी स्लाइड्स को एक प्रस्तुति में प्रभावी रूप से संयोजित कर रहे हैं। Aspose.Slides आपको दो प्रस्तुतियों को अलग-अलग तरीकों से मर्ज करने की अनुमति देता है। आप गुणवत्ता या डेटा के नुकसान के बारे में चिंता किए बिना प्रस्तुतियों को उनके सभी आकारों, शैलियों, ग्रंथों, स्वरूपण, टिप्पणियों, एनिमेशन आदि के साथ मर्ज कर सकते हैं।

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python का उपयोग करके FODP फ़ाइलों को TIFF में मर्ज करें" %}}
PowerPoint प्रस्तुतियों को मर्ज करने के लिए, आपको स्लाइडों को एक प्रस्तुति से दूसरी प्रस्तुति में क्लोन करना होगा।

{{% blocks/products/pf/agp/code-block title="एकाधिक FODP को एकल TIFF फ़ाइल में मर्ज करने के लिए पायथन कोड" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.fodp") as pres1:
    with slides.Presentation("presentation2.fodp") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.tiff", slides.export.SaveFormat.TIFF)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API का उपयोग करके FODP को TIFF में कैसे मर्ज करें?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये दो FODP फाइलों को मर्ज करने और परिणाम को पायथन में TIFF के रूप में सहेजने के चरण हैं।" >}}

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
पायथन में स्रोत FODP फ़ाइलें खोलें।
```
pres1 = slides.Presentation('pres1.fodp')
pres2 = slides.Presentation('pres2.fodp')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods) पद्धति का उपयोग करके FODP फाइलों को मिलाएं।
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति सहेजें और परिणाम एकल TIFF फ़ाइल के रूप में प्राप्त करें।
```
pres1.save("presentation.tiff", slides.export.SaveFormat.TIFF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="पीडीएफ फाइलों को ऑनलाइन मर्ज करें" sectionDescription="[पायथन में पीडीएफ को कैसे मर्ज करें](https://products.aspose.com/slides/hi/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="FODP अन्य समर्थित प्रारूपों में निर्यात करें" subTitle="आप FODP को भी जोड़ सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। सभी समर्थित प्रारूप नीचे देखें" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-pptx/" name="FODP TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-ppt/" name="FODP TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-pdf/" name="FODP TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-html/" name="FODP TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-png/" name="FODP TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-bmp/" name="FODP TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-jpg/" name="FODP TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-gif/" name="FODP TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-odp/" name="FODP TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-otp/" name="FODP TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-pot/" name="FODP TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-potm/" name="FODP TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-potx/" name="FODP TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-pps/" name="FODP TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-ppsm/" name="FODP TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-ppsx/" name="FODP TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-pptm/" name="FODP TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-svg/" name="FODP TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp-to-xps/" name="FODP TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}