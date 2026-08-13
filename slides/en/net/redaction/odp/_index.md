---
lastmod: 2026-07-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Redact ODP Presentation Files using .NET
url: /net/redaction/odp/
keywords: Redact ODP, Find and Replace Text in ODP, Update ODP Presentation
description: C# source code to find and replace text in ODP presentations.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redact ODP Files using C#" h2="Build .NET apps that find and replace text in presentations with server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Redact an ODP Presentation using C#" %}}
With [Aspose.Slides for .NET](/slides/net/), you can find and replace text in an ODP presentation. Use `Presentation.ReplaceText` with `TextSearchOptions` to control the search, then save the modified presentation.
{{% blocks/products/pf/agp/code-block title="Redact ODP Presentation using C#" offSpacer="true" %}}

```cs
using var presentation = new Presentation("presentation.odp");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.odp", SaveFormat.Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Redact an ODP Presentation using C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to replace text in an ODP presentation." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the ODP file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Use [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) with `TextSearchOptions` to replace the required text.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the modified presentation with `SaveFormat.Odp`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Redaction" sectionDescription="Find and replace text in ODP presentations online." >}}
{{< /blocks/products/pf/agp/demobox >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Redaction Formats" subTitle="Using C#, you can also redact the following formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}