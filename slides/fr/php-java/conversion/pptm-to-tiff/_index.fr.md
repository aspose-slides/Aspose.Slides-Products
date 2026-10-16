---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PPTM en TIFF en PHP
weight: 2510
url: /fr/php-java/conversion/pptm-to-tiff/ 
keywords: "Convert, PowerPoint, PPTM, TIFF, Presentation, PHP"
description: Exemple de code pour la conversion PHP de PPTM à TIFF. Utilisez l'API PHP PowerPoint pour la conversion par lots de fichiers PPTM en fichiers TIFF.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PPTM en TIFF en PHP" h2="Bibliothèque PHP PowerPoint puissante pour convertir PPTM en TIFF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PPTM en TIFF en PHP" %}}

Besoin de convertir des fichiers PPTM en TIFF par programmation ? En utilisant [*Aspose.Slides pour PHP via Java*](https://products.aspose.com/slides/fr/php-java/), n'importe quel développeur peut convertir le format PPTM au format TIFF avec seulement quelques lignes de code PHP .

En tant qu'API de traitement de présentation moderne, Aspose.Slides pour PHP crée rapidement TIFF à partir de PPTM. Testez la qualité de la conversion de PPTM à TIFF directement dans votre [navigateur](https://products.aspose.app/slides/conversion). La bibliothèque Aspose PowerPoint PPTX vous permet de convertir des fichiers PPTM vers de nombreux formats populaires.

Vous pouvez installer la bibliothèque depuis [Composer](https://packagist.org/packages/aspose/slides) à l'aide de la commande suivante :

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Enregistrer PPTM sous TIFF en PHP" %}}

Utilisez l'application gratuite pour voir une démonstration du processus de conversion de PPTM à TIFF.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cet exemple de code montre la conversion PHP de PPTM à TIFF" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptm");
try
{
    $pres->save("output.tiff", SaveFormat::Tiff);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir PPTM en TIFF en PHP" intro="Voici les étapes pour convertir un fichier PPTM en TIFF en utilisant PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Charger le fichier PPTM avec une instance de la classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode `save` tout en spécifiant le chemin du fichier de sortie et SaveFormat.TIFF en tant que paramètres{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Le fichier PPTM sera enregistré dans le chemin spécifié{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Configuration requise" intro="Avant d'exécuter l'exemple de code source de conversion PHP, assurez-vous que vous disposez des prérequis suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez PHP 7, ajoutez le chemin vers PHP à la variable système `PATH` et définissez `allow_url_include` sur `On` dans le fichier `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez JRE 8. Définissez la variable d'environnement `JAVA_HOME` comme chemin vers l'emplacement JRE installé.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez Apache Tomcat 8.0 (voir [plus](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPTM to TIFF"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir PPTM vers de nombreux autres formats de fichiers. Voir les autres conversions prises en charge ci-dessous" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Image bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" description="Présentation XML plate d'OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Format d'échange graphique" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-html/" name="PPTM TO HTML" description="Langage Signalétique Hyper Text" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" description="Images JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="Format de présentation OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="Format standard OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Portable Document Format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-png/" name="PPTM TO PNG" description="Portable Network Graphics" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-pot/" name="PPTM TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Fichier de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Diaporama compatible avec les macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="Format de présentation XML ouvert" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="Image Vectorielle" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="Spécifications papier XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
