---
title: Zobrazení nebo úprava metadat souborů PPSM pomocí .NET
url: /cs/net/metadata/ppsm/
keywords: Upravit metadata PPSM, zobrazit metadata PPSM, upravit vlastnosti PPSM, zobrazit vlastnosti PPSM
description: Zdrojový kód C# pro úpravu nebo zobrazení metadat formátu PPSM.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Upravit vlastnosti PPSM pomocí C#" h2="Vytvořte si vlastní aplikace .NET a upravte vestavěné a vlastní vlastnosti v souborech prezentace pomocí rozhraní API na straně serveru." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSM" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Upravit vlastnosti PPSM prostřednictvím C#" %}}
Pomocí Aspose.Slides for .NET mohou vývojáři přistupovat k hodnotám vestavěných i vlastních vlastností a upravovat je. Vývojáři mohou použít vlastnost [DocumentProperties](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) vystavenou objektem Presentation pro přístup k vlastnostem dokumentu souboru prezentace.
{{% blocks/products/pf/agp/code-block title="Upravit PPSM vestavěné vlastnosti – C#" offSpacer="true" %}}

```cs

// Instantiate the Presentation class that represents the Presentation
Presentation presentation = new Presentation("presentation.ppsm");

// Create a reference to IDocumentProperties object associated with Presentation
IDocumentProperties documentProperties = presentation.DocumentProperties;

// Set the builtin properties
documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

// Save your presentation to a file
presentation.Save("DocumentProperties_out.ppsm", SaveFormat.Ppsm);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Přidat uživatelské vlastnosti do PPSM – C#" offSpacer="true" %}}

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
presentation.Save("CustomDocumentProperties_out.ppsm", SaveFormat.Ppsm);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak extrahovat metadata PPSM přes C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky k extrahování metadat ze souborů PPSM." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvořte instanci třídy Presentation s cestou k souboru PPSM
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Získat objekt DocumentProperties spojený s Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Opakujte položky v objektu DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přístup a úpravy uživatelských vlastností
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty metadat" subTitle="Pomocí C# můžete také manipulovat s metadaty mnoha dalších formátů, včetně." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/net/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}