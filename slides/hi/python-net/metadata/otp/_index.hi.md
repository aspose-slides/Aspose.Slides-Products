---
title: Python का उपयोग करके OTP फ़ाइलें मेटाडेटा देखें या संपादित करें
url: /hi/python-net/metadata/otp/
keywords: OTP मेटाडेटा संपादित करें, OTP मेटाडेटा देखें, OTP गुण संपादित करें, OTP गुण देखें
description: संपादित करने या OTP प्रारूप मेटाडेटा देखने के लिए Python स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python का इस्तेमाल करके OTP प्रॉपर्टी में बदलाव करें" h2="सर्वर-साइड API का उपयोग करके प्रस्तुतिकरण फ़ाइलों में अंतर्निहित और कस्टम गुणों को संशोधित करने के लिए अपने स्वयं के Python ऐप्स बनाएं." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="OTP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="OTP प्रॉपर्टी को Python के ज़रिए बदलें" %}}
{Product_name} का इस्तेमाल करके, डेवलपर बिल्ट-इन प्रॉपर्टी के साथ-साथ कस्टम प्रॉपर्टी के मानों को एक्सेस और संशोधित कर सकते हैं. प्रस्तुतिकरण फ़ाइल के दस्तावेज़ गुणों तक पहुँचने के लिए डेवलपर प्रस्तुति वस्तु द्वारा प्रदर्शित [DocumentProperties](https://reference.aspose.com/slides/python-net/aspose.slides/documentproperties/) संपत्ति का उपयोग कर सकते हैं।
{{% blocks/products/pf/agp/code-block title="OTP अंतर्निहित गुणों को संशोधित करें - Python" offSpacer="true" %}}

```py

import aspose.slides as slides

# Instantiate the Presentation class that represents the Presentation
with slides.Presentation(path + "ModifyBuiltinProperties.otp") as presentation:
    # Create a reference to object associated with Presentation
    documentProperties = presentation.document_properties

    # Set the builtin properties
    documentProperties.author = "Aspose.Slides for Python"
    documentProperties.title = "Modifying Presentation Properties"
    documentProperties.subject = "Aspose Subject"
    documentProperties.comments = "Aspose Description"
    documentProperties.manager = "Aspose Manager"

    # save your presentation to a file
    presentation.save("DocumentProperties_out.otp", slides.export.SaveFormat.OTP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="OTP - Python में कस्टम गुण जोड़ें" offSpacer="true" %}}

```py

import aspose.slides as slides

# Instantiate the Presentation class
with slides.Presentation() as presentation:
    # Getting Document Properties
    documentProperties = presentation.document_properties

    # Adding Custom properties
    documentProperties.set_custom_property_value("New Custom", 12)
    documentProperties.set_custom_property_value("My Nam", "Aspose Metadata Editor")
    documentProperties.set_custom_property_value("Custom", 124)

    # Getting property name at particular index
    getPropertyName = documentProperties.get_custom_property_name(2)

    # Removing selected property
    documentProperties.remove_custom_property(getPropertyName)

    # Saving presentation
    presentation.save("CustomDocumentProperties_out.otp", slides.export.SaveFormat.OTP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python के द्वारा OTP का मेटाडेटा कैसे निकालें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये OTP फ़ाइलों से मेटाडेटा निकालने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
OTP फ़ाइल के पाथ के साथ प्रेजेंटेशन क्लास को इंस्टेंट करें
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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}