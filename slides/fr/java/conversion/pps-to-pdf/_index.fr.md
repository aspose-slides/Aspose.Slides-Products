---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PPS en PDF via Java
weight: 2040
url: /fr/java/conversion/pps-to-pdf/ 
description: Exemple de code de conversion Java pour le format PPS en fichier PDF. Utilisez cet exemple de code pour exporter des présentations PowerPoint et OpenOffice au format PDF dans n'importe quelle application Web ou de bureau basée sur Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PPS en PDF via Java" h2="Conversion PPS en PDF Java pour convertir une ou plusieurs pages en PDF à l'aide de la bibliothèque Java sur site."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Comment convertir PPS en PDF en utilisant Java" %}}

Afin de rendre PPS en PDF, nous utiliserons
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code source de conversion PPS en PDF Java" >}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("template.pps");
// save the presentation as PDF
presentation.save("output.pdf", SaveFormat.Pdf);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Étapes pour convertir PPS en PDF via Java" intro="Les développeurs Java peuvent facilement convertir un fichier PPS en PDF en quelques lignes de code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Charger le fichier PPS avec une instance de la classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode Presentation.save tout en spécifiant le chemin du fichier de sortie et SaveFormat{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Le fichier PDF sera enregistré dans le chemin spécifié{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Configuration requise" intro="Avant d'exécuter l'exemple de code de conversion Java, assurez-vous que vous disposez des prérequis suivants." %}}

- Microsoft Windows ou un système d'exploitation compatible avec Java Runtime Environment pour les applications d'application et de bureau JSP/JSF.
- Obtenez la dernière version d'Aspose.Slides pour Java directement à partir de Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Application gratuite pour convertir PPS en PDF"
  description="[Essayez notre application gratuite pour convertir PPT en PDF](https://products.aspose.app/slides/conversion/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir PPS en de nombreux autres formats de fichiers, dont quelques-uns sont répertoriés ci-dessous." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-bmp/" name="PPS TO BMP" description="Image bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-gif/" name="PPS TO GIF" description="Format d'échange graphique" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-html/" name="PPS TO HTML" description="Langage Signalétique Hyper Text" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-jpeg/" name="PPS TO JPEG" description="Images JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-odp/" name="PPS TO ODP" description="Format de présentation OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-otp/" name="PPS TO OTP" description="Format standard OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-png/" name="PPS TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-pot/" name="PPS TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-potm/" name="PPS TO POTM" description="Fichier de modèle Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-potx/" name="PPS TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Diaporama compatible avec les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="Diaporama PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-pptm/" name="PPS TO PPTM" description="Fichier de présentation prenant en charge les macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Format de présentation XML ouvert" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-svg/" name="PPS TO SVG" description="Image Vectorielle" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-swf/" name="PPS TO SWF" description="Format SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Format d'image balisé" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/java/conversion/pps-to-xps/" name="PPS TO XPS" description="Spécifications papier XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
