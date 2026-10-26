---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Protéger des fichiers de présentation PPT avec Python
url: /fr/python-net/protect/ppt/
description: Chiffrez des présentations PPT ou définissez une protection en écriture avec Python.
keywords: protection en écriture PPT, chiffrer un PPT avec Python, verrouiller une présentation PPT, protéger un PPT avec Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Protéger des présentations PPT avec Python" h2="Créez des applications Python qui chiffrent des présentations ou définissent une protection en écriture avec Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Protéger une présentation PPT avec Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/fr/python-net/) offre deux mécanismes de protection distincts. Appelez `ProtectionManager.encrypt` pour chiffrer une présentation PPT et exiger un mot de passe à l'ouverture. Vous pouvez aussi appeler `ProtectionManager.set_write_protection` pour dissuader toute modification sans chiffrer le fichier. Un utilisateur peut toujours ouvrir une présentation protégée en écriture et enregistrer ses modifications dans un autre fichier.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Chiffrer une présentation PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Définir la protection en écriture d'une présentation PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment protéger un PPT avec Python" intro="Suivez ces étapes pour protéger un fichier PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ouvrez le fichier PPT avec `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utilisez `ProtectionManager.encrypt` pour exiger un mot de passe à l'ouverture, ou `ProtectionManager.set_write_protection` pour dissuader les modifications.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez la présentation protégée au format PPT avec `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Conçu avec Aspose.Slides" title="Protéger des fichiers PPT par mot de passe en ligne" description="L'application gratuite Aspose.Slides Lock est conçue avec [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/fr/python-net/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPT." button="Ouvrir Aspose.Slides Lock" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides protège les présentations avant d'écrire du code.
- Définissez un mot de passe pour ouvrir ou modifier votre fichier PPT.
- Téléchargez le fichier protégé.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour la protection" subTitle="Utilisez Python pour protéger d'autres formats de présentation pris en charge." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
