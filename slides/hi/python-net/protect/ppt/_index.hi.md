---
title: Python का उपयोग करके PPT प्रस्तुतिकरण फ़ाइलों की सुरक्षा करें
url: /hi/python-net/protect/ppt/
keywords: राइट प्रोटेक्शन PPT, PPT को एन्क्रिप्ट करना, PPT प्रेजेंटेशन को लॉक करना, PPT को प्रोटेक्ट करना
description: PPT प्रस्तुति की सुरक्षा के लिए Python स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python का इस्तेमाल करके PPT को लॉक या पासवर्ड प्रोटेक्ट करें" h2="सर्वर-साइड API का उपयोग करके प्रस्तुतिकरण फ़ाइलों की सुरक्षा के लिए अपना स्वयं का Python ऐप्लिकेशन बनाएं." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python के माध्यम से एक PPT प्रस्तुति की सुरक्षा करना" %}}
{Product_name} का उपयोग करके, आप पासवर्ड सेट करके अपनी PPT प्रस्तुति को खोलने या बदलने से बचा सकते हैं। फिर, लॉक की गई प्रस्तुति को खोलने या संशोधित करने के लिए, उपयोगकर्ता को पासवर्ड प्रदान करना होगा।
{{% blocks/products/pf/agp/code-block title="Python का उपयोग करके एक PPT प्रस्तुति को एन्क्रिप्ट करना" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="{Product_lang} का उपयोग करके एक PPT प्रस्तुति के लिए लेखन सुरक्षा सेट करना" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python द्वारा PPT को पासवर्ड कैसे सुरक्षित करें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये PPT फ़ाइलों को सुरक्षित रखने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति के उदाहरण के साथ PPT लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
सुरक्षा प्रबंधक वर्ग का उपयोग करके प्रस्तुति को सुरक्षित रखें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम PPT प्रारूप में सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित सुरक्षा प्रारूप" subTitle="Python का उपयोग करके, आप निम्न स्वरूपों की सुरक्षा भी कर सकते हैं:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}