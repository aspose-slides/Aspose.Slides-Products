---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Protéger des présentations PPTX avec C++
url: /fr/cpp/protect/pptx/
description: Protégez des présentations PPTX en C++. Utilisez Aspose.Slides for C++ pour chiffrer des fichiers et définir une protection en écriture.
keywords: Protection en écriture PPTX, chiffrer un PPTX, verrouiller une présentation PPTX, protéger un PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Verrouiller ou protéger un PPTX par mot de passe avec C++" h2="Utilisez Aspose.Slides for C++ pour chiffrer des présentations et définir une protection en écriture sans Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Protéger une présentation PPTX avec C++" variant="code" %}}

Aspose.Slides for C++ vous permet d'empêcher l'ouverture ou la modification de présentations PPTX. Utilisez l'objet `ProtectionManager` de la classe `Presentation` pour chiffrer un fichier avec `Encrypt` ou limiter sa modification avec `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Chiffrer une présentation PPTX avec C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Définir la protection en écriture d'une présentation PPTX avec C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment protéger un PPTX par mot de passe avec C++" intro="Suivez ces étapes pour protéger une présentation PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier PPTX avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Protégez la présentation avec l'objet `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utilisez `Encrypt` pour la protection par mot de passe ou `SetWriteProtection` pour la protection en écriture.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le fichier protégé avec `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Conçu avec Aspose.Slides" title="Protéger des fichiers PPTX par mot de passe en ligne" description="L'application gratuite Aspose.Slides Lock est conçue avec [Aspose.Slides for C++](https://products.aspose.com/slides/fr/cpp/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPTX." button="Ouvrir Aspose.Slides Lock" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides protège les présentations avant d'écrire du code.
- Définissez un mot de passe pour ouvrir ou modifier votre fichier PPTX.
- Téléchargez le fichier protégé.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour la protection" subTitle="Avec C++, vous pouvez également protéger les formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
