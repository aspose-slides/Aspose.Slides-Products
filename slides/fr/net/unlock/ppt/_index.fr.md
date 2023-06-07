---
title: Déverrouillez les fichiers de présentation PPT à l'aide de .NET
url: /fr/net/unlock/ppt/
keywords: Supprimer la protection en écriture PPT, décrypter une présentation PPT, déverrouiller la présentation PPT, déprotéger PPT
description: Code source C# pour supprimer la protection de la présentation PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Déverrouillez PPT en utilisant C#" h2="Créez vos propres applications .NET pour supprimer les mots de passe de PowerPoint et décrypter les fichiers de présentations à l'aide d'API côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Suppression du cryptage de la présentation PPT via C#" %}}
À l'aide de Aspose.Slides for .NET, vous pouvez supprimer le cryptage ou la protection par mot de passe de la présentation PPT. De cette façon, les utilisateurs peuvent accéder ou modifier la présentation PPT sans restrictions.
{{% blocks/products/pf/agp/code-block title="Désactivation de la protection par mot de passe de PPT à l'aide de C#" offSpacer="true" %}}

```cs

LoadOptions loadOptions = new LoadOptions {Password = "123123"};
using (Presentation presentation = new Presentation("pres.ppt", loadOptions))
{
    presentation.ProtectionManager.RemoveEncryption();
    presentation.Save("encryption-removed.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Suppression de la protection en écriture de la présentation PPT à l'aide de C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.ppt"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment supprimer le mot de passe de PPT via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour supprimer la protection des fichiers PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger PPT avec une instance de Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Supprimer la protection en écriture à l'aide de la classe ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrer le résultat au format PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats pris en charge" subTitle="À l'aide de C#, vous pouvez également supprimer la protection des formats suivants :" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}