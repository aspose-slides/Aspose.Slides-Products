---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Redact PPTX Presentation Files using .NET
url: /net/redaction/pptx/
keywords: Redact PPTX, Find and Replace Text in PPTX, Update PPTX Presentation
description: C# source code to find and replace text in PPTX presentations.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Redact PPTX Files using C#" h2="Build .NET apps that find and replace text in presentations with server-side APIs." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Redact a PPTX Presentation using C#" variant="code" %}}

With [Aspose.Slides for .NET](/slides/net/), you can find and replace text in a PPTX presentation. Use `Presentation.ReplaceText` with `TextSearchOptions` to control the search, then save the modified presentation.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Redact a PPTX Presentation using C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Redact a PPTX Presentation using C#" intro="Follow these steps to replace text in a PPTX presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPTX file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) with `TextSearchOptions` to replace the required text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the modified presentation with `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Redaction Formats" subTitle="Using C#, you can also redact the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
