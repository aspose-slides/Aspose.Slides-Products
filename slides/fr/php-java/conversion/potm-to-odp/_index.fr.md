---
title: Convertir POTM en ODP en PHP
weight: 1110
url: /fr/php-java/conversion/potm-to-odp/ 
keywords: "Convert, PowerPoint, POTM, ODP, Presentation, PHP"
description: Exemple de code pour la conversion PHP de POTM à ODP. Utilisez l'API PHP PowerPoint pour la conversion par lots de fichiers POTM en fichiers ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir POTM en ODP en PHP" h2="Bibliothèque PHP PowerPoint puissante pour convertir POTM en ODP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Convertir POTM en ODP en PHP" %}}

Besoin de convertir des fichiers POTM en ODP par programmation ? En utilisant [*Aspose.Slides pour PHP via Java*](https://products.aspose.com/slides/fr/php-java/), n'importe quel développeur peut convertir le format POTM au format ODP avec seulement quelques lignes de code PHP .

En tant qu'API de traitement de présentation moderne, Aspose.Slides pour PHP crée rapidement ODP à partir de POTM. Testez la qualité de la conversion de POTM à ODP directement dans votre [navigateur](https://products.aspose.app/slides/conversion). La bibliothèque Aspose PowerPoint PPTX vous permet de convertir des fichiers POTM vers de nombreux formats populaires.

Vous pouvez installer la bibliothèque depuis [Composer](https://packagist.org/packages/aspose/slides) à l'aide de la commande suivante :

{{% blocks/products/pf/agp/code-block title="Console/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Comment convertir POTM en ODP en PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour convertir un fichier POTM en ODP en utilisant PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Charger le fichier POTM avec une instance de la classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Appelez la méthode `save` tout en spécifiant le chemin du fichier de sortie et SaveFormat.ODP en tant que paramètres
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Le fichier POTM sera enregistré dans le chemin spécifié
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Avant d'exécuter l'exemple de code source de conversion PHP, assurez-vous que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

1. Installez PHP 7, ajoutez le chemin vers PHP à la variable système `PATH` et définissez `allow_url_include` sur `On` dans le fichier `php.ini`.
1. Installez JRE 8. Définissez la variable d'environnement `JAVA_HOME` comme chemin vers l'emplacement JRE installé.
1. Installez Apache Tomcat 8.0 (voir [plus](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cet exemple de code montre la conversion PHP de POTM à ODP" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potm");
try
{
    $pres->save("output.odp", SaveFormat::Odp);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Enregistrer POTM sous ODP en PHP" %}}
Utilisez l'application gratuite pour voir une démonstration du processus de conversion de POTM à ODP. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert POTM to ODP" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir POTM vers de nombreux autres formats de fichiers. Voir les autres conversions prises en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-bmp/" name="POTM TO BMP" description="Image bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-fodp/" name="POTM TO FODP" description="Présentation XML plate d'OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-gif/" name="POTM TO GIF" description="Format d'échange graphique" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-html/" name="POTM TO HTML" description="Langage Signalétique Hyper Text" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-jpg/" name="POTM TO JPG" description="Images JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-otp/" name="POTM TO OTP" description="Format standard OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-pdf/" name="POTM TO PDF" description="Portable Document Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-png/" name="POTM TO PNG" description="Portable Network Graphics" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-pot/" name="POTM TO POT" description="Fichiers de modèle Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-potx/" name="POTM TO POTX" description="Modèle de présentation Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-pps/" name="POTM TO PPS" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Diaporama compatible avec les macros" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="Diaporama PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Fichier de présentation prenant en charge les macros" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Format de présentation XML ouvert" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-svg/" name="POTM TO SVG" description="Image Vectorielle" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-swf/" name="POTM TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Format d'image balisé" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/potm-to-xps/" name="POTM TO XPS" description="Spécifications papier XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}