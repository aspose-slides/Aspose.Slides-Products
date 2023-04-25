---
title: Java का उपयोग करके ODP फ़ाइलें मेटाडेटा देखें या संपादित करें
url: /hi/java/metadata/odp/
keywords: ODP मेटाडेटा संपादित करें, ODP मेटाडेटा देखें, ODP गुण संपादित करें, ODP गुण देखें
description: संपादित करने या ODP प्रारूप मेटाडेटा देखने के लिए Java स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java का इस्तेमाल करके ODP प्रॉपर्टी में बदलाव करें" h2="सर्वर-साइड API का उपयोग करके प्रस्तुतिकरण फ़ाइलों में अंतर्निहित और कस्टम गुणों को संशोधित करने के लिए अपने स्वयं के Java ऐप्स बनाएं." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="ODP प्रॉपर्टी को Java के ज़रिए बदलें" %}}
{Product_name} का इस्तेमाल करके, डेवलपर बिल्ट-इन प्रॉपर्टी के साथ-साथ कस्टम प्रॉपर्टी के मानों को एक्सेस और संशोधित कर सकते हैं. प्रस्तुतिकरण फ़ाइल के दस्तावेज़ गुणों तक पहुँचने के लिए डेवलपर प्रस्तुति वस्तु द्वारा प्रदर्शित [DocumentProperties](https://reference.aspose.com/slides/java/com.aspose.slides/documentproperties/) संपत्ति का उपयोग कर सकते हैं।
{{% blocks/products/pf/agp/code-block title="ODP अंतर्निहित गुणों को संशोधित करें - Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation("Presentation.odp");
try {
    // Create a reference to IDocumentProperties object associated with Presentation
    IDocumentProperties dp = pres.getDocumentProperties();
    
    // Set the built-in properties
    dp.setAuthor("Aspose.Slides for Java");
    dp.setTitle("Modifying Presentation Properties");
    dp.setSubject("Aspose Subject");
    dp.setComments("Aspose Description");
    dp.setManager("Aspose Manager");
    
    // Save your presentation to a file
    pres.save("DocProps.odp", SaveFormat.Odp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="ODP - Java में कस्टम गुण जोड़ें" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    // Getting Document Properties
    IDocumentProperties dProps = pres.getDocumentProperties();
    
    // Adding Custom properties
    dProps.set_Item("New Custom", 12);
    dProps.set_Item("My Name", "Aspose Metadata Editor");
    dProps.set_Item("Custom", 124);
    
    // Getting property name at particular index
    String getPropertyName = dProps.getCustomPropertyName(2);
    
    // Removing selected property
    dProps.removeCustomProperty(getPropertyName);
    
    // Saving presentation
    pres.save("CustomDemo.odp", SaveFormat.Odp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java के द्वारा ODP का मेटाडेटा कैसे निकालें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये ODP फ़ाइलों से मेटाडेटा निकालने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP फ़ाइल के पाथ के साथ प्रेजेंटेशन क्लास को इंस्टेंट करें
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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}