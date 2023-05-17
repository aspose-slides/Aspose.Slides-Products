---
title: .NET का इस्तेमाल करके ODP प्रस्तुति फ़ाइलें संपादित करें
url: /hi/net/redaction/odp/
keywords: ODP संपादित करें, ODP में टेक्स्ट ढूंढें और बदलें, ODP प्रस्तुति अपडेट करें
description: ODP प्रस्तुतिकरण में टेक्स्ट खोजने और बदलने के लिए C# स्रोत कोड.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C# का उपयोग करके ODP संपादित करें" h2="सर्वर-साइड API का उपयोग करके प्रस्तुतिकरण फ़ाइलों में टेक्स्ट खोजने और बदलने के लिए अपना स्वयं का .NET ऐप्लिकेशन बनाएं. सामग्री, टिप्पणियों या ODP प्रस्तुतियों के मेटाडेटा में टेक्स्ट को खोजने और बदलने का तरीका जानें" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="C# के माध्यम से ODP प्रस्तुतिकरण संपादित करें" %}}
सामग्री, टिप्पणियों, स्लाइड नोट्स या मेटाडेटा में मूल दस्तावेज़ खोज और टेक्स्ट को Aspose.Slides for .NET API के साथ कोड की कुछ पंक्तियों के साथ किया जा सकता है। PowerPoint और OpenOffice में टेक्स्ट ढूँढें और बदलें। रेगेक्सपी डेटा मिलान के माध्यम से प्रस्तुतिकरण में टेक्स्ट, टिप्पणियाँ, मेटाडेटा संपादित करें।
{{% blocks/products/pf/agp/code-block title="C# का उपयोग करके ODP प्रस्तुतिकरण संपादित करें" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.odp"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C# द्वारा ODP को कैसे संपादित करें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये ODP फ़ाइलों को संपादित करने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रस्तुति के उदाहरण के साथ ODP लोड करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
टेक्स्ट को खोजने और बदलने के लिए [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) विधि का उपयोग करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम ODP प्रारूप में सहेजें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="ऑनलाइन ODP रिडक्शन लाइव डेमो" sectionDescription="ODP दस्तावेज़ों में अभी सामग्री, टिप्पणियों या मेटाडेटा में टेक्स्ट खोजें और बदलें।" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रिडक्ट प्रारूप" subTitle="{Product_lang} का उपयोग करके, आप निम्न स्वरूपों को संपादित भी कर सकते हैं:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}