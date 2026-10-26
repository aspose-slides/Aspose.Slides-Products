---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Déverrouiller des présentations ODP avec C++
url: /fr/cpp/unlock/odp/
description: Déverrouillez des présentations ODP en C++. Utilisez Aspose.Slides for C++ pour supprimer le chiffrement et la protection en écriture des fichiers de présentation.
keywords: Supprimer la protection en écriture ODP, déchiffrer un ODP, déverrouiller une présentation ODP, déprotéger un ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Déverrouiller un ODP avec C++" h2="Utilisez Aspose.Slides for C++ pour supprimer le chiffrement et la protection en écriture des fichiers de présentation sans Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Supprimer la protection d'une présentation ODP avec C++" variant="code" %}}

Aspose.Slides for C++ vous permet de supprimer le chiffrement ou la protection en écriture des présentations ODP. Utilisez `LoadOptions` pour ouvrir un fichier chiffré, puis l'objet `ProtectionManager` de la classe `Presentation` pour appeler `RemoveEncryption` ou `RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Supprimer la protection par mot de passe d'un ODP avec C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.odp", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Supprimer la protection en écriture d'une présentation ODP avec C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.odp");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment supprimer le mot de passe d'un ODP avec C++" intro="Suivez ces étapes pour supprimer la protection d'une présentation ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier ODP avec la classe `Presentation`, et avec `LoadOptions` si un mot de passe est requis.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utilisez l'objet `ProtectionManager` pour supprimer la protection.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez `RemoveEncryption` pour les fichiers chiffrés ou `RemoveWriteProtection` pour les fichiers protégés en écriture.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le fichier déverrouillé avec `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Conçu avec Aspose.Slides" title="Déverrouiller des fichiers ODP en ligne" description="L'application gratuite Aspose.Slides Unlock est conçue avec [Aspose.Slides for C++](https://products.aspose.com/slides/fr/cpp/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers ODP." button="Ouvrir Aspose.Slides Unlock" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides supprime la protection avant d'écrire du code.
- Supprimez le mot de passe ou la protection en écriture de votre fichier ODP.
- Téléchargez le fichier déverrouillé.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour le déverrouillage" subTitle="Avec C++, vous pouvez également supprimer la protection des formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
