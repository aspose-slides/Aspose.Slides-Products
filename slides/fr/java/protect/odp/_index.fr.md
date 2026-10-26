---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Protéger des fichiers de présentation ODP avec Java
url: /fr/java/protect/odp/
description: Protégez des présentations ODP en Java. Utilisez Aspose.Slides for Java pour chiffrer des fichiers de présentation et définir une protection en écriture.
keywords: Protection en écriture ODP, chiffrer un ODP, verrouiller une présentation ODP, protéger un ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Verrouiller ou protéger un ODP par mot de passe avec Java" h2="Créez des applications Java qui protègent les fichiers de présentation grâce à des API côté serveur." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Protéger une présentation ODP avec Java" variant="code" %}}

Avec [Aspose.Slides for Java](/slides/fr/java/), vous pouvez empêcher l'ouverture ou la modification d'une présentation ODP en définissant un mot de passe. Utilisez l'objet `ProtectionManager` de la classe `Presentation` pour appeler des méthodes comme `encrypt` et `setWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Chiffrer une présentation ODP avec Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Définir la protection en écriture d'une présentation ODP avec Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment protéger un ODP par mot de passe avec Java" intro="Suivez ces étapes pour protéger une présentation ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier ODP avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode `encrypt` ou la méthode `setWriteProtection` de l'objet `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le fichier protégé avec `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Conçu avec Aspose.Slides" title="Protéger des fichiers ODP par mot de passe en ligne" description="L'application gratuite Aspose.Slides Lock est conçue avec [Aspose.Slides for Java](https://products.aspose.com/slides/fr/java/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers ODP." button="Ouvrir Aspose.Slides Lock" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides protège les présentations avant d'écrire du code.
- Définissez un mot de passe pour ouvrir ou modifier votre fichier ODP.
- Téléchargez le fichier protégé.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats pris en charge pour la protection" subTitle="Avec Java, vous pouvez également protéger les formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/java/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/java/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
