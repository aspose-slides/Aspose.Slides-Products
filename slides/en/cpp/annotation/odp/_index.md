---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Remove ODP Annotations Using C++
weight: 4380
url: /cpp/annotation/odp/
description: C++ source code to remove annotations from ODP presentations.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Remove Comments and Comment Authors from ODP in C++" h2="Build C++ apps to manipulate comments and authors in presentation files using server-side APIs." related="PPTX,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Remove Comments from ODP via C++" variant="code" %}}

Use [Aspose.Slides for C++](/slides/cpp/) to remove comments and comment authors from ODP presentations. The example below clears the comments of each author from `get_CommentAuthors` and then clears the comment author collection.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Delete Annotations from ODP - C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.odp");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Remove Comments from ODP via C++" intro="Follow these steps to remove comments and comment authors from an ODP presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install Aspose.Slides for C++. See [Installation](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the ODP file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through the comment authors from `get_CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Clear the comments of each author with `get_Comments()->Clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Clear the comment author collection.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the updated presentation with `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Annotation Formats" subTitle="Using C++, you can also remove annotations from other formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
