---
title: Java का उपयोग करके PPTX एनोटेशन निकालें
weight: 360
url: /hi/java/annotation/pptx/ 
description: जेएसपी/जेएसएफ एप्लीकेशन और डेस्कटॉप एप्लीकेशन के लिए जावा रनटाइम पर्यावरण पर पीपीटीएक्स प्रारूप एनोटेशन को हटाने के लिए जावा नमूना कोड।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="जावा में PPTX से टिप्पणियाँ और टिप्पणी लेखक निकालें" h2="सर्वर-साइड एपीआई का उपयोग करके दस्तावेज़ फ़ाइलों में टिप्पणियों और लेखकों में हेरफेर करने के लिए अपने स्वयं के जावा ऐप बनाएं।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से पीपीटीएक्स से टिप्पणियां हटाएं" %}}
PPTX फ़ाइल से एनोटेशन हटाने के लिए, हम [Aspose.Slides for Java](https://products.aspose.com/slides/hi/java/) एपीआई का इस्तेमाल करेंगे, जो सुविधाओं से भरपूर, शक्तिशाली और इस्तेमाल में आसान है जावा प्लेटफॉर्म के लिए दस्तावेज़ हेरफेर एपीआई।
{{% blocks/products/pf/agp/code-block title="पीपीटीएक्स - जावा से एनोटेशन हटाएं" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.pptx");
try {
    // Deletes all comments from the presentation
    for (ICommentAuthor author : presentation.getCommentAuthors())
    {
        author.getComments().clear();
    }

    // Deletes all authors
    presentation.getCommentAuthors().clear();

    presentation.save("example_out.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="जावा के माध्यम से पीपीटीएक्स से टिप्पणियाँ कैसे निकालें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for Java** इंस्टॉल करें। देखें [**इंस्टॉलेशन**](https://docs.aspose.com/slides/java/installation/)।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX को प्रेजेंटेशन क्लास के उदाहरण के साथ लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
लोड किए गए PPTX के सभी लेखकों पर पुनरावृति करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
किसी लेखक की सभी टिप्पणियाँ हटाएं
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अंत में सभी लेखकों को हटा दें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित एनोटेशन प्रारूप" subTitle="जावा का उपयोग करके, कोई अन्य प्रारूपों को आसानी से एनोटेट कर सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/java/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}