---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir ODP en FODP en PHP
weight: 230
url: /fr/php-java/conversion/odp-to-fodp/ 
keywords: "Convert, PowerPoint, ODP, FODP, Presentation, PHP"
description: Exemple de code pour la conversion PHP de ODP à FODP. Utilisez l'API PHP PowerPoint pour la conversion par lots de fichiers ODP en fichiers FODP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir ODP en FODP en PHP" h2="Bibliothèque PHP PowerPoint puissante pour convertir ODP en FODP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir ODP en FODP en PHP" %}}

Besoin de convertir des fichiers ODP en FODP par programmation ? En utilisant [*Aspose.Slides pour PHP via Java*](https://products.aspose.com/slides/fr/php-java/), n'importe quel développeur peut convertir le format ODP au format FODP avec seulement quelques lignes de code PHP .

En tant qu'API de traitement de présentation moderne, Aspose.Slides pour PHP crée rapidement FODP à partir de ODP. Testez la qualité de la conversion de ODP à FODP directement dans votre [navigateur](https://products.aspose.app/slides/conversion). La bibliothèque Aspose PowerPoint PPTX vous permet de convertir des fichiers ODP vers de nombreux formats populaires.

Vous pouvez installer la bibliothèque depuis [Composer](https://packagist.org/packages/aspose/slides) à l'aide de la commande suivante :

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Enregistrer ODP sous FODP en PHP" %}}

Utilisez l'application gratuite pour voir une démonstration du processus de conversion de ODP à FODP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cet exemple de code montre la conversion PHP de ODP à FODP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.odp");
try
{
    $pres->save("output.fodp", SaveFormat::Fodp);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir ODP en FODP en PHP" intro="Voici les étapes pour convertir un fichier ODP en FODP en utilisant PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Charger le fichier ODP avec une instance de la classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Appelez la méthode `save` tout en spécifiant le chemin du fichier de sortie et SaveFormat.FODP en tant que paramètres{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Le fichier ODP sera enregistré dans le chemin spécifié{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Configuration requise" intro="Avant d'exécuter l'exemple de code source de conversion PHP, assurez-vous que vous disposez des prérequis suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez PHP 7, ajoutez le chemin vers PHP à la variable système `PATH` et définissez `allow_url_include` sur `On` dans le fichier `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez JRE 8. Définissez la variable d'environnement `JAVA_HOME` comme chemin vers l'emplacement JRE installé.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez Apache Tomcat 8.0 (voir [plus](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert ODP to FODP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir ODP vers de nombreux autres formats de fichiers. Voir les autres conversions prises en charge ci-dessous" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-bmp/" name="ODP TO BMP" description="Image bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-gif/" name="ODP TO GIF" description="Format d'échange graphique" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-html/" name="ODP TO HTML" description="Langage Signalétique Hyper Text" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-jpg/" name="ODP TO JPG" description="Images JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-otp/" name="ODP TO OTP" description="Format standard OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-pdf/" name="ODP TO PDF" description="Portable Document Format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-png/" name="ODP TO PNG" description="Portable Network Graphics" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-pot/" name="ODP TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-potm/" name="ODP TO POTM" description="Fichier de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-potx/" name="ODP TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-pps/" name="ODP TO PPS" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Diaporama compatible avec les macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Fichier de présentation prenant en charge les macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Format de présentation XML ouvert" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-svg/" name="ODP TO SVG" description="Image Vectorielle" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-swf/" name="ODP TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Format d'image balisé" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/php-java/conversion/odp-to-xps/" name="ODP TO XPS" description="Spécifications papier XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
