---
title: Convertir SVG en PNG en PHP
url: /fr/php-java/conversion/svg-to-png/
keywords: SVG en PNG, Convertir SVG en PNG, API PHP, Bibliothèque PHP, SVG, PNG
description: Convertissez SVG en PNG en PHP. Utilisez l'API PHP de PowerPoint pour convertir les fichiers SVG en PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir SVG en PNG en PHP" h2="Puissante bibliothèque PowerPoint PHP qui aide à développer des applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir SVG en PNG en PHP" %}}

[**Aspose.Slides pour PHP via Java**](https://products.aspose.com/slides/fr/php-java/) est une puissante bibliothèque PHP pour créer et manipuler des fichiers de présentation. De plus, il fournit des moyens flexibles pour convertir SVG en PNG. En utilisant **Aspose.Slides pour PHP via Java**, n'importe quel développeur ou application peut convertir des fichiers SVG en fichiers PNG avec seulement quelques lignes de code PHP.

En tant qu'API de traitement de documents moderne, Aspose.Slides pour PHP exporte rapidement les fichiers SVG vers les formats de fichier PNG. La bibliothèque Aspose PowerPoint vous permet de convertir SVG en PNGs et de nombreux autres formats de fichiers

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir SVG en PNG en utilisant PHP" %}}
Pour convertir le SVG en PNG, vous devrez créer une présentation à partir du fichier SVG et l'enregistrer sous le nom PNG.

{{% blocks/products/pf/agp/code-block title="Code PHP pour convertir SVG en PNG" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.svg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $svgImage = new SvgImage($contents);
    $image = $pres->getImages()->addImage($svgImage);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".png");
        $imageio->write($bmp, "PNG", $javafile);
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

{{< blocks/products/pf/feature-page-section  h2="Comment convertir SVG en PNG en utilisant Aspose.Slides pour l'API PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour convertir SVG en PNG en PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides pour PHP via Java**](https://products.aspose.com/slides/fr/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers source SVG en PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le résultat en tant que fichier PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertisseur en ligne gratuit" sectionDescription="[Comment convertir PPT en HTML en Python](https://products.aspose.com/slides/fr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir SVG vers d'autres formats pris en charge" subTitle="Vous pouvez également convertir SVG et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/svg-to-ppt/" name="SVG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/conversion/svg-to-pptx/" name="SVG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}