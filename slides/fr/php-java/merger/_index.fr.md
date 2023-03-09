---
title: Fusionnez PDF, PPT, PPTX et de nombreux autres formats de fichiers à l'aide de PHP
url: /fr/php-java/merger/
keywords: Fusionner, Joindre, PowerPoint, Présentation, PHP, Aspose
description: Fusionnez plusieurs fichiers en PHP PPT, PPTX, ODP, PDF, PNG, JPG et bien d'autres.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Fusionnez Powerpoint, PDF, PPT ou d'autres documents ensemble en PHP" h2="Bibliothèque PHP haute vitesse pour fusionner les formats PPT, PPTX, PDF, PNG, JPEG et autres." >}}

{{% blocks/products/pf/feature-page-section h2="Fusionner PPT, PPTX, PDF en utilisant PHP" %}}

[**Aspose.Slides pour PHP via Java**](https://products.aspose.com/slides/fr/php-java/) est une puissante bibliothèque PHP pour créer et manipuler des fichiers de présentation. De plus, il offre des moyens flexibles de combiner plusieurs présentations PPT/PPTX. Lorsque vous fusionnez une présentation avec une autre, vous combinez efficacement leurs diapositives dans une seule présentation pour obtenir un fichier. Aspose.Slides vous permet de fusionner deux présentations de différentes manières. Vous pouvez fusionner des présentations avec toutes leurs formes, styles, textes, mises en forme, commentaires, animations, etc. sans avoir à vous soucier de la perte de qualité ou de données.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Fusionner des présentations PowerPoint en PHP" %}}
Pour fusionner les présentations PowerPoint, vous devrez cloner les diapositives d'une présentation à l'autre.

{{% blocks/products/pf/agp/code-block title="Fusionner des fichiers PPTX en utilisant PHP" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres1 = new Presentation("document1.ppt");
$pres2 = new Presentation("document2.ppt");
try
{
    for ($i = 0; $i < java_values($pres2->getSlides()->size()); $i++) 
    {
        $pres1->getSlides()->addClone($pres2->getSlides()->get_Item($i));
    }

    $pres1->save("merged.ppt", SaveFormat::Ppt);
}
finally
{
    if ($pres1 != null) $pres1->dispose();
    if ($pres2 != null) $pres2->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment fusionner des présentations à l'aide d'Aspose.Slides pour l'API PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour fusionner deux fichiers PPTX et enregistrer le résultat au format PDF en PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides pour PHP via Java**](https://docs.aspose.com/slides/php-java/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers PPTX source en PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combinez les fichiers PPTX à l'aide de la méthode **addClone**.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez la présentation et obtenez le résultat sous forme de fichier PDF unique.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats pris en charge à fusionner" subTitle="Vous pouvez également combiner d'autres formats de fichiers. Voir les autres formats pris en charge ci-dessous." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/merger/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/merger/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/merger/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/merger/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/merger/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/merger/potm/" name="POTM" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/merger/potx/" name="POTX" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/merger/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/merger/ppsm/" name="PPSM" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/merger/ppsx/" name="PPSX" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/merger/pptm/" name="PPTM" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/merger/fodp/" name="FODP" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/php-java/merger/pdf-to-pdf/" name="PDF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}