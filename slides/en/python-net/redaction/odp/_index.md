---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Redact Text in ODP Presentations with Python
url: /python-net/redaction/odp/
keywords: redact ODP, find and replace text in ODP, update ODP presentation
description: Find and replace sensitive text in ODP presentations with Python.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Redact Text in ODP Presentations with Python" h2="Build Python applications that find and replace sensitive text in presentations with Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Redact Text in an ODP Presentation with Python" variant="code" %}}

With [Aspose.Slides for Python via .NET](/slides/python-net/), you can replace sensitive text throughout an ODP presentation. Use `Presentation.replace_text` with `TextSearchOptions` to control the search, then save the modified presentation.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Redact Text in an ODP Presentation - Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.odp") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Redact Text in an ODP Presentation with Python" intro="Follow these steps to replace sensitive text in an ODP presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the ODP file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) with `TextSearchOptions` to replace the required text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the modified presentation with `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Redaction Formats" subTitle="Use Python to redact text in other supported presentation formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
