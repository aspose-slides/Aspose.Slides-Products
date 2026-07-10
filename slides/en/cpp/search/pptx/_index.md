---
title: Search Text in PPTX Presentations using C++
url: /cpp/search/pptx/
keywords: search words in PPTX, search and replace text in PPTX, search text PPTX Presentation
description: Search and replace text in PPTX presentations in C++. Use Aspose.Slides for C++ to find text in presentation files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Search Text in PPTX using C++" h2="Use Aspose.Slides for C++ to find and replace text in presentation files without Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Search and Replace Text in PPTX Presentation via C++" %}}
Aspose.Slides for C++ lets you search text in PPTX presentations and replace matching content. Use `SlideUtil::FindAndReplaceText` with a `Presentation` object to search slide text and save the updated presentation.
{{% blocks/products/pf/agp/code-block title="Search Text in PPTX Presentation using C++" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"Quarterly Report", u"Annual Report", nullptr);
presentation->Save(u"updated-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Search Text in PPTX via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to search text in PPTX files." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PPTX file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Use the [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) method to find and replace text.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the updated file with `SaveFormat::Pptx`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Search Live Demos" sectionDescription="Search and replace text in PPTX documents right now." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Search Formats" subTitle="You can also search text in the following formats with C++." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
