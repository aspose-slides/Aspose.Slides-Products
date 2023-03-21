---
title: Convertir PDF en JPG en PHP
url: /fr/php-java/conversion/pdf-to-jpg/
keywords: PDF en JPG, Convertir PDF en JPG, API PHP, Bibliothèque PHP, PDF, JPG
description: Convertissez PDF en JPG en PHP. Utilisez l'API PHP de PowerPoint pour convertir les fichiers PDF en JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir PDF en JPG en PHP" h2="Puissante bibliothèque PowerPoint PHP qui aide à développer des applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir PDF en JPG en PHP" %}}

[**Aspose.Slides pour PHP via Java**](https://products.aspose.com/slides/fr/php-java/) est une puissante bibliothèque PHP pour créer et manipuler des fichiers de présentation. De plus, il fournit des moyens flexibles pour convertir PDF en JPG. En utilisant **Aspose.Slides pour PHP via Java**, n'importe quel développeur ou application peut convertir des fichiers PDF en fichiers JPG avec seulement quelques lignes de code PHP.

En tant qu'API de traitement de documents moderne, Aspose.Slides pour PHP exporte rapidement les fichiers PDF vers les formats de fichier JPG. La bibliothèque Aspose PowerPoint vous permet de convertir PDF en JPGs et de nombreux autres formats de fichiers

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir PDF en JPG en utilisant PHP" %}}
Pour convertir le PDF en JPG, vous devrez créer une présentation à partir du fichier PDF et l'enregistrer sous le nom JPG.

{{% blocks/products/pf/agp/code-block title="Code PHP pour convertir PDF en JPG" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment convertir PDF en JPG en utilisant Aspose.Slides pour l'API PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour convertir PDF en JPG en PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides pour PHP via Java**](https://products.aspose.com/slides/fr/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers source PDF en PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le résultat en tant que fichier JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertisseur en ligne gratuit" sectionDescription="[Comment convertir PPT en HTML en Python](https://products.aspose.com/slides/fr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir PDF vers d'autres formats pris en charge" subTitle="Vous pouvez également convertir PDF et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/pdf-to-xml/" name="PDF TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}