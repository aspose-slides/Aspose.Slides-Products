---
title: Rechercher du texte dans les fichiers de présentation ODP à l'aide de C++
url: /fr/cpp/search/odp/
keywords: rechercher des mots dans ODP, rechercher et remplacer du texte dans ODP, rechercher du texte ODP
description: Code source C++ pour rechercher du texte dans la présentation ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Rechercher le texte ODP en utilisant C++" h2="Créez vos propres applications C++ pour rechercher et remplacer du texte dans les fichiers de présentation à l'aide d'API côté serveur. Apprenez à trouver toutes les entrées d'un mot ou d'une phrase dans les documents de présentation. Recherche de texte par correspondance exacte des données et correspondance des expressions régulières." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Rechercher et remplacer le texte ODP Présentation via C++" %}}
Une recherche de document de base et le remplacement de texte dans le contenu, les commentaires, les notes de diapositive ou les métadonnées avec les API Aspose.Slides for C++ peuvent être effectués avec seulement quelques lignes de code. Utilisez la correspondance d'expressions régulières, faites correspondre la casse pour rechercher du texte dans la présentation. Recherchez du texte dans les titres, le contenu, le pied de page ou l'en-tête.
{{% blocks/products/pf/agp/code-block title="Texte de recherche ODP Présentation utilisant C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.odp", SaveFormat::Odp);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment rechercher du texte en ODP via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour rechercher des fichiers texte ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chargez ODP avec une instance de Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utilisez la méthode [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) pour rechercher et remplacer du texte.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrer le résultat au format ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="ODP Rechercher des démos en direct en ligne" sectionDescription="Recherchez et remplacez du texte dans le contenu, les commentaires ou les métadonnées des documents ODP dès maintenant." >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de recherche pris en charge" subTitle="À l'aide de C++, vous pouvez également rechercher du texte dans les formats suivants :" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}