---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Protéger des fichiers de présentation PPTX avec Python
url: /fr/python-net/protect/pptx/
description: Chiffrez des présentations PPTX ou définissez une protection en écriture avec Python.
keywords: protection en écriture PPTX, chiffrer un PPTX avec Python, verrouiller une présentation PPTX, protéger un PPTX avec Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Protéger des présentations PPTX avec Python" h2="Créez des applications Python qui chiffrent des présentations ou définissent une protection en écriture avec Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Protéger une présentation PPTX avec Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/fr/python-net/) offre deux mécanismes de protection distincts. Appelez `ProtectionManager.encrypt` pour chiffrer une présentation PPTX et exiger un mot de passe à l'ouverture. Vous pouvez aussi appeler `ProtectionManager.set_write_protection` pour dissuader toute modification sans chiffrer le fichier. Un utilisateur peut toujours ouvrir une présentation protégée en écriture et enregistrer ses modifications dans un autre fichier.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Chiffrer une présentation PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Définir la protection en écriture d'une présentation PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment protéger un PPTX avec Python" intro="Suivez ces étapes pour protéger un fichier PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez le fichier PPTX avec `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utilisez `ProtectionManager.encrypt` pour exiger un mot de passe à l'ouverture, ou `ProtectionManager.set_write_protection` pour dissuader les modifications.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez la présentation protégée au format PPTX avec `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Conçu avec Aspose.Slides" title="Protéger des fichiers PPTX par mot de passe en ligne" description="L'application gratuite Aspose.Slides Lock est conçue avec [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fr/python-net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPTX." button="Ouvrir Aspose.Slides Lock" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides protège les présentations avant d'écrire du code.
- Définissez un mot de passe pour ouvrir ou modifier votre fichier PPTX.
- Téléchargez le fichier protégé.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour la protection" subTitle="Utilisez Python pour protéger d'autres formats de présentation pris en charge." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
