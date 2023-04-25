---
title: Afficher ou modifier les métadonnées des fichiers PPTM à l'aide de C++
url: /fr/cpp/metadata/pptm/
keywords: Modifier les métadonnées PPTM, Afficher les métadonnées PPTM, Modifier les propriétés PPTM, Afficher les propriétés PPTM
description: Code source C++ pour modifier ou afficher les métadonnées du format PPTM.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Modifier les propriétés PPTM à l'aide de C++" h2="Créez vos propres applications C++ pour modifier les propriétés intégrées et personnalisées dans les fichiers de présentation à l'aide d'API côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTM" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Modifier les propriétés PPTM via C++" %}}
À l'aide de Aspose.Slides for C++, les développeurs peuvent accéder et modifier les valeurs des propriétés intégrées ainsi que des propriétés personnalisées. Les développeurs peuvent utiliser la propriété [DocumentProperties](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) exposée par l'objet Presentation pour accéder aux propriétés de document du fichier de présentation.
{{% blocks/products/pf/agp/code-block title="Modifier les propriétés intégrées de PPTM - C++" offSpacer="true" %}}

```cpp

// Instantiate the Presentation class that represents the Presentation
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"presentation.pptm");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();

// Set the builtin properties
documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

// Save your presentation to a file
presentation->Save(u"DocumentProperties_out.pptm", SaveFormat::Pptm);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ajouter des propriétés personnalisées à PPTM - C++" offSpacer="true" %}}

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
presentation->Save(u"CustomDocumentProperties_out.pptm", SaveFormat::Pptm);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment extraire les métadonnées de PPTM via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour extraire les métadonnées des fichiers PPTM." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instanciez la classe Presentation avec le chemin vers le fichier PPTM
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Obtenir l'objet DocumentProperties associé à la présentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Boucle sur les éléments de l'objet DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Accéder et modifier les propriétés personnalisées
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de métadonnées pris en charge" subTitle="En utilisant C++, vous pouvez également manipuler les métadonnées de nombreux autres formats, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}