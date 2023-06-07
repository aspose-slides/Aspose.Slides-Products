---
title: Déverrouillez les fichiers de présentation ODP à l'aide de .NET
url: /fr/net/unlock/odp/
keywords: Supprimer la protection en écriture ODP, décrypter une présentation ODP, déverrouiller la présentation ODP, déprotéger ODP
description: Code source C# pour supprimer la protection de la présentation ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Déverrouillez ODP en utilisant C#" h2="Créez vos propres applications .NET pour supprimer les mots de passe de PowerPoint et décrypter les fichiers de présentations à l'aide d'API côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Suppression du cryptage de la présentation ODP via C#" %}}
À l'aide de Aspose.Slides for .NET, vous pouvez supprimer le cryptage ou la protection par mot de passe de la présentation ODP. De cette façon, les utilisateurs peuvent accéder ou modifier la présentation ODP sans restrictions.
{{% blocks/products/pf/agp/code-block title="Désactivation de la protection par mot de passe de ODP à l'aide de C#" offSpacer="true" %}}

```cs

LoadOptions loadOptions = new LoadOptions {Password = "123123"};
using (Presentation presentation = new Presentation("pres.odp", loadOptions))
{
    presentation.ProtectionManager.RemoveEncryption();
    presentation.Save("encryption-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Suppression de la protection en écriture de la présentation ODP à l'aide de C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment supprimer le mot de passe de ODP via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour supprimer la protection des fichiers ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger ODP avec une instance de Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Supprimer la protection en écriture à l'aide de la classe ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrer le résultat au format ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats pris en charge" subTitle="À l'aide de C#, vous pouvez également supprimer la protection des formats suivants :" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}