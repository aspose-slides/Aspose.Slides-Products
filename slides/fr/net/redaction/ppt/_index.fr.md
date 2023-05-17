---
title: Masquer les fichiers de présentation PPT à l'aide de .NET
url: /fr/net/redaction/ppt/
keywords: Caviarder PPT, rechercher et remplacer du texte dans PPT, mettre à jour la présentation PPT
description: Code source C# pour rechercher et remplacer du texte dans la présentation PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Caviardez PPT en utilisant C#" h2="Créez vos propres applications .NET pour rechercher et remplacer du texte dans les fichiers de présentation à l'aide d'API côté serveur. Découvrez comment rechercher et remplacer du texte dans le contenu, les commentaires ou les métadonnées des présentations PPT" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Caviarder la présentation PPT via C#" %}}
Une recherche de document de base et le remplacement de texte dans le contenu, les commentaires, les notes de diapositive ou les métadonnées avec les API Aspose.Slides for .NET peuvent être effectués avec seulement quelques lignes de code. Recherchez et remplacez du texte dans PowerPoint et OpenOffice. Modifiez le texte, les commentaires, les métadonnées dans la présentation via la correspondance des données regexp.
{{% blocks/products/pf/agp/code-block title="Caviarder PPT Présentation en utilisant C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.ppt"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment expurger PPT via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour expurger les fichiers PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chargez PPT avec une instance de Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Utilisez la méthode [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) pour rechercher et remplacer du texte.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrer le résultat au format PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Démonstrations en direct de la rédaction PPT en ligne" sectionDescription="Recherchez et remplacez du texte dans le contenu, les commentaires ou les métadonnées des documents PPT dès maintenant." >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de rédaction pris en charge" subTitle="À l'aide de C#, vous pouvez également masquer les formats suivants :" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}