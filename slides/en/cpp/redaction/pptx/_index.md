---
lastmod: 2026-07-09
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Redact PPTX Presentations using C++
url: /cpp/redaction/pptx/
keywords: Redact PPTX, find and replace text in PPTX, update PPTX Presentation
description: Redact PPTX presentations in C++. Use Aspose.Slides for C++ to find and replace sensitive text in presentation files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redact PPTX using C++" h2="Use Aspose.Slides for C++ to find and replace sensitive text in presentation files without Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Redact PPTX Presentation via C++" %}}
Aspose.Slides for C++ lets you redact PPTX presentations by replacing sensitive text in slides. Use `SlideUtil::FindAndReplaceText` with a `Presentation` object to search the presentation and replace matching text before saving the updated file.
{{% blocks/products/pf/agp/code-block title="Redact PPTX Presentation using C++" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Redact PPTX via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to redact PPTX files." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PPTX file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Use the [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) method to find and replace sensitive text.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the redacted file with `SaveFormat::Pptx`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Redaction Live Demos" sectionDescription="Search and replace text in PPTX documents right now." >}}
{{< /blocks/products/pf/agp/demobox >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Redact Formats" subTitle="You can also redact the following formats with C++." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
