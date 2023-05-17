---
title:  Redact PPTX Presentation Files using Python
url: /python-net/redaction/pptx/
keywords: Redact PPTX, find and replace text in PPTX, update PPTX Presentation
description: Python source code to find and replace text in PPTX Presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redact PPTX using Python" h2="Build your own Python apps to find and replace text in presentation files using server-side APIs. Learn how to search and replace text in content, comments or metadata of PPTX presentations" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Redact PPTX Presentation via Python" %}}
A basic document search and replace text in contents, comments, slide notes or metadata with Aspose.Slides for Python via .NET APIs can be done with just few lines of code. Find and replace text in PowerPoint and OpenOffice. Edit text, comments, metadata in presentation via regexp data matching.
{{% blocks/products/pf/agp/code-block title="Redact PPTX Presentation using Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.pptx") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Redact PPTX via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to Redact PPTX files." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load PPTX with an instance of Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Use [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) method to find and replace text.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result in PPTX format
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Redaction Live Demos" sectionDescription="Search and replace text in contents, comments or metadata in PPTX documents right now." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Redact Formats" subTitle="Using Python, You can also redact the following formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}