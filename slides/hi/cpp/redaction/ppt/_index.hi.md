---
title: C++ का इस्तेमाल करके PPT प्रस्तुति फ़ाइलें संपादित करें
url: /hi/cpp/redaction/ppt/
keywords: PPT संपादित करें, PPT में टेक्स्ट ढूंढें और बदलें, PPT प्रस्तुति अपडेट करें
description: PPT प्रस्तुतिकरण में टेक्स्ट खोजने और बदलने के लिए C++ स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++ का उपयोग करके PPT संपादित करें" h2="सर्वर-साइड API का उपयोग करके प्रस्तुतिकरण फ़ाइलों में टेक्स्ट खोजने और बदलने के लिए अपना स्वयं का C++ ऐप्लिकेशन बनाएं. सामग्री, टिप्पणियों या PPT प्रस्तुतियों के मेटाडेटा में टेक्स्ट को खोजने और बदलने का तरीका जानें" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="C++ के माध्यम से PPT प्रस्तुतिकरण संपादित करें" %}}
सामग्री, टिप्पणियों, स्लाइड नोट्स या मेटाडेटा में मूल दस्तावेज़ खोज और टेक्स्ट को Aspose.Slides for C++ API के साथ कोड की कुछ पंक्तियों के साथ किया जा सकता है। PowerPoint और OpenOffice में टेक्स्ट ढूँढें और बदलें। रेगेक्सपी डेटा मिलान के माध्यम से प्रस्तुतिकरण में टेक्स्ट, टिप्पणियाँ, मेटाडेटा संपादित करें।
{{% blocks/products/pf/agp/code-block title="C++ का उपयोग करके PPT प्रस्तुतिकरण संपादित करें" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.ppt");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.ppt", SaveFormat::Ppt);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++ द्वारा PPT को कैसे संपादित करें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये PPT फ़ाइलों को संपादित करने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति के उदाहरण के साथ PPT लोड करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
टेक्स्ट को खोजने और बदलने के लिए [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) विधि का उपयोग करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम PPT प्रारूप में सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="ऑनलाइन PPT रिडक्शन लाइव डेमो" sectionDescription="PPT दस्तावेज़ों में अभी सामग्री, टिप्पणियों या मेटाडेटा में टेक्स्ट खोजें और बदलें।" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रिडक्ट प्रारूप" subTitle="{Product_lang} का उपयोग करके, आप निम्न स्वरूपों को संपादित भी कर सकते हैं:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}