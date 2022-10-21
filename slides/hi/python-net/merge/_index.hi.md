---
title: Python का उपयोग करके PDF, PPT, PPTX और कई अन्य फ़ाइल स्वरूपों को मर्ज करें
url: /hi/python-net/merge/
keywords: मर्ज, जॉइन, पॉवरपॉइंट, प्रेजेंटेशन, पायथन, एस्पोज
description: पायथन पीपीटी, पीपीटीएक्स, ओडीपी, पीडीएफ, पीएनजी, जेपीजी और कई अन्य फाइलों को मर्ज करें।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="पायथन में पावरपॉइंट, पीडीएफ, पीपीटी या अन्य दस्तावेजों को एक साथ मिलाएं" h2="पीपीटी, पीपीटीएक्स, पीडीएफ, पीएनजी, जेपीईजी और अन्य प्रारूपों को मर्ज करने के लिए हाई-स्पीड पायथन लाइब्रेरी।" >}}

{{% blocks/products/pf/feature-page-section h2="PPT, PPTX, PDF को Python का उपयोग करके मर्ज करें" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/hi/python-net/) प्रेजेंटेशन फाइल बनाने और उसमें हेरफेर करने के लिए एक शक्तिशाली पायथन लाइब्रेरी है। इसके अलावा, यह कई पीपीटी / पीपीटीएक्स प्रस्तुतियों को संयोजित करने के लचीले तरीके प्रदान करता है। जब आप एक प्रस्तुति को दूसरे में मर्ज करते हैं, तो आप एक फ़ाइल प्राप्त करने के लिए उनकी स्लाइड्स को एक प्रस्तुति में प्रभावी रूप से संयोजित कर रहे हैं। Aspose.Slides आपको दो प्रस्तुतियों को अलग-अलग तरीकों से मर्ज करने की अनुमति देता है। आप गुणवत्ता या डेटा के नुकसान के बारे में चिंता किए बिना प्रस्तुतियों को उनके सभी आकारों, शैलियों, ग्रंथों, स्वरूपण, टिप्पणियों, एनिमेशन आदि के साथ मर्ज कर सकते हैं।

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Python में PowerPoint प्रस्तुतियों को मर्ज करें" %}}
PowerPoint प्रस्तुतियों को मर्ज करने के लिए, आपको स्लाइडों को एक प्रस्तुति से दूसरी प्रस्तुति में क्लोन करना होगा।

{{% blocks/products/pf/agp/code-block title="पायथन का उपयोग करके पीपीटीएक्स फाइलों को मर्ज करें" offSpacer="true" %}}

```python

import aspose.slides as slides

# open first presentation
with slides.Presentation("presentation1.pptx") as pres1:
    # open second presentation
    with slides.Presentation("presentation2.pptx") as pres2:
        # loop through slides
        for slide in pres2.slides:
            # clone slide
            pres1.slides.add_clone(slide)
        # save merged presentation
        pres1.save("combined.pptx", slides.export.SaveFormat.PPTX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="पायथन का उपयोग करके स्लाइड मास्टर के साथ प्रस्तुतियों को मिलाएं" %}}
यह पायथन कोड दर्शाता है कि कैसे कई प्रस्तुतियों को एक में मिलाएं और स्लाइड मास्टर प्रस्तुति टेम्पलेट से शैलियों को लागू करें। तो, परिणाम प्रस्तुति एक ही स्रोत स्वरूपण रखेगी और इसमें किसी अन्य प्रस्तुति की मास्टर स्लाइड से स्वरूपण होगा।

{{% blocks/products/pf/agp/code-block title="पायथन में एकाधिक पीपीटी को सिंगल में मर्ज करें" offSpacer="true" %}}

```python

import aspose.slides as slides

files = ['pres1.pptx', 'pres2.pptx', 'pres3.pptx']

with slides.Presentation('master.pptx') as master:
    masterSlide = master.masters[0]

    for file in files:
        with slides.Presentation(file) as source:
            for slide in source.slides:
                clone = master.slides.add_clone(slide)

                for shape in masterSlide.shapes:
                    clone.shapes.add_clone(shape)
    
    master.save("combined.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Python API का उपयोग करके प्रस्तुतियों को कैसे मर्ज करें?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये दो PPTX फ़ाइलों को मर्ज करने और परिणाम को Python में PDF के रूप में सहेजने के चरण हैं।" >}}

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
पायथन में स्रोत पीपीटीएक्स फाइलें खोलें।
```
pres1 = slides.Presentation('pres1.pptx')
pres2 = slides.Presentation('pres2.pptx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
**add_clone** विधि का उपयोग करके PPTX फाइलों को मिलाएं।
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति सहेजें और एकल पीडीएफ फाइल के रूप में परिणाम प्राप्त करें।
```
pres1.save("document.pdf", slides.export.SaveFormat.PDF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="मर्ज करने के लिए अन्य समर्थित प्रारूप" subTitle="आप अन्य फ़ाइल स्वरूपों को भी जोड़ सकते हैं। नीचे अन्य समर्थित प्रारूप देखें।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/ppt/" name="PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptx/" name="PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pdf/" name="PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/odp/" name="ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/otp/" name="OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pot/" name="POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/potm/" name="POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/potx/" name="POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pps/" name="PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/ppsm/" name="PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/ppsx/" name="PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/pptm/" name="PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/merge/fodp/" name="FODP" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}