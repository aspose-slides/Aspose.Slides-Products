---
title: Masquer les fichiers de présentation ODP à l'aide de Python
url: /fr/python-net/redaction/odp/
keywords: Caviarder ODP, rechercher et remplacer du texte dans ODP, mettre à jour la présentation ODP
description: Code source Python pour rechercher et remplacer du texte dans la présentation ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Caviardez ODP en utilisant Python" h2="Créez vos propres applications Python pour rechercher et remplacer du texte dans les fichiers de présentation à l'aide d'API côté serveur. Découvrez comment rechercher et remplacer du texte dans le contenu, les commentaires ou les métadonnées des présentations ODP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Caviarder la présentation ODP via Python" %}}
Une recherche de document de base et le remplacement de texte dans le contenu, les commentaires, les notes de diapositive ou les métadonnées avec les API Aspose.Slides for Python via .NET peuvent être effectués avec seulement quelques lignes de code. Recherchez et remplacez du texte dans PowerPoint et OpenOffice. Modifiez le texte, les commentaires, les métadonnées dans la présentation via la correspondance des données regexp.
{{% blocks/products/pf/agp/code-block title="Caviarder ODP Présentation en utilisant Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.odp") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment expurger ODP via Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour expurger les fichiers ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chargez ODP avec une instance de Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utilisez la méthode [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) pour rechercher et remplacer du texte.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrer le résultat au format ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Démonstrations en direct de la rédaction ODP en ligne" sectionDescription="Recherchez et remplacez du texte dans le contenu, les commentaires ou les métadonnées des documents ODP dès maintenant." >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de rédaction pris en charge" subTitle="À l'aide de Python, vous pouvez également masquer les formats suivants :" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/python-net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}