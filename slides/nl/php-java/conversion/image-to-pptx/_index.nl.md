---
title: Converteer Image naar PPTX in PHP
url: /nl/php-java/conversion/image-to-pptx/
keywords: Image naar PPTX, Converteer Image naar PPTX, PHP API, PHP Library, Image, PPTX
description: Converteer Image naar PPTX in PHP. Gebruik PowerPoint PHP API om Image bestanden te converteren naar PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converteer Image naar PPTX in PHP" h2="Krachtige PowerPoint PHP-bibliotheek die helpt bij het ontwikkelen van toepassingen met de mogelijkheid om Microsoft PowerPoint- en OpenOffice-presentatiebestanden te maken, samen te voegen, te inspecteren of te converteren zonder het gebruik van software zoals Microsoft of Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converteer Image naar PPTX in PHP" %}}

[**Aspose.Slides voor PHP via Java**](https://products.aspose.com/slides/nl/php-java/) is een krachtige PHP-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om Image naar PPTX te converteren. Met behulp van **Aspose.Slides voor PHP via Java** kan elke ontwikkelaar of toepassing Image naar PPTX bestanden converteren met slechts een paar regels PHP-code.

Aspose.Slides voor PHP is een moderne documentverwerkings-API en exporteert snel Image-bestanden naar PPTX-bestandsindelingen. Met de Aspose PowerPoint-bibliotheek kunt u Image naar PPTXs en vele andere bestandsindelingen converteren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer Image naar PPTX met behulp van PHP" %}}
Om de Image naar PPTX te converteren, moet u een presentatie maken van het Image-bestand en deze opslaan als PPTX.

{{% blocks/products/pf/agp/code-block title="PHP-code voor het converteren van Image naar PPTX" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.png';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.pptx", SaveFormat::Pptx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hoe Image naar PPTX te converteren met Aspose.Slides voor PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om Image naar PPTX in PHP te converteren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installeer [**Aspose.Slides voor PHP via Java**](https://products.aspose.com/slides/nl/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een bibliotheekreferentie toe (importeer de bibliotheek) aan uw PHP-project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open de bronbestanden Image in PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op als PPTX bestand.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Gratis online converter" sectionDescription="[Hoe PPT naar HTML in Python te converteren](https://products.aspose.com/slides/nl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converteer Image naar andere ondersteunde formaten" subTitle="U kunt Image ook converteren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/image-to-html/" name="IMAGE TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}