---
title: C++ का उपयोग करके PPTX प्रस्तुति फ़ाइलें अनलॉक करें
url: /hi/cpp/unlock/pptx/
keywords: राइट प्रोटेक्शन हटाएं PPTX, PPTX को डिक्रिप्ट करना, PPTX प्रेजेंटेशन को अनलॉक करना, PPTX को अनप्रोटेक्ट करना
description: PPTX प्रस्तुति से सुरक्षा हटाने के लिए C++ स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++ का इस्तेमाल करके PPTX को अनलॉक करें" h2="PowerPoint से पासवर्ड निकालने और सर्वर-साइड API का उपयोग करके प्रस्तुतियों की फ़ाइलों को डिक्रिप्ट करने के लिए अपना C++ ऐप्लिकेशन बनाएं." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="C++ के माध्यम से PPTX प्रस्तुतिकरण से एन्क्रिप्शन को निकाला जा रहा है" %}}
{Product_name} का उपयोग करके, आप PPTX प्रस्तुति पर एन्क्रिप्शन या पासवर्ड सुरक्षा को निकाल सकते हैं। इस तरह, उपयोगकर्ता बिना किसी प्रतिबंध के PPTX प्रस्तुति को एक्सेस या संशोधित कर सकते हैं।
{{% blocks/products/pf/agp/code-block title="C++ का उपयोग करके PPTX से पासवर्ड सुरक्षा अक्षम करना" offSpacer="true" %}}

```cpp

auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"123123");
    
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"encryption-removed.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ का उपयोग करके PPTX प्रस्तुतिकरण से लेखन सुरक्षा हटाना" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="PPTX से C++ के जरिए पासवर्ड कैसे हटाएं" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये PPTX फ़ाइलों से सुरक्षा हटाने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति के उदाहरण के साथ PPTX लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
सुरक्षा प्रबंधक वर्ग का उपयोग करके लेखन सुरक्षा हटाएं
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम PPTX प्रारूप में सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित प्रारूप" subTitle="C++ का इस्तेमाल करके, आप नीचे दिए गए फ़ॉर्मैट से भी सुरक्षा हटा सकते हैं:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/unlock/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}