---
title: Java का उपयोग करके ODP प्रस्तुतिकरण फ़ाइलों में टेक्स्ट खोजें
url: /hi/java/search/odp/
keywords: ODP में शब्द खोजें, ODP में टेक्स्ट खोजें और बदलें, टेक्स्ट खोजें ODP प्रस्तुति
description: ODP प्रस्तुतिकरण में पाठ खोजने के लिए Java स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="{Product_lang} का उपयोग करके टेक्स्ट ODP खोजें" h2="सर्वर-साइड API का उपयोग करके प्रस्तुतिकरण फ़ाइलों में टेक्स्ट खोजने और बदलने के लिए अपना Java ऐप्लिकेशन बनाएं. प्रस्तुति दस्तावेज़ों में एक निश्चित शब्द या वाक्यांश के सभी प्रवेशों को खोजने का तरीका जानें। सटीक डेटा मिलान और रेगुलर एक्सप्रेशन मिलान द्वारा पाठ खोजें।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="टेक्स्ट को खोजें और बदलें ODP प्रस्तुति Java के माध्यम से" %}}
सामग्री, टिप्पणियों, स्लाइड नोट्स या मेटाडेटा में मूल दस्तावेज़ खोज और टेक्स्ट को Aspose.Slides for Java API के साथ कोड की कुछ पंक्तियों के साथ किया जा सकता है। प्रेजेंटेशन में टेक्स्ट खोजने के लिए रेगुलर एक्सप्रेशन मैचिंग, मैच केस का उपयोग करें। शीर्षक, सामग्री, पाद लेख या शीर्षक में पाठ खोजें।
{{% blocks/products/pf/agp/code-block title="Java का उपयोग कर पाठ खोजें ODP प्रस्तुतिकरण" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java के द्वारा ODP में लेख कैसे खोजें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="टेक्स्ट ODP फ़ाइलों को खोजने के लिए ये चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति के उदाहरण के साथ ODP लोड करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
टेक्स्ट को खोजने और बदलने के लिए [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) विधि का उपयोग करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम ODP प्रारूप में सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="ऑनलाइन ODP लाइव डेमो खोजें" sectionDescription="ODP दस्तावेज़ों में अभी सामग्री, टिप्पणियों या मेटाडेटा में टेक्स्ट खोजें और बदलें।" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित खोज प्रारूप" subTitle="{Product_lang} का उपयोग करके, आप निम्न स्वरूपों में लेख भी खोज सकते हैं:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}