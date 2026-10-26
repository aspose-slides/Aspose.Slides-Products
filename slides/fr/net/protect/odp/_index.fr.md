---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Protéger des fichiers de présentation ODP avec .NET
url: /fr/net/protect/odp/
description: Code source C# pour protéger des présentations ODP par mot de passe.
keywords: Protection en écriture ODP, chiffrer un ODP, verrouiller une présentation ODP, protéger un ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Verrouiller ou protéger par mot de passe des fichiers ODP avec C#" h2="Créez des applications .NET qui chiffrent les présentations et limitent les modifications grâce à des API côté serveur." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Protéger une présentation ODP avec C#" variant="code" %}}

Avec [Aspose.Slides for .NET](/slides/fr/net/), vous pouvez chiffrer une présentation ODP ou limiter sa modification par un mot de passe. L'ouverture d'une présentation chiffrée avec `ProtectionManager.Encrypt` exige le mot de passe. Utilisez `ProtectionManager.SetWriteProtection` pour autoriser l'ouverture de la présentation tout en limitant les modifications.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Chiffrer une présentation ODP avec C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Définir la protection en écriture d'une présentation ODP avec C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment protéger une présentation ODP par mot de passe avec C#" intro="Suivez ces étapes pour protéger une présentation ODP par mot de passe." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier ODP avec `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chiffrez la présentation avec `ProtectionManager.Encrypt` ou limitez les modifications avec `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le fichier protégé avec `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Conçu avec Aspose.Slides" title="Protéger des fichiers ODP par mot de passe en ligne" description="L'application gratuite Aspose.Slides Lock est conçue avec [Aspose.Slides for .NET](https://products.aspose.com/slides/fr/net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers ODP." button="Ouvrir Aspose.Slides Lock" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides protège les présentations avant d'écrire du code.
- Définissez un mot de passe pour ouvrir ou modifier votre fichier ODP.
- Téléchargez le fichier protégé.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour la protection" subTitle="Avec C#, vous pouvez également protéger les formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
