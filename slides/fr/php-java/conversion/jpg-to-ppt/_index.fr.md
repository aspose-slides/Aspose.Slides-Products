---
title: Convertir JPG en PPT en PHP
url: /fr/php-java/conversion/jpg-to-ppt/
keywords: JPG en PPT, Convertir JPG en PPT, API PHP, Bibliothèque PHP, JPG, PPT
description: Convertissez JPG en PPT en PHP. Utilisez l'API PHP de PowerPoint pour convertir les fichiers JPG en PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir JPG en PPT en PHP" h2="Puissante bibliothèque PowerPoint PHP qui aide à développer des applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir JPG en PPT en PHP" %}}

[**Aspose.Slides pour PHP via Java**](https://products.aspose.com/slides/fr/php-java/) est une puissante bibliothèque PHP pour créer et manipuler des fichiers de présentation. De plus, il fournit des moyens flexibles pour convertir JPG en PPT. En utilisant **Aspose.Slides pour PHP via Java**, n'importe quel développeur ou application peut convertir des fichiers JPG en fichiers PPT avec seulement quelques lignes de code PHP.

En tant qu'API de traitement de documents moderne, Aspose.Slides pour PHP exporte rapidement les fichiers JPG vers les formats de fichier PPT. La bibliothèque Aspose PowerPoint vous permet de convertir JPG en PPTs et de nombreux autres formats de fichiers

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir JPG en PPT en utilisant PHP" %}}
Pour convertir le JPG en PPT, vous devrez créer une présentation à partir du fichier JPG et l'enregistrer sous le nom PPT.

{{% blocks/products/pf/agp/code-block title="Code PHP pour convertir JPG en PPT" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.jpg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.ppt", SaveFormat::Ppt);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment convertir JPG en PPT en utilisant Aspose.Slides pour l'API PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour convertir JPG en PPT en PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides pour PHP via Java**](https://products.aspose.com/slides/fr/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers source JPG en PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le résultat en tant que fichier PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertisseur en ligne gratuit" sectionDescription="[Comment convertir PPT en HTML en Python](https://products.aspose.com/slides/fr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir JPG vers d'autres formats pris en charge" subTitle="Vous pouvez également convertir JPG et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/jpg-to-html/" name="JPG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}