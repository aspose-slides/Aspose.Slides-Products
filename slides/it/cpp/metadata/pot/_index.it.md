---
title: Visualizza o modifica i metadati dei file POT utilizzando C++
url: /it/cpp/metadata/pot/
keywords: Modifica metadati POT, Visualizza metadati POT, Modifica proprietà POT, Visualizza proprietà POT
description: C++ codice sorgente per modificare o visualizzare i metadati del formato POT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Modifica le proprietà POT utilizzando C++" h2="Crea le tue app C++ per modificare le proprietà integrate e personalizzate nei file di presentazione utilizzando le API lato server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Modifica le proprietà POT tramite C++" %}}
Utilizzando Aspose.Slides for C++, gli sviluppatori possono accedere e modificare i valori delle proprietà integrate e delle proprietà personalizzate. Gli sviluppatori possono utilizzare la proprietà [DocumentProperties](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) esposta dall'oggetto Presentation per accedere alle proprietà del documento del file di presentazione.
{{% blocks/products/pf/agp/code-block title="Modifica proprietà integrate POT - C++" offSpacer="true" %}}

```cpp

// Instantiate the Presentation class that represents the Presentation
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"presentation.pot");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();

// Set the builtin properties
documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

// Save your presentation to a file
presentation->Save(u"DocumentProperties_out.pot", SaveFormat::Pot);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Aggiungi proprietà personalizzate a POT - C++" offSpacer="true" %}}

```cpp

// Instantiate the Presentation class
auto presentation = System::MakeObject<Presentation>();

// Getting Document Properties
auto documentProperties = presentation->get_DocumentProperties();

// Adding Custom properties
documentProperties->idx_set(u"New Custom", ObjectExt::Box<int32_t>(12));
documentProperties->idx_set(u"My Name", ObjectExt::Box<String>(u"Aspose Metadata Editor"));
documentProperties->idx_set(u"Custom", ObjectExt::Box<int32_t>(124));

// Getting property name at particular index
String getPropertyName = documentProperties->GetCustomPropertyName(2);

// Removing selected property
documentProperties->RemoveCustomProperty(getPropertyName);

// Saving presentation
presentation->Save(u"CustomDocumentProperties_out.pot", SaveFormat::Pot);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Come estrarre i metadati di POT tramite C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Questi sono i passaggi per estrarre i metadati dai file POT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea un'istanza della classe Presentation con il percorso del file POT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ottenere l'oggetto DocumentProperties associato alla presentazione
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Passa sugli elementi nell'oggetto DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Accedi e modifica le proprietà personalizzate
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di metadati supportati" subTitle="Usando C++, puoi anche manipolare i metadati di molti altri formati tra cui." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/cpp/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}