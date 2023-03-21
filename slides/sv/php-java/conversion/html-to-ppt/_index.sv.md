---
title: Konvertera HTML till PPT i PHP
url: /sv/php-java/conversion/html-to-ppt/
keywords: HTML till PPT, Konvertera HTML till PPT, PHP API, PHP Library, HTML, PPT
description: Konvertera HTML till PPT i PHP. Använd PowerPoint PHP API för att konvertera HTML-filer till PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera HTML till PPT i PHP" h2="Kraftfullt PowerPoint PHP-bibliotek som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera HTML till PPT i PHP" %}}

[**Aspose.Slides för PHP via Java**](https://products.aspose.com/slides/sv/php-java/) är ett kraftfullt PHP-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera HTML till PPT. Genom att använda **Aspose.Slides för PHP via Java**, kan vilken utvecklare eller applikation som helst konvertera filer från HTML till PPT med bara några rader PHP-kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för PHP snabbt HTML-filer till PPT-filformat. Aspose PowerPoint-bibliotek låter dig konvertera HTML till PPT och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera HTML till PPT med PHP" %}}
För att konvertera HTML till PPT måste du skapa en presentation från filen HTML och spara den som PPT.

{{% blocks/products/pf/agp/code-block title="PHP-kod för att konvertera HTML till PPT" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
        
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $filename = 'file.html';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $pres->getSlides()->addFromHtml($contents);        
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

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar HTML till PPT med Aspose.Slides för PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att konvertera HTML till PPT i PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides för PHP via Java**](https://products.aspose.com/slides/sv/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt PHP-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilen HTML i PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som PPT-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Gratis onlinekonverterare" sectionDescription="[Hur man konverterar PPT till HTML i Python](https://products.aspose.com/slides/sv/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera HTML till andra format som stöds" subTitle="Du kan också konvertera HTML och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}