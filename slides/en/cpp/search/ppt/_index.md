---
title: Search Text in PPT Presentations using C++
url: /cpp/search/ppt/
keywords: search words in PPT, search and replace text in PPT, search text PPT Presentation
description: Search and replace text in PPT presentations in C++. Use Aspose.Slides for C++ to find text in presentation files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Search Text in PPT using C++" h2="Use Aspose.Slides for C++ to find and replace text in presentation files without Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Search and Replace Text in PPT Presentation via C++" %}}
Aspose.Slides for C++ lets you search text in PPT presentations and replace matching content. Use `SlideUtil::FindAndReplaceText` with a `Presentation` object to search slide text and save the updated presentation.
{{% blocks/products/pf/agp/code-block title="Search Text in PPT Presentation using C++" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

SlideUtil::FindAndReplaceText(presentation, true, u"Quarterly Report", u"Annual Report", nullptr);
presentation->Save(u"updated-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Search Text in PPT via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to search text in PPT files." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the PPT file with the `Presentation` class.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use the [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) method to find and replace text.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the updated file with `SaveFormat::Ppt`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Search Live Demos" sectionDescription="Search and replace text in PPT documents right now." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Search Formats" subTitle="You can also search text in the following formats with C++." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
