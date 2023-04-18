---
title: सी ++ का उपयोग कर पीपीटी एनोटेशन निकालें
weight: 4380
url: /hi/cpp/annotation/ppt/ 
description: पीपीटी से एनोटेशन हटाने के लिए सी ++ स्रोत कोड
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++ में PPT से टिप्पणियाँ और टिप्पणी लेखक निकालें" h2="सर्वर-साइड APIs का उपयोग करके दस्तावेज़ फ़ाइलों में टिप्पणियों और लेखकों में हेरफेर करने के लिए अपने स्वयं के C++ ऐप्स बनाएं।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="पीपीटी से सी ++ के माध्यम से टिप्पणियां हटाएं" %}}
PPT फ़ाइल से एनोटेशन हटाने के लिए, हम [Aspose.Slides for C++](https://products.aspose.com/slides/hi/cpp/) API का उपयोग करेंगे, जो सुविधाओं से भरपूर, शक्तिशाली और उपयोग में आसान है C++ प्लेटफॉर्म के लिए दस्तावेज़ हेरफेर एपीआई।
{{% blocks/products/pf/agp/code-block title="पीपीटी - सी ++ से एनोटेशन हटाएं" offSpacer="true" %}}

```cpp

using namespace Aspose::Slides;
using namespace Aspose::Slides::Export;
using namespace System::Drawing;

auto presentation = System::MakeObject<Presentation>(u"example.ppt");

// Deletes all comments from the presentation
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}
        
// Deletes all authors
presentation->get_CommentAuthors()->Clear();
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="पीपीटी से सी ++ के माध्यम से टिप्पणियाँ कैसे निकालें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
C++** के लिए **Aspose.Slides इंस्टॉल करें। देखें [**इंस्टॉलेशन**](https://docs.aspose.com/slides/cpp/installation/)।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रेजेंटेशन क्लास के उदाहरण के साथ पीपीटी लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
लोड किए गए पीपीटी के सभी लेखकों पर पुनरावृति करें
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

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित एनोटेशन प्रारूप" subTitle="सी ++ का उपयोग करके, कोई अन्य प्रारूपों को आसानी से एनोटेट कर सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/cpp/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}