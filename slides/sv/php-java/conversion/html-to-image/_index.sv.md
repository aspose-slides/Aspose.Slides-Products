---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera HTML till Image i PHP
url: /sv/php-java/conversion/html-to-image/
keywords: HTML till Image, Konvertera HTML till Image, PHP API, PHP Library, HTML, Image
description: Konvertera HTML till Image i PHP. Använd PowerPoint PHP API för att konvertera HTML-filer till Image
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera HTML till Image i PHP" h2="Kraftfullt PowerPoint PHP-bibliotek som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera HTML till Image med PHP" variant="code" %}}

För att konvertera HTML till Image måste du skapa en presentation från filen HTML och spara den som Image.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP-kod för att konvertera HTML till Image" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera HTML till Image i PHP" %}}

[**Aspose.Slides för PHP via Java**](https://products.aspose.com/slides/sv/php-java/) är ett kraftfullt PHP-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera HTML till Image. Genom att använda **Aspose.Slides för PHP via Java**, kan vilken utvecklare eller applikation som helst konvertera filer från HTML till Image med bara några rader PHP-kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för PHP snabbt HTML-filer till Image-filformat. Aspose PowerPoint-bibliotek låter dig konvertera HTML till Image och många andra filformat

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man konverterar HTML till Image med Aspose.Slides för PHP API" intro="Det här är stegen för att konvertera HTML till Image i PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera [**Aspose.Slides för PHP via Java**](https://products.aspose.com/slides/sv/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till en biblioteksreferens (importera biblioteket) till ditt PHP-projekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öppna källfilen HTML i PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara resultatet som Image-fil.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis onlinekonverterare"
  description="[Hur man konverterar PPT till HTML i Python](https://products.aspose.com/slides/sv/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konvertera HTML till andra format som stöds" subTitle="Du kan också konvertera HTML och spara till andra filformat. Se alla format som stöds nedan" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/html-to-xml/" name="HTML TO XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
