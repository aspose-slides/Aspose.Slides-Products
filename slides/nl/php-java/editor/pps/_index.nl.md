---
title: Bewerk PPS in PHP
url: /nl/php-java/editor/pps/
keywords: Bewerk PPS, Bewerk PowerPoint, PPS, PowerPoint, PHP API, PHP Library
description: Bewerk PPS in PHP. Gebruik de PHP-bibliotheek-API om PPS-bestanden te bewerken
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Bewerk PPS in PHP" h2="Snelle en platformonafhankelijke PHP-bibliotheek voor het bewerken van PPS met behulp van PHP-code" >}}

{{% blocks/products/pf/feature-page-section h2="Bewerk PPS met Aspose.Slides" %}}

[**Aspose.Slides voor PHP via Java**](https://products.aspose.com/slides/nl/php-java/) is een krachtige PHP-bibliotheek voor het snel en gemakkelijk bewerken van presentaties. Het biedt gebruikers een uitgebreid scala aan functies waarmee ze in een mum van tijd professioneel ogende dia's kunnen maken. Met Aspose kunnen gebruikers tekst bewerken, afbeeldingen, animaties en overgangen aan hun presentatie toevoegen en verschillende opmaakopties toepassen, zoals lettertype en kleurselectie. Bovendien biedt de bibliotheek ondersteuning voor zowel PowerPoint-bestanden (PPT) als OpenOffice Presentation-indelingen (ODP), waardoor het gemakkelijker dan ooit is om presentaties op verschillende platforms te delen zonder dat er compatibiliteitsproblemen optreden. Door gebruik te maken van de kracht van de Aspose-bibliotheek bij het maken of bewerken van uw volgende presentatie, weet u zeker dat uw dia's er elke keer geweldig uitzien!
U kunt een PPS-bestand bewerken door er een nieuwe regel tekst aan toe te voegen. 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Bewerk PPS in PHP" %}}
Met behulp van [**Aspose.Slides voor PHP via Java**](https://products.aspose.com/slides/nl/php-java/), kunt u een nieuwe regel tekst toevoegen aan het PPS-document met slechts een paar regels code.

{{% blocks/products/pf/agp/code-block title="PHP-code voor het bewerken van PPS" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pps");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.pps", SaveFormat::Pps);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hoe PPS in PHP te bewerken" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installeer **Aspose.Slides voor PHP via Java**. Zie [**Installatie**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg de bibliotheek toe als referentie in uw project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Maak een instantie van de klasse Presentatie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad de PPS presentatie die je wilt bewerken.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een nieuwe regel tekst toe.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla het gewijzigde bestand op.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Bewerk andere bestanden" subTitle="U kunt ook bestanden in andere indelingen bewerken" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}