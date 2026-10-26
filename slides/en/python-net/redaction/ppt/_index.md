---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Redact Text in PPT Presentations with Python
url: /python-net/redaction/ppt/
keywords: redact PPT, find and replace text in PPT, update PPT presentation
description: Find and replace sensitive text in PPT presentations with Python.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Redact Text in PPT Presentations with Python" h2="Build Python applications that find and replace sensitive text in presentations with Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Redact Text in a PPT Presentation with Python" variant="code" %}}

With [Aspose.Slides for Python via .NET](/slides/python-net/), you can replace sensitive text throughout a PPT presentation. Use `Presentation.replace_text` with `TextSearchOptions` to control the search, then save the modified presentation.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Redact Text in a PPT Presentation - Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.ppt") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Redact Text in a PPT Presentation with Python" intro="Follow these steps to replace sensitive text in a PPT presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the PPT file with `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) with `TextSearchOptions` to replace the required text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the modified presentation with `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Redaction Formats" subTitle="Use Python to redact text in other supported presentation formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
