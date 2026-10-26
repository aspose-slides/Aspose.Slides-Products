---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Déverrouiller des fichiers de présentation PPTX avec Java
url: /fr/java/unlock/pptx/
description: Supprimez les mots de passe et la protection en écriture des présentations PPTX en Java avec Aspose.Slides for Java.
keywords: Supprimer la protection en écriture PPTX, déchiffrer un PPTX, déverrouiller une présentation PPTX, déprotéger un PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Déverrouiller un PPTX avec Java" h2="Créez des applications Java qui suppriment les mots de passe et la protection en écriture des fichiers de présentation grâce à des API côté serveur." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Supprimer la protection d'une présentation PPTX avec Java" variant="code" %}}

Avec [Aspose.Slides for Java](/slides/fr/java/), vous pouvez supprimer le chiffrement ou la protection en écriture d'une présentation PPTX. Utilisez `LoadOptions.setPassword` pour ouvrir une présentation chiffrée, puis les méthodes `removeEncryption` et `removeWriteProtection` de `ProtectionManager` pour supprimer les paramètres de protection.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Supprimer la protection par mot de passe d'un PPTX avec Java" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.pptx", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Supprimer la protection en écriture d'une présentation PPTX avec Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment supprimer le mot de passe d'un PPTX avec Java" intro="Suivez ces étapes pour supprimer la protection d'une présentation PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier PPTX avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Utilisez `LoadOptions.setPassword` si la présentation est chiffrée.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez `removeEncryption` ou `removeWriteProtection` de l'objet `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez la présentation déverrouillée avec `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Conçu avec Aspose.Slides" title="Déverrouiller des fichiers PPTX en ligne" description="L'application gratuite Aspose.Slides Unlock est conçue avec [Aspose.Slides for Java](https://products.aspose.com/slides/fr/java/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPTX." button="Ouvrir Aspose.Slides Unlock" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides supprime la protection avant d'écrire du code.
- Supprimez le mot de passe ou la protection en écriture de votre fichier PPTX.
- Téléchargez le fichier déverrouillé.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour le déverrouillage" subTitle="Avec Java, vous pouvez également supprimer la protection des formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/java/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
