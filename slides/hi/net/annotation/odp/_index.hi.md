---
title: .NET का उपयोग करके ODP एनोटेशन निकालें
weight: 4380
url: /hi/net/annotation/odp/ 
description: .NET फ्रेमवर्क, .NET Core, Windows Azure, Mono या Xamarin प्लेटफॉर्म पर ODP प्रारूप एनोटेशन को हटाने के लिए C# स्रोत कोड।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="सी # में ओडीपी से टिप्पणियां और टिप्पणी लेखक हटाएं" h2="सर्वर-साइड एपीआई का उपयोग करके दस्तावेज़ फ़ाइलों में टिप्पणियों और लेखकों में हेरफेर करने के लिए अपने स्वयं के .NET ऐप्स बनाएं।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="ओडीपी से सी # के माध्यम से टिप्पणियां हटाएं" %}}
ODP फ़ाइल से एनोटेशन हटाने के लिए, हम [Aspose.Slides for .NET](https://products.aspose.com/slides/hi/net) API का उपयोग करेंगे, जो सुविधाओं से भरपूर, शक्तिशाली और उपयोग में आसान है सी # प्लेटफॉर्म के लिए दस्तावेज़ मैनिपुलेशन एपीआई।
{{% blocks/products/pf/agp/code-block title="ओडीपी से एनोटेशन हटाएं - सी #" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.odp"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="ओडीपी से सी # के माध्यम से टिप्पणियां कैसे निकालें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET** इंस्टॉल करें। [**इंस्टॉलेशन**](https://docs.aspose.com/slides/net/installation/) देखें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रेजेंटेशन क्लास के उदाहरण के साथ ओडीपी लोड करें
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
लोड किए गए ODP के सभी लेखकों पर पुनरावृति करें
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

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित एनोटेशन प्रारूप" subTitle="सी # का उपयोग करके, कोई अन्य प्रारूपों को आसानी से एनोटेट कर सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}