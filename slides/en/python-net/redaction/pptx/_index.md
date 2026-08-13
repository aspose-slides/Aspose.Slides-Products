---
lastmod: 2026-07-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Redact Text in PPTX Presentations with Python
url: /python-net/redaction/pptx/
keywords: redact PPTX, find and replace text in PPTX, update PPTX presentation
description: Find and replace sensitive text in PPTX presentations with Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redact Text in PPTX Presentations with Python" h2="Build Python applications that find and replace sensitive text in presentations with Aspose.Slides." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides" subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Redact Text in a PPTX Presentation with Python" %}}
With [Aspose.Slides for Python via .NET](/slides/python-net/), you can replace sensitive text throughout a PPTX presentation. Use `Presentation.replace_text` with `TextSearchOptions` to control the search, then save the modified presentation.
{{% blocks/products/pf/agp/code-block title="Redact Text in a PPTX Presentation - Python" offSpacer="true" %}}

```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.pptx") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Redact Text in a PPTX Presentation with Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to replace sensitive text in a PPTX presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the PPTX file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Use [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) with `TextSearchOptions` to replace the required text.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the modified presentation with `SaveFormat.PPTX`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Redaction" sectionDescription="Find and replace text in PPTX presentations online." >}}
{{< /blocks/products/pf/agp/demobox >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Redaction Formats" subTitle="Use Python to redact text in other supported presentation formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
