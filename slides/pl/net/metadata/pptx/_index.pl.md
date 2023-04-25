---
title: Wyświetl lub edytuj metadane plików PPTX za pomocą .NET
url: /pl/net/metadata/pptx/
keywords: Edytuj metadane PPTX, Wyświetl metadane PPTX, Edytuj właściwości PPTX, Wyświetl właściwości PPTX
description: Kod źródłowy C#, aby edytować lub przeglądać metadane formatu PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Edytuj właściwości PPTX za pomocą C#" h2="Twórz własne aplikacje .NET, aby modyfikować wbudowane i niestandardowe właściwości w plikach prezentacji za pomocą interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Zmodyfikuj właściwości PPTX za pomocą C#" %}}
Korzystając z Aspose.Slides for .NET, programiści mogą uzyskiwać dostęp i modyfikować wartości właściwości wbudowanych oraz właściwości niestandardowych. Deweloperzy mogą użyć właściwości [DocumentProperties](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) udostępnionej przez obiekt prezentacji, aby uzyskać dostęp do właściwości dokumentu w pliku prezentacji.
{{% blocks/products/pf/agp/code-block title="Zmodyfikuj wbudowane właściwości PPTX – C#" offSpacer="true" %}}

```cs

// Instantiate the Presentation class that represents the Presentation
Presentation presentation = new Presentation("presentation.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
IDocumentProperties documentProperties = presentation.DocumentProperties;

// Set the builtin properties
documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

// Save your presentation to a file
presentation.Save("DocumentProperties_out.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dodaj niestandardowe właściwości do PPTX – C#" offSpacer="true" %}}

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
presentation.Save("CustomDocumentProperties_out.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak wyodrębnić metadane PPTX przez C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Oto kroki, aby wyodrębnić metadane z plików PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utwórz instancję klasy Presentation ze ścieżką do pliku PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Pobierz obiekt DocumentProperties powiązany z prezentacją
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zapętl elementy w obiekcie DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uzyskaj dostęp do właściwości niestandardowych i modyfikuj je
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty metadanych" subTitle="Korzystając z C#, możesz także manipulować metadanymi wielu innych formatów, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pl/net/metadata/pptm/" name="PPTM" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}