---
lastmod: 2023-02-06
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Bewerk PPSX in PHP
url: /nl/php-java/editor/ppsx/
keywords: Bewerk PPSX, Bewerk PowerPoint, PPSX, PowerPoint, PHP API, PHP Library
description: Bewerk PPSX in PHP. Gebruik de PHP-bibliotheek-API om PPSX-bestanden te bewerken
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bewerk PPSX in PHP" h2="Snelle en platformonafhankelijke PHP-bibliotheek voor het bewerken van PPSX met behulp van PHP-code" related="FODP,HTML,ODP,OTP,PDF,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Bewerk PPSX in PHP" variant="code" %}}

Met behulp van [**Aspose.Slides voor PHP via Java**](https://products.aspose.com/slides/nl/php-java/), kunt u een nieuwe regel tekst toevoegen aan het PPSX-document met slechts een paar regels code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP-code voor het bewerken van PPSX" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsx");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.ppsx", SaveFormat::Ppsx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Bewerk PPSX met Aspose.Slides" %}}

[**Aspose.Slides voor PHP via Java**](https://products.aspose.com/slides/nl/php-java/) is een krachtige PHP-bibliotheek voor het snel en gemakkelijk bewerken van presentaties. Het biedt gebruikers een uitgebreid scala aan functies waarmee ze in een mum van tijd professioneel ogende dia's kunnen maken. Met Aspose kunnen gebruikers tekst bewerken, afbeeldingen, animaties en overgangen aan hun presentatie toevoegen en verschillende opmaakopties toepassen, zoals lettertype en kleurselectie. Bovendien biedt de bibliotheek ondersteuning voor zowel PowerPoint-bestanden (PPT) als OpenOffice Presentation-indelingen (ODP), waardoor het gemakkelijker dan ooit is om presentaties op verschillende platforms te delen zonder dat er compatibiliteitsproblemen optreden. Door gebruik te maken van de kracht van de Aspose-bibliotheek bij het maken of bewerken van uw volgende presentatie, weet u zeker dat uw dia's er elke keer geweldig uitzien!
U kunt een PPSX-bestand bewerken door er een nieuwe regel tekst aan toe te voegen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe PPSX in PHP te bewerken" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer **Aspose.Slides voor PHP via Java**. Zie [**Installatie**](https://docs.aspose.com/slides/php-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg de bibliotheek toe als referentie in uw project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Maak een instantie van de klasse Presentatie.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laad de PPSX presentatie die je wilt bewerken.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg een nieuwe regel tekst toe.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla het gewijzigde bestand op.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Gebouwd met Aspose.Slides" title="PPTX-bestanden online bewerken" description="De gratis app Aspose.Slides Editor is gebouwd met [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/nl/php-java/), dezelfde API als in de bovenstaande code. Open de app en ontdek wat de API kan met uw eigen PPTX-bestanden." button="Aspose.Slides Editor openen" note="[Alle gratis apps](https://products.aspose.app/slides/family)" >}}
- Werkt in uw browser, niets te installeren.
- Zie hoe Aspose.Slides uw bestanden verwerkt voordat u code schrijft.
- Upload uw PPTX-bestanden en bewerk ze direct.
- Sla het bewerkte bestand op en download het.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Bewerk andere bestanden" subTitle="U kunt ook bestanden in andere indelingen bewerken" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/php-java/editor/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
