---
title: Déverrouillez les fichiers de présentation PPTX à l'aide de C++
url: /fr/cpp/unlock/pptx/
keywords: Supprimer la protection en écriture PPTX, décrypter une présentation PPTX, déverrouiller la présentation PPTX, déprotéger PPTX
description: Code source C++ pour supprimer la protection de la présentation PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Déverrouillez PPTX en utilisant C++" h2="Créez vos propres applications C++ pour supprimer les mots de passe de PowerPoint et décrypter les fichiers de présentations à l'aide d'API côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Suppression du cryptage de la présentation PPTX via C++" %}}
À l'aide de Aspose.Slides for C++, vous pouvez supprimer le cryptage ou la protection par mot de passe de la présentation PPTX. De cette façon, les utilisateurs peuvent accéder ou modifier la présentation PPTX sans restrictions.
{{% blocks/products/pf/agp/code-block title="Désactivation de la protection par mot de passe de PPTX à l'aide de C++" offSpacer="true" %}}

```cpp

auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"123123");
    
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"encryption-removed.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Suppression de la protection en écriture de la présentation PPTX à l'aide de C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment supprimer le mot de passe de PPTX via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour supprimer la protection des fichiers PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger PPTX avec une instance de Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Supprimer la protection en écriture à l'aide de la classe ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrer le résultat au format PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats pris en charge" subTitle="À l'aide de C++, vous pouvez également supprimer la protection des formats suivants :" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/unlock/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}