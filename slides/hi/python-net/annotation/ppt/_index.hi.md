---
title: पायथन का उपयोग करके पीपीटी एनोटेशन निकालें
weight: 4380
url: /hi/python-net/annotation/ppt/ 
description: पीपीटी प्रस्तुति टिप्पणियों को हटाने के लिए पायथन स्रोत कोड
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="पायथन में पीपीटी से टिप्पणियां और टिप्पणी लेखक हटाएं" h2="सर्वर-साइड एपीआई का उपयोग करके दस्तावेज़ फ़ाइलों में टिप्पणियों और लेखकों में हेरफेर करने के लिए अपनी खुद की पायथन स्क्रिप्ट बनाएं।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="पायथन के माध्यम से पीपीटी से टिप्पणियां हटाएं" %}}
PPT फ़ाइल से एनोटेशन हटाने के लिए, हम [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hi/python-net/) API का उपयोग करेंगे, जो सुविधाओं से भरपूर है, पायथन प्लेटफॉर्म के लिए दस्तावेज़ हेरफेर एपीआई का उपयोग करने के लिए शक्तिशाली और आसान।
{{% blocks/products/pf/agp/code-block title="पीपीटी - पायथन से एनोटेशन हटाएं" offSpacer="true" %}}

```python

import aspose.slides as slides

with slides.Presentation("example.ppt") as presentation:
    # Deletes all comments from the presentation
    for author in presentation.comment_authors:
        author.comments.clear()

    # Deletes all authors
    presentation.comment_authors.clear()

    presentation.save("example_out.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="पायथन के माध्यम से पीपीटी से टिप्पणियाँ कैसे निकालें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
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

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित एनोटेशन प्रारूप" subTitle="पायथन का उपयोग करके, कोई अन्य प्रारूपों को आसानी से एनोटेट कर सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/python-net/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}