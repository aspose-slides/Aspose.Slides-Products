---
title: Protégez les fichiers de présentation PPT à l'aide de Java
url: /fr/java/protect/ppt/
keywords: Protection en écriture PPT, Crypter une présentation PPT, Verrouiller la présentation PPT, Protéger PPT
description: Code source Java pour protéger la présentation PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Verrouiller ou protéger par mot de passe PPT en utilisant Java" h2="Créez vos propres applications Java pour protéger les fichiers de présentation à l'aide d'API côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Protéger une présentation PPT via Java" %}}
À l'aide de Aspose.Slides for Java, vous pouvez protéger votre présentation PPT contre l'ouverture ou la modification en définissant un mot de passe. Ensuite, pour ouvrir ou modifier la présentation verrouillée, un utilisateur doit fournir le mot de passe.
{{% blocks/products/pf/agp/code-block title="Chiffrement d'une présentation PPT à l'aide de Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.ppt");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-pres.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Définition de la protection en écriture sur une présentation PPT à l'aide de Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.ppt");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-pres.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment protéger par mot de passe PPT via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour protéger les fichiers PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger PPT avec une instance de Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Protéger la présentation à l'aide de la classe ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrer le résultat au format PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de protection pris en charge" subTitle="En utilisant Java, vous pouvez également protéger les formats suivants :" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/java/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}