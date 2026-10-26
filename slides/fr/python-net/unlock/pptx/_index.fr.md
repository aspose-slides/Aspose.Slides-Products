---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Déverrouiller des présentations PPTX avec Python
url: /fr/python-net/unlock/pptx/
description: Supprimez le chiffrement et la protection en écriture des présentations PPTX avec Python.
keywords: déverrouiller un PPTX, supprimer le mot de passe d'un PPTX, supprimer le chiffrement PPTX, supprimer la protection en écriture d'un PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Déverrouiller des présentations PPTX avec Python" h2="Créez des applications Python qui suppriment les mots de passe d'ouverture et la protection en écriture des présentations PPTX avec Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Supprimer le chiffrement et la protection en écriture d'un PPTX avec Python" variant="code" %}}

Avec [Aspose.Slides for Python via .NET](/slides/fr/python-net/), vous pouvez supprimer le chiffrement qui exige un mot de passe pour ouvrir une présentation PPTX, ou désactiver sa protection en écriture. Pour ouvrir un fichier chiffré, indiquez le mot de passe actuel via `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Supprimer le chiffrement d'une présentation PPTX – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.pptx", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Supprimer la protection en écriture d'une présentation PPTX – Python" >}}
```py
with slides.Presentation("write-protected-presentation.pptx") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment supprimer la protection d'un PPTX avec Python" intro="Suivez ces étapes pour supprimer la protection d'une présentation PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pour un fichier PPTX chiffré, définissez le mot de passe actuel dans `LoadOptions`, puis ouvrez le fichier avec `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez `ProtectionManager.remove_encryption` pour supprimer le mot de passe d'ouverture, ou `ProtectionManager.remove_write_protection` pour désactiver la protection en écriture.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez la présentation obtenue avec `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Conçu avec Aspose.Slides" title="Déverrouiller des fichiers PPTX en ligne" description="L'application gratuite Aspose.Slides Unlock est conçue avec [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fr/python-net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPTX." button="Ouvrir Aspose.Slides Unlock" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides supprime la protection avant d'écrire du code.
- Supprimez le mot de passe ou la protection en écriture de votre fichier PPTX.
- Téléchargez le fichier déverrouillé.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour le déverrouillage" subTitle="Utilisez Python pour supprimer la protection d'autres formats de présentation pris en charge." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
