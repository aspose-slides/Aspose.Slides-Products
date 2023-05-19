---
title: Search Text in PPTX Presentation Files using C++
url: /cpp/search/pptx/
keywords: search words in PPTX, search and replace text in PPTX, search text PPTX Presentation
description: C++ source code to search text in PPTX Presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Search Text PPTX using C++" h2="Build your own C++ apps to search and replace text in presentation files using server-side APIs. Learn how to find all the entrances of a certain word or phrase in presentation documents. Search text by exact data matching and regular expression matching." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Search and Replace Text PPTX Presentation via C++" %}}
A basic document search and replace text in contents, comments, slide notes or metadata with Aspose.Slides for C++ APIs can be done with just few lines of code. Use regular expression matching, match case to search text in presentation. Search text in titles, content, footer or header.
{{% blocks/products/pf/agp/code-block title="Search text PPTX Presentation using C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.pptx", SaveFormat::Pptx);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Search Text in PPTX via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to search text PPTX files." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load PPTX with an instance of Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) method to find and replace text.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result in PPTX format
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Search Live Demos" sectionDescription="Search and replace text in contents, comments or metadata in PPTX documents right now." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Search Formats" subTitle="Using C++, You can also search text in the following formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}