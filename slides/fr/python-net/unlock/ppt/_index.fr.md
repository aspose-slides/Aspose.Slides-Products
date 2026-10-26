---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Déverrouiller des présentations PPT avec Python
url: /fr/python-net/unlock/ppt/
description: Supprimez le chiffrement et la protection en écriture des présentations PPT avec Python.
keywords: déverrouiller un PPT, supprimer le mot de passe d'un PPT, supprimer le chiffrement PPT, supprimer la protection en écriture d'un PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Déverrouiller des présentations PPT avec Python" h2="Créez des applications Python qui suppriment les mots de passe d'ouverture et la protection en écriture des présentations PPT avec Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Supprimer le chiffrement et la protection en écriture d'un PPT avec Python" variant="code" %}}

Avec [Aspose.Slides for Python via .NET](/slides/fr/python-net/), vous pouvez supprimer le chiffrement qui exige un mot de passe pour ouvrir une présentation PPT, ou désactiver sa protection en écriture. Pour ouvrir un fichier chiffré, indiquez le mot de passe actuel via `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Supprimer le chiffrement d'une présentation PPT – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.ppt", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Supprimer la protection en écriture d'une présentation PPT – Python" >}}
```py
with slides.Presentation("write-protected-presentation.ppt") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment supprimer la protection d'un PPT avec Python" intro="Suivez ces étapes pour supprimer la protection d'une présentation PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pour un fichier PPT chiffré, définissez le mot de passe actuel dans `LoadOptions`, puis ouvrez le fichier avec `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez `ProtectionManager.remove_encryption` pour supprimer le mot de passe d'ouverture, ou `ProtectionManager.remove_write_protection` pour désactiver la protection en écriture.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez la présentation obtenue avec `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Conçu avec Aspose.Slides" title="Déverrouiller des fichiers PPT en ligne" description="L'application gratuite Aspose.Slides Unlock est conçue avec [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fr/python-net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPT." button="Ouvrir Aspose.Slides Unlock" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides supprime la protection avant d'écrire du code.
- Supprimez le mot de passe ou la protection en écriture de votre fichier PPT.
- Téléchargez le fichier déverrouillé.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour le déverrouillage" subTitle="Utilisez Python pour supprimer la protection d'autres formats de présentation pris en charge." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
