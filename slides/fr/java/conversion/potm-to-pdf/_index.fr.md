---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir POTM en PDF via Java
weight: 7440
url: /fr/java/conversion/potm-to-pdf/ 
description: Exemple de code de conversion Java pour le format POTM en fichier PDF. Utilisez cet exemple de code pour exporter des présentations PowerPoint et OpenOffice au format PDF dans n'importe quelle application Web ou de bureau basée sur Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir POTM en PDF via Java" h2="Conversion POTM en PDF Java pour convertir une ou plusieurs pages en PDF à l'aide de la bibliothèque Java sur site."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Comment convertir POTM en PDF en utilisant Java" %}}

Afin de rendre POTM en PDF, nous utiliserons
 [Aspose.Slides pour Java](https://products.aspose.com/slides/fr/java/)
 API qui est une API de conversion riche en fonctionnalités, puissante et facile à utiliser pour la plate-forme Java. Vous pouvez télécharger sa dernière version directement depuis
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 et installez-le dans votre projet basé sur Maven en ajoutant les configurations suivantes au fichier pom.xml.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Dépôt" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Dépendance" >}}
```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code source de conversion POTM en PDF Java" >}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("template.potm");
// save the presentation as PDF
presentation.save("output.pdf", SaveFormat.Pdf);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Étapes pour convertir POTM en PDF via Java" intro="Les développeurs Java peuvent facilement convertir un fichier POTM en PDF en quelques lignes de code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Charger le fichier POTM avec une instance de la classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode Presentation.save tout en spécifiant le chemin du fichier de sortie et SaveFormat{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Le fichier PDF sera enregistré dans le chemin spécifié{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Configuration requise" intro="Avant d'exécuter l'exemple de code de conversion Java, assurez-vous que vous disposez des prérequis suivants." %}}

- Microsoft Windows ou un système d'exploitation compatible avec Java Runtime Environment pour les applications d'application et de bureau JSP/JSF.
- Obtenez la dernière version d'Aspose.Slides pour Java directement à partir de Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Conçu avec Aspose.Slides" title="Convertir POTM en PDF en ligne" description="L'application gratuite Aspose.Slides Conversion est conçue avec [Aspose.Slides for Java](https://products.aspose.com/slides/fr/java/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers POTM." button="Ouvrir Aspose.Slides Conversion" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" upload="Déposez ou importez votre fichier" saveAs="Enregistrer sous" convert="Convertir" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Découvrez comment Aspose.Slides convertit les fichiers avant d'écrire du code.
- Téléchargez des fichiers POTM et enregistrez-les au format PDF.
- Téléchargez le résultat ou convertissez d'autres fichiers.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir POTM dans de nombreux autres formats de fichiers, dont quelques-uns sont répertoriés ci-dessous." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-bmp/" name="POTM TO BMP" description="Image bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-gif/" name="POTM TO GIF" description="Format d'échange graphique" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-html/" name="POTM TO HTML" description="Langage Signalétique Hyper Text" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-jpeg/" name="POTM TO JPEG" description="Images JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-odp/" name="POTM TO ODP" description="Format de présentation OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-otp/" name="POTM TO OTP" description="Format standard OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-png/" name="POTM TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-pot/" name="POTM TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-potx/" name="POTM TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-pps/" name="POTM TO PPS" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Diaporama compatible avec les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Fichier de présentation prenant en charge les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Format de présentation XML ouvert" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-svg/" name="POTM TO SVG" description="Image Vectorielle" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-swf/" name="POTM TO SWF" description="Format SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Format d'image balisé" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/potm-to-xps/" name="POTM TO XPS" description="Spécifications papier XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
