---
lastmod: 2026-07-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Redact PPTX Presentation Files using .NET
url: /net/redaction/pptx/
keywords: Redact PPTX, Find and Replace Text in PPTX, Update PPTX Presentation
description: C# source code to find and replace text in PPTX presentations.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redact PPTX Files using C#" h2="Build .NET apps that find and replace text in presentations with server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Redact a PPTX Presentation using C#" %}}
With [Aspose.Slides for .NET](/slides/net/), you can find and replace text in a PPTX presentation. Use `Presentation.ReplaceText` with `TextSearchOptions` to control the search, then save the modified presentation.
{{% blocks/products/pf/agp/code-block title="Redact PPTX Presentation using C#" offSpacer="true" %}}

```cs
using var presentation = new Presentation("presentation.pptx");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Redact a PPTX Presentation using C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to replace text in a PPTX presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PPTX file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Use [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) with `TextSearchOptions` to replace the required text.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the modified presentation with `SaveFormat.Pptx`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Redaction" sectionDescription="Find and replace text in PPTX presentations online." >}}
{{< /blocks/products/pf/agp/demobox >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Redaction Formats" subTitle="Using C#, you can also redact the following formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}