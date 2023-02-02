---
title: Konvertera PDF till XML i PHP
url: /sv/php-java/conversion/pdf-to-xml/
keywords: PDF till XML, Konvertera PDF till XML, PHP API, PHP Library, PDF, XML
description: Konvertera PDF till XML i PHP. Använd PowerPoint PHP API för att konvertera PDF-filer till XML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera PDF till XML i PHP" h2="Kraftfullt PowerPoint PHP-bibliotek som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera PDF till XML i PHP" %}}

[**Aspose.Slides för PHP via Java**](https://products.aspose.com/slides/sv/php-java/) är ett kraftfullt PHP-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera PDF till XML. Genom att använda **Aspose.Slides för PHP via Java**, kan vilken utvecklare eller applikation som helst konvertera filer från PDF till XML med bara några rader PHP-kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för PHP snabbt PDF-filer till XML-filformat. Aspose PowerPoint-bibliotek låter dig konvertera PDF till XML och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera PDF till XML med PHP" %}}
För att konvertera PDF till XML måste du skapa en presentation från filen PDF och spara den som XML.

{{% blocks/products/pf/agp/code-block title="PHP-kod för att konvertera PDF till XML" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $slide = $pres->getSlides()->get_Item($i);
        $javafos = new Java("java.io.FileOutputStream", "slide_". $i .".xml");
        $slide->writeAsSvg($javafos);
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

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar PDF till XML med Aspose.Slides för PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att konvertera PDF till XML i PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides för PHP via Java**](https://products.aspose.com/slides/sv/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt PHP-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilen PDF i PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som XML-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera PDF till andra format som stöds" subTitle="Du kan också konvertera PDF och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}