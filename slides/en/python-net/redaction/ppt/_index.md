---
title: Redact Text in PPT Presentations with Python
url: /python-net/redaction/ppt/
keywords: redact PPT, find and replace text in PPT, update PPT presentation
description: Find and replace sensitive text in PPT presentations with Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redact Text in PPT Presentations with Python" h2="Build Python applications that find and replace sensitive text in presentations with Aspose.Slides." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides" subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Redact Text in a PPT Presentation with Python" %}}
With [Aspose.Slides for Python via .NET](/slides/python-net/), you can replace sensitive text throughout a PPT presentation. Use `Presentation.replace_text` with `TextSearchOptions` to control the search, then save the modified presentation.
{{% blocks/products/pf/agp/code-block title="Redact Text in a PPT Presentation - Python" offSpacer="true" %}}

```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.ppt") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Redact Text in a PPT Presentation with Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to replace sensitive text in a PPT presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the PPT file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Use [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) with `TextSearchOptions` to replace the required text.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the modified presentation with `SaveFormat.PPT`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Redaction" sectionDescription="Find and replace text in PPT presentations online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Redaction Formats" subTitle="Use Python to redact text in other supported presentation formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/python-net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
