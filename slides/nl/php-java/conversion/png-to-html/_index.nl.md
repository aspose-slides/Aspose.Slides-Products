---
title: Converteer PNG naar HTML in PHP
url: /nl/php-java/conversion/png-to-html/
keywords: PNG naar HTML, Converteer PNG naar HTML, PHP API, PHP Library, PNG, HTML
description: Converteer PNG naar HTML in PHP. Gebruik PowerPoint PHP API om PNG bestanden te converteren naar HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converteer PNG naar HTML in PHP" h2="Krachtige PowerPoint PHP-bibliotheek die helpt bij het ontwikkelen van toepassingen met de mogelijkheid om Microsoft PowerPoint- en OpenOffice-presentatiebestanden te maken, samen te voegen, te inspecteren of te converteren zonder het gebruik van software zoals Microsoft of Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converteer PNG naar HTML in PHP" %}}

[**Aspose.Slides voor PHP via Java**](https://products.aspose.com/slides/nl/php-java/) is een krachtige PHP-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om PNG naar HTML te converteren. Met behulp van **Aspose.Slides voor PHP via Java** kan elke ontwikkelaar of toepassing PNG naar HTML bestanden converteren met slechts een paar regels PHP-code.

Aspose.Slides voor PHP is een moderne documentverwerkings-API en exporteert snel PNG-bestanden naar HTML-bestandsindelingen. Met de Aspose PowerPoint-bibliotheek kunt u PNG naar HTMLs en vele andere bestandsindelingen converteren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer PNG naar HTML met behulp van PHP" %}}
Om de PNG naar HTML te converteren, moet u een presentatie maken van het PNG-bestand en deze opslaan als HTML.

{{% blocks/products/pf/agp/code-block title="PHP-code voor het converteren van PNG naar HTML" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Hoe PNG naar HTML te converteren met Aspose.Slides voor PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om PNG naar HTML in PHP te converteren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installeer [**Aspose.Slides voor PHP via Java**](https://products.aspose.com/slides/nl/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een bibliotheekreferentie toe (importeer de bibliotheek) aan uw PHP-project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open de bronbestanden PNG in PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op als HTML bestand.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converteer PNG naar andere ondersteunde formaten" subTitle="U kunt PNG ook converteren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}