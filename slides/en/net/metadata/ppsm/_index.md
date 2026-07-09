---
title: View or Edit PPSM Files Metadata using .NET
url: /net/metadata/ppsm/
keywords: Edit PPSM Metadata, View PPSM Metadata, Edit PPSM properties, View PPSM properties
description: C# source code to edit or view PPSM format metadata.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Edit PPSM Properties using C#" h2="Build .NET apps that read and modify built-in and custom presentation properties with server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSM" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Modify PPSM Properties via C#" %}}
Using [Aspose.Slides for .NET](/slides/net/), developers can access and modify built-in and custom presentation properties. Use the [`DocumentProperties`](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) property exposed by a `Presentation` object to read and update PPSM metadata.
{{% blocks/products/pf/agp/code-block title="Modify PPSM Built-in Properties - C#" offSpacer="true" %}}

```cs
using var presentation = new Presentation("presentation.ppsm");
var documentProperties = presentation.DocumentProperties;

documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

presentation.Save("DocumentProperties_out.ppsm", SaveFormat.Ppsm);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Add Custom Properties to PPSM - C#" offSpacer="true" %}}

```cs
using var presentation = new Presentation();
var documentProperties = presentation.DocumentProperties;

documentProperties["New Custom"] = 12;
documentProperties["My Name"] = "Aspose Metadata Editor";
documentProperties["Custom"] = 124;

var propertyName = documentProperties.GetCustomPropertyName(2);
documentProperties.RemoveCustomProperty(propertyName);

presentation.Save("CustomDocumentProperties_out.ppsm", SaveFormat.Ppsm);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Extract Metadata of PPSM via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to extract metadata from PPSM files." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PPSM file with `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Get the `DocumentProperties` object from the presentation.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Read or update built-in properties such as `Author`, `Title`, and `Subject`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Access and modify custom properties with `DocumentProperties`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Metadata Formats" subTitle="You can also manipulate metadata of many other formats in C#." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
