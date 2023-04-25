---
title: Visa eller redigera metadata för PPT filer med .NET
url: /sv/net/metadata/ppt/
keywords: Redigera PPT-metadata, visa PPT-metadata, redigera PPT-egenskaper, visa PPT-egenskaper
description: Källkod för C# för att redigera eller visa metadata i formatet PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redigera egenskaper för PPT med C#" h2="Bygg dina egna .NET-appar för att ändra inbyggda och anpassade egenskaper i presentationsfiler med hjälp av API:er på serversidan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Ändra PPT-egenskaper via C#" %}}
Med hjälp av Aspose.Slides for .NET kan utvecklare komma åt och ändra värdena för inbyggda egenskaper såväl som anpassade egenskaper. Utvecklare kan använda egenskapen [DocumentProperties](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) som exponeras av Presentation-objektet för att komma åt presentationsfilens dokumentegenskaper.
{{% blocks/products/pf/agp/code-block title="Ändra PPT inbyggda egenskaper - C#" offSpacer="true" %}}

```cs

// Instantiate the Presentation class that represents the Presentation
Presentation presentation = new Presentation("presentation.ppt");

// Create a reference to IDocumentProperties object associated with Presentation
IDocumentProperties documentProperties = presentation.DocumentProperties;

// Set the builtin properties
documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

// Save your presentation to a file
presentation.Save("DocumentProperties_out.ppt", SaveFormat.Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Lägg till anpassade egenskaper i PPT - C#" offSpacer="true" %}}

```cs

// Instantiate the Presentation class
Presentation presentation = new Presentation();

// Getting Document Properties
IDocumentProperties documentProperties = presentation.DocumentProperties;

// Adding Custom properties
documentProperties["New Custom"] = 12;
documentProperties["My Name"] = "Aspose Metadata Editor";
documentProperties["Custom"] = 124;

// Getting property name at particular index
String getPropertyName = documentProperties.GetCustomPropertyName(2);

// Removing selected property
documentProperties.RemoveCustomProperty(getPropertyName);

// Save your presentation to a file
presentation.Save("CustomDocumentProperties_out.ppt", SaveFormat.Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man extraherar metadata för PPT via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att extrahera metadata från PPT-filer." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instantiera presentationsklassen med sökvägen till filen PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hämta DocumentProperties-objekt kopplat till Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Slinga över objekten i DocumentProperties-objektet
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Få tillgång till och ändra anpassade egenskaper
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra metadataformat som stöds" subTitle="Med hjälp av C# kan du också manipulera metadata i många andra format, inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}