---
title: Voeg PDF, PPT, PPTX en vele andere bestandsindelingen samen met PHP
url: /nl/php-java/merger/
keywords: Samenvoegen, Samenvoegen, PowerPoint, Presentatie, PHP, Aspose
description: Voeg meerdere bestanden samen in PHP PPT, PPTX, ODP, PDF, PNG, JPG en nog veel meer.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Voeg Powerpoint, PDF, PPT of andere documenten samen in PHP" h2="Snelle PHP-bibliotheek om PPT, PPTX, PDF, PNG, JPEG en andere formaten samen te voegen." >}}

{{% blocks/products/pf/feature-page-section h2="Voeg PPT, PPTX, PDF samen met PHP" %}}

[**Aspose.Slides voor PHP via Java**](https://products.aspose.com/slides/nl/php-java/) is een krachtige PHP-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om meerdere PPT/PPTX-presentaties te combineren. Wanneer u de ene presentatie met de andere samenvoegt, combineert u in feite hun dia's in één enkele presentatie om één bestand te verkrijgen. Met Aspose.Slides kunt u twee presentaties op verschillende manieren samenvoegen. U kunt presentaties samenvoegen met al hun vormen, stijlen, teksten, opmaak, opmerkingen, animaties, enz. zonder dat u zich zorgen hoeft te maken over verlies van kwaliteit of gegevens.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint-presentaties samenvoegen in PHP" %}}
Om de PowerPoint-presentaties samen te voegen, moet u de dia's van de ene presentatie naar de andere klonen.

{{% blocks/products/pf/agp/code-block title="Voeg PPTX-bestanden samen met PHP" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Presentaties samenvoegen met Aspose.Slides voor PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om twee PPTX-bestanden samen te voegen en het resultaat op te slaan als PDF in PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installeer [**Aspose.Slides voor PHP via Java**](https://docs.aspose.com/slides/php-java/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een bibliotheekreferentie toe (importeer de bibliotheek) aan uw PHP-project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open de bron-PPTX-bestanden in PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Combineer PPTX-bestanden met behulp van de **addClone**-methode.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla de presentatie op en krijg het resultaat als één PDF-bestand.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde indelingen om samen te voegen" subTitle="U kunt ook andere bestandsindelingen combineren. Zie andere ondersteunde formaten hieronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/merger/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/merger/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/merger/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/merger/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/merger/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/merger/potm/" name="POTM" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/merger/potx/" name="POTX" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/merger/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/merger/ppsm/" name="PPSM" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/merger/ppsx/" name="PPSX" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/merger/pptm/" name="PPTM" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/merger/fodp/" name="FODP" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/merger/pdf-to-pdf/" name="PDF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}