---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PPTX en PPS en PHP
weight: 2650
url: /fr/php-java/conversion/pptx-to-pps/ 
keywords: "Convert, PowerPoint, PPTX, PPS, Presentation, PHP"
description: Exemple de code pour la conversion PHP de PPTX à PPS. Utilisez l'API PHP PowerPoint pour la conversion par lots de fichiers PPTX en fichiers PPS.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PPTX en PPS en PHP" h2="Bibliothèque PHP PowerPoint puissante pour convertir PPTX en PPS"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PPTX en PPS en PHP" %}}

Besoin de convertir des fichiers PPTX en PPS par programmation ? En utilisant [*Aspose.Slides pour PHP via Java*](https://products.aspose.com/slides/fr/php-java/), n'importe quel développeur peut convertir le format PPTX au format PPS avec seulement quelques lignes de code PHP .

En tant qu'API de traitement de présentation moderne, Aspose.Slides pour PHP crée rapidement PPS à partir de PPTX. Testez la qualité de la conversion de PPTX à PPS directement dans votre [navigateur](https://products.aspose.app/slides/conversion). La bibliothèque Aspose PowerPoint PPTX vous permet de convertir des fichiers PPTX vers de nombreux formats populaires.

Vous pouvez installer la bibliothèque depuis [Composer](https://packagist.org/packages/aspose/slides) à l'aide de la commande suivante :

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Enregistrer PPTX sous PPS en PHP" %}}

Utilisez l'application gratuite pour voir une démonstration du processus de conversion de PPTX à PPS.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cet exemple de code montre la conversion PHP de PPTX à PPS" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptx");
try
{
    $pres->save("output.pps", SaveFormat::Pps);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir PPTX en PPS en PHP" intro="Voici les étapes pour convertir un fichier PPTX en PPS en utilisant PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Charger le fichier PPTX avec une instance de la classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode `save` tout en spécifiant le chemin du fichier de sortie et SaveFormat.PPS en tant que paramètres{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Le fichier PPTX sera enregistré dans le chemin spécifié{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Configuration requise" intro="Avant d'exécuter l'exemple de code source de conversion PHP, assurez-vous que vous disposez des prérequis suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez PHP 7, ajoutez le chemin vers PHP à la variable système `PATH` et définissez `allow_url_include` sur `On` dans le fichier `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez JRE 8. Définissez la variable d'environnement `JAVA_HOME` comme chemin vers l'emplacement JRE installé.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez Apache Tomcat 8.0 (voir [plus](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPTX to PPS"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir PPTX vers de nombreux autres formats de fichiers. Voir les autres conversions prises en charge ci-dessous" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Image bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-fodp/" name="PPTX TO FODP" description="Présentation XML plate d'OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Format d'échange graphique" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-html/" name="PPTX TO HTML" description="Langage Signalétique Hyper Text" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-jpg/" name="PPTX TO JPG" description="Images JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-odp/" name="PPTX TO ODP" description="Format de présentation OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-otp/" name="PPTX TO OTP" description="Format standard OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Portable Document Format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-png/" name="PPTX TO PNG" description="Portable Network Graphics" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-pot/" name="PPTX TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Fichier de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Diaporama compatible avec les macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Fichier de présentation prenant en charge les macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Image Vectorielle" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-swf/" name="PPTX TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Format d'image balisé" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/pptx-to-xps/" name="PPTX TO XPS" description="Spécifications papier XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
