---
title: C++ का उपयोग करके POT फ़ाइलें मेटाडेटा देखें या संपादित करें
url: /hi/cpp/metadata/pot/
keywords: POT मेटाडेटा संपादित करें, POT मेटाडेटा देखें, POT गुण संपादित करें, POT गुण देखें
description: संपादित करने या POT प्रारूप मेटाडेटा देखने के लिए C++ स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++ का इस्तेमाल करके POT प्रॉपर्टी में बदलाव करें" h2="सर्वर-साइड API का उपयोग करके प्रस्तुतिकरण फ़ाइलों में अंतर्निहित और कस्टम गुणों को संशोधित करने के लिए अपने स्वयं के C++ ऐप्स बनाएं." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="POT प्रॉपर्टी को C++ के ज़रिए बदलें" %}}
{Product_name} का इस्तेमाल करके, डेवलपर बिल्ट-इन प्रॉपर्टी के साथ-साथ कस्टम प्रॉपर्टी के मानों को एक्सेस और संशोधित कर सकते हैं. प्रस्तुतिकरण फ़ाइल के दस्तावेज़ गुणों तक पहुँचने के लिए डेवलपर प्रस्तुति वस्तु द्वारा प्रदर्शित [DocumentProperties](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) संपत्ति का उपयोग कर सकते हैं।
{{% blocks/products/pf/agp/code-block title="POT अंतर्निहित गुणों को संशोधित करें - C++" offSpacer="true" %}}

```cpp

// Instantiate the Presentation class that represents the Presentation
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"presentation.pot");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();

// Set the builtin properties
documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

// Save your presentation to a file
presentation->Save(u"DocumentProperties_out.pot", SaveFormat::Pot);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="POT - C++ में कस्टम गुण जोड़ें" offSpacer="true" %}}

```cpp

// Instantiate the Presentation class
auto presentation = System::MakeObject<Presentation>();

// Getting Document Properties
auto documentProperties = presentation->get_DocumentProperties();

// Adding Custom properties
documentProperties->idx_set(u"New Custom", ObjectExt::Box<int32_t>(12));
documentProperties->idx_set(u"My Name", ObjectExt::Box<String>(u"Aspose Metadata Editor"));
documentProperties->idx_set(u"Custom", ObjectExt::Box<int32_t>(124));

// Getting property name at particular index
String getPropertyName = documentProperties->GetCustomPropertyName(2);

// Removing selected property
documentProperties->RemoveCustomProperty(getPropertyName);

// Saving presentation
presentation->Save(u"CustomDocumentProperties_out.pot", SaveFormat::Pot);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++ के द्वारा POT का मेटाडेटा कैसे निकालें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये POT फ़ाइलों से मेटाडेटा निकालने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
POT फ़ाइल के पाथ के साथ प्रेजेंटेशन क्लास को इंस्टेंट करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रेजेंटेशन से जुड़े डॉक्यूमेंटप्रॉपर्टीज ऑब्जेक्ट प्राप्त करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
DocumentProperties ऑब्जेक्ट में आइटम्स पर लूप करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
कस्टम गुणों तक पहुंचें और संशोधित करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित मेटाडेटा प्रारूप" subTitle="{Product_lang} का उपयोग करके, आप सहित कई अन्य प्रारूपों के मेटाडेटा में हेरफेर भी कर सकते हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}