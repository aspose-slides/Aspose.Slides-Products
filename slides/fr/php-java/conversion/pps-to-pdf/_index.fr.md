---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PPS en PDF en PHP
weight: 1550
url: /fr/php-java/conversion/pps-to-pdf/ 
keywords: "Convert, PowerPoint, PPS, PDF, Presentation, PHP"
description: Exemple de code pour la conversion PHP de PPS à PDF. Utilisez l'API PHP PowerPoint pour la conversion par lots de fichiers PPS en fichiers PDF.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PPS en PDF en PHP" h2="Bibliothèque PHP PowerPoint puissante pour convertir PPS en PDF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PPS en PDF en PHP" %}}

Besoin de convertir des fichiers PPS en PDF par programmation ? En utilisant [*Aspose.Slides pour PHP via Java*](https://products.aspose.com/slides/fr/php-java/), n'importe quel développeur peut convertir le format PPS au format PDF avec seulement quelques lignes de code PHP .

En tant qu'API de traitement de présentation moderne, Aspose.Slides pour PHP crée rapidement PDF à partir de PPS. Testez la qualité de la conversion de PPS à PDF directement dans votre [navigateur](https://products.aspose.app/slides/conversion). La bibliothèque Aspose PowerPoint PPTX vous permet de convertir des fichiers PPS vers de nombreux formats populaires.

Vous pouvez installer la bibliothèque depuis [Composer](https://packagist.org/packages/aspose/slides) à l'aide de la commande suivante :

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Enregistrer PPS sous PDF en PHP" %}}

Utilisez l'application gratuite pour voir une démonstration du processus de conversion de PPS à PDF.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cet exemple de code montre la conversion PHP de PPS à PDF" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pps");
try
{
    $pres->save("output.pdf", SaveFormat::Pdf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir PPS en PDF en PHP" intro="Voici les étapes pour convertir un fichier PPS en PDF en utilisant PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Charger le fichier PPS avec une instance de la classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode `save` tout en spécifiant le chemin du fichier de sortie et SaveFormat.PDF en tant que paramètres{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Le fichier PPS sera enregistré dans le chemin spécifié{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Configuration requise" intro="Avant d'exécuter l'exemple de code source de conversion PHP, assurez-vous que vous disposez des prérequis suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez PHP 7, ajoutez le chemin vers PHP à la variable système `PATH` et définissez `allow_url_include` sur `On` dans le fichier `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez JRE 8. Définissez la variable d'environnement `JAVA_HOME` comme chemin vers l'emplacement JRE installé.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez Apache Tomcat 8.0 (voir [plus](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPS to PDF"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir PPS vers de nombreux autres formats de fichiers. Voir les autres conversions prises en charge ci-dessous" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-bmp/" name="PPS TO BMP" description="Image bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-fodp/" name="PPS TO FODP" description="Présentation XML plate d'OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-gif/" name="PPS TO GIF" description="Format d'échange graphique" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-html/" name="PPS TO HTML" description="Langage Signalétique Hyper Text" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-jpg/" name="PPS TO JPG" description="Images JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-odp/" name="PPS TO ODP" description="Format de présentation OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-otp/" name="PPS TO OTP" description="Format standard OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-png/" name="PPS TO PNG" description="Portable Network Graphics" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-pot/" name="PPS TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-potm/" name="PPS TO POTM" description="Fichier de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-potx/" name="PPS TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Diaporama compatible avec les macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-pptm/" name="PPS TO PPTM" description="Fichier de présentation prenant en charge les macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Format de présentation XML ouvert" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-svg/" name="PPS TO SVG" description="Image Vectorielle" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-swf/" name="PPS TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Format d'image balisé" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pps-to-xps/" name="PPS TO XPS" description="Spécifications papier XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
