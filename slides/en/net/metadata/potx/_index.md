---
title: View or Edit POTX Files Metadata using .NET
url: /net/metadata/potx/
keywords: Edit POTX Metadata, View POTX Metadata, Edit POTX properties, View POTX properties
description: C# source code to edit or view POTX format metadata.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Edit POTX Properties using C#" h2="Build .NET apps that read and modify built-in and custom presentation properties with server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="POTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Modify POTX Properties via C#" %}}
Using [Aspose.Slides for .NET](/slides/net/), developers can access and modify built-in and custom presentation properties. Use the [`DocumentProperties`](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) property exposed by a `Presentation` object to read and update POTX metadata.
{{% blocks/products/pf/agp/code-block title="Modify POTX Built-in Properties - C#" offSpacer="true" %}}

```cs
using var presentation = new Presentation("presentation.potx");
var documentProperties = presentation.DocumentProperties;

documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

presentation.Save("DocumentProperties_out.potx", SaveFormat.Potx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Add Custom Properties to POTX - C#" offSpacer="true" %}}

```cs
using var presentation = new Presentation();
var documentProperties = presentation.DocumentProperties;

documentProperties["New Custom"] = 12;
documentProperties["My Name"] = "Aspose Metadata Editor";
documentProperties["Custom"] = 124;

var propertyName = documentProperties.GetCustomPropertyName(2);
documentProperties.RemoveCustomProperty(propertyName);

presentation.Save("CustomDocumentProperties_out.potx", SaveFormat.Potx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Extract Metadata of POTX via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to extract metadata from POTX files." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the POTX file with `Presentation`.
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
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/net/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
