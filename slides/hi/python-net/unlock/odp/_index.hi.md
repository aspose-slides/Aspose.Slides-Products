---
title: Python का उपयोग करके ODP प्रस्तुति फ़ाइलें अनलॉक करें
url: /hi/python-net/unlock/odp/
keywords: राइट प्रोटेक्शन हटाएं ODP, ODP को डिक्रिप्ट करना, ODP प्रेजेंटेशन को अनलॉक करना, ODP को अनप्रोटेक्ट करना
description: ODP प्रस्तुति से सुरक्षा हटाने के लिए Python स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python का इस्तेमाल करके ODP को अनलॉक करें" h2="PowerPoint से पासवर्ड निकालने और सर्वर-साइड API का उपयोग करके प्रस्तुतियों की फ़ाइलों को डिक्रिप्ट करने के लिए अपना Python ऐप्लिकेशन बनाएं." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python के माध्यम से ODP प्रस्तुतिकरण से एन्क्रिप्शन को निकाला जा रहा है" %}}
{Product_name} का उपयोग करके, आप ODP प्रस्तुति पर एन्क्रिप्शन या पासवर्ड सुरक्षा को निकाल सकते हैं। इस तरह, उपयोगकर्ता बिना किसी प्रतिबंध के ODP प्रस्तुति को एक्सेस या संशोधित कर सकते हैं।
{{% blocks/products/pf/agp/code-block title="Python का उपयोग करके ODP से पासवर्ड सुरक्षा अक्षम करना" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.odp", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python का उपयोग करके ODP प्रस्तुतिकरण से लेखन सुरक्षा हटाना" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.odp") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.odp", slides.export.SaveFormat.ODP)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="ODP से Python के जरिए पासवर्ड कैसे हटाएं" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये ODP फ़ाइलों से सुरक्षा हटाने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति के उदाहरण के साथ ODP लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
सुरक्षा प्रबंधक वर्ग का उपयोग करके लेखन सुरक्षा हटाएं
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम ODP प्रारूप में सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित प्रारूप" subTitle="Python का इस्तेमाल करके, आप नीचे दिए गए फ़ॉर्मैट से भी सुरक्षा हटा सकते हैं:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}