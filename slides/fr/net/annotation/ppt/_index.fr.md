---
title: Supprimer l'annotation PPT à l'aide de .NET
weight: 4380
url: /fr/net/annotation/ppt/ 
description: Code source C# pour supprimer les annotations au format PPT sur les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Supprimer les commentaires et les auteurs de commentaires de PPT en C#" h2="Créez vos propres applications .NET pour manipuler les commentaires et les auteurs dans les fichiers de document à l'aide d'API côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Supprimer les commentaires de PPT via C#" %}}
Afin de supprimer les annotations du fichier PPT, nous utiliserons l'API [Aspose.Slides pour .NET](https://products.aspose.com/slides/fr/net) qui est riche en fonctionnalités, puissante et facile à utiliser API de manipulation de documents pour la plateforme C#.
{{% blocks/products/pf/agp/code-block title="Supprimer les annotations de PPT - C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.ppt"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Comment supprimer des commentaires de PPT via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez **Aspose.Slides pour .NET**. Voir [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger PPT avec une instance de la classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Itérer sur tous les auteurs du PPT chargé
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Supprimer tous les commentaires d'un auteur
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Supprimer tous les auteurs à la fin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats d'annotation pris en charge" subTitle="En utilisant C#, on peut facilement annoter d'autres formats, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}