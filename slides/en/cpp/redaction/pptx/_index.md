---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Redact PPTX Presentations using C++
url: /cpp/redaction/pptx/
keywords: Redact PPTX, find and replace text in PPTX, update PPTX Presentation
description: Redact PPTX presentations in C++. Use Aspose.Slides for C++ to find and replace sensitive text in presentation files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Redact PPTX using C++" h2="Use Aspose.Slides for C++ to find and replace sensitive text in presentation files without Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Redact a PPTX Presentation via C++" variant="code" %}}

Aspose.Slides for C++ lets you redact PPTX presentations by replacing sensitive text in slides. Use `SlideUtil::FindAndReplaceText` with a `Presentation` object to search the presentation and replace matching text before saving the updated file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Redact a PPTX Presentation using C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Redact PPTX via C++" intro="Follow these steps to redact a PPTX presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPTX file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use the [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) method to find and replace sensitive text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the redacted file with `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Redaction Formats" subTitle="Using C++, you can also redact the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
