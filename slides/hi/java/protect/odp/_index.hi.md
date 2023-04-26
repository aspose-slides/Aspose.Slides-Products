---
title: Java का उपयोग करके ODP प्रस्तुतिकरण फ़ाइलों की सुरक्षा करें
url: /hi/java/protect/odp/
keywords: राइट प्रोटेक्शन ODP, ODP को एन्क्रिप्ट करना, ODP प्रेजेंटेशन को लॉक करना, ODP को प्रोटेक्ट करना
description: ODP प्रस्तुति की सुरक्षा के लिए Java स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java का इस्तेमाल करके ODP को लॉक या पासवर्ड प्रोटेक्ट करें" h2="सर्वर-साइड API का उपयोग करके प्रस्तुतिकरण फ़ाइलों की सुरक्षा के लिए अपना स्वयं का Java ऐप्लिकेशन बनाएं." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Java के माध्यम से एक ODP प्रस्तुति की सुरक्षा करना" %}}
{Product_name} का उपयोग करके, आप पासवर्ड सेट करके अपनी ODP प्रस्तुति को खोलने या बदलने से बचा सकते हैं। फिर, लॉक की गई प्रस्तुति को खोलने या संशोधित करने के लिए, उपयोगकर्ता को पासवर्ड प्रदान करना होगा।
{{% blocks/products/pf/agp/code-block title="Java का उपयोग करके एक ODP प्रस्तुति को एन्क्रिप्ट करना" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.odp");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-pres.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="{Product_lang} का उपयोग करके एक ODP प्रस्तुति के लिए लेखन सुरक्षा सेट करना" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.odp");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-pres.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java द्वारा ODP को पासवर्ड कैसे सुरक्षित करें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये ODP फ़ाइलों को सुरक्षित रखने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति के उदाहरण के साथ ODP लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
सुरक्षा प्रबंधक वर्ग का उपयोग करके प्रस्तुति को सुरक्षित रखें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम ODP प्रारूप में सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित सुरक्षा प्रारूप" subTitle="Java का उपयोग करके, आप निम्न स्वरूपों की सुरक्षा भी कर सकते हैं:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}