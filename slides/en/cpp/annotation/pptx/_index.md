---
title: Remove PPTX Annotations Using C++
weight: 4380
url: /cpp/annotation/pptx/
description: C++ source code to remove annotations from PPTX presentations.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Remove Comments and Comment Authors from PPTX in C++" h2="Build C++ apps to manipulate comments and authors in presentation files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides" subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Remove Comments from PPTX via C++" %}}
To remove annotations from a PPTX file, use the [Aspose.Slides for C++](/slides/cpp/) API, a feature-rich and easy-to-use presentation manipulation API for C++.
{{% blocks/products/pf/agp/code-block title="Delete Annotations from PPTX - C++" offSpacer="true" %}}

```cpp
auto presentation = MakeObject<Presentation>(u"example.pptx");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="How to Remove Comments from PPTX via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for C++**. See [**Installation**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load a PPTX file with an instance of the Presentation class.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterate over all authors in the loaded PPTX file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Remove all comments from each author.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Remove all authors at the end.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Annotation Formats" subTitle="Using C++, you can also remove annotations from other formats, including:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/cpp/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}
