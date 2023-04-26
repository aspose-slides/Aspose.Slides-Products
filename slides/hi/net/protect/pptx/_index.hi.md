---
title: .NET का उपयोग करके PPTX प्रस्तुतिकरण फ़ाइलों की सुरक्षा करें
url: /hi/net/protect/pptx/
keywords: राइट प्रोटेक्शन PPTX, PPTX को एन्क्रिप्ट करना, PPTX प्रेजेंटेशन को लॉक करना, PPTX को प्रोटेक्ट करना
description: PPTX प्रस्तुति की सुरक्षा के लिए C# स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C# का इस्तेमाल करके PPTX को लॉक या पासवर्ड प्रोटेक्ट करें" h2="सर्वर-साइड API का उपयोग करके प्रस्तुतिकरण फ़ाइलों की सुरक्षा के लिए अपना स्वयं का .NET ऐप्लिकेशन बनाएं." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="C# के माध्यम से एक PPTX प्रस्तुति की सुरक्षा करना" %}}
{Product_name} का उपयोग करके, आप पासवर्ड सेट करके अपनी PPTX प्रस्तुति को खोलने या बदलने से बचा सकते हैं। फिर, लॉक की गई प्रस्तुति को खोलने या संशोधित करने के लिए, उपयोगकर्ता को पासवर्ड प्रदान करना होगा।
{{% blocks/products/pf/agp/code-block title="C# का उपयोग करके एक PPTX प्रस्तुति को एन्क्रिप्ट करना" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="{Product_lang} का उपयोग करके एक PPTX प्रस्तुति के लिए लेखन सुरक्षा सेट करना" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C# द्वारा PPTX को पासवर्ड कैसे सुरक्षित करें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये PPTX फ़ाइलों को सुरक्षित रखने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति के उदाहरण के साथ PPTX लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
सुरक्षा प्रबंधक वर्ग का उपयोग करके प्रस्तुति को सुरक्षित रखें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम PPTX प्रारूप में सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित सुरक्षा प्रारूप" subTitle="C# का उपयोग करके, आप निम्न स्वरूपों की सुरक्षा भी कर सकते हैं:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}