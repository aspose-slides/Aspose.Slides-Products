---
title: Upravte PPS v PHP
url: /cs/php-java/editor/pps/
keywords: Upravit PPS, Upravit PowerPoint, PPS, PowerPoint, PHP API, PHP Library
description: Upravte PPS v PHP. K úpravě souborů PPS použijte API knihovny PHP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Upravte PPS v PHP" h2="Vysokorychlostní a multiplatformní PHP knihovna pro editaci PPS pomocí PHP kódu" >}}

{{% blocks/products/pf/feature-page-section h2="Upravte PPS pomocí Aspose.Slides" %}}

[**Aspose.Slides pro PHP přes Javu**](https://products.aspose.com/slides/cs/php-java/) je výkonná PHP knihovna pro rychlou a snadnou úpravu prezentací. Poskytuje uživatelům širokou škálu funkcí, které jim pomohou vytvořit profesionálně vypadající snímky během okamžiku. S Aspose mohou uživatelé upravovat text, přidávat obrázky, animace a přechody do své prezentace a také používat různé možnosti formátování, jako je typ písma a výběr barev. Knihovna navíc nabízí podporu pro soubory PowerPoint (PPT) i formáty OpenOffice Presentation (ODP), což usnadňuje sdílení prezentací na různých platformách bez jakýchkoli problémů s kompatibilitou. Využitím výkonu knihovny Aspose při vytváření nebo úpravách vaší další prezentace budete mít jistotu, že vaše snímky budou pokaždé vypadat skvěle!
Soubor PPS můžete upravit přidáním nového řádku textu. 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Upravte PPS v PHP" %}}
Pomocí [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/cs/php-java/) můžete přidat nový řádek textu do dokumentu PPS pouhým několik řádků kódu.

{{% blocks/products/pf/agp/code-block title="PHP kód pro úpravu PPS" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Jak upravit PPS v PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte **Aspose.Slides pro PHP přes Java**. Viz [**Instalace**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte knihovnu jako referenci do svého projektu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvořte instanci třídy Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte prezentaci PPS, kterou chcete upravit.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte nový řádek textu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte změněný soubor.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Upravte další soubory" subTitle="Můžete také upravovat soubory v jiných formátech" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}