---
title: Protégez les fichiers de présentation ODP à l'aide de .NET
url: /fr/net/protect/odp/
keywords: Protection en écriture ODP, Crypter une présentation ODP, Verrouiller la présentation ODP, Protéger ODP
description: Code source C# pour protéger la présentation ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Verrouiller ou protéger par mot de passe ODP en utilisant C#" h2="Créez vos propres applications .NET pour protéger les fichiers de présentation à l'aide d'API côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Protéger une présentation ODP via C#" %}}
À l'aide de Aspose.Slides for .NET, vous pouvez protéger votre présentation ODP contre l'ouverture ou la modification en définissant un mot de passe. Ensuite, pour ouvrir ou modifier la présentation verrouillée, un utilisateur doit fournir le mot de passe.
{{% blocks/products/pf/agp/code-block title="Chiffrement d'une présentation ODP à l'aide de C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Définition de la protection en écriture sur une présentation ODP à l'aide de C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment protéger par mot de passe ODP via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour protéger les fichiers ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger ODP avec une instance de Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Protéger la présentation à l'aide de la classe ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrer le résultat au format ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de protection pris en charge" subTitle="En utilisant C#, vous pouvez également protéger les formats suivants :" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}