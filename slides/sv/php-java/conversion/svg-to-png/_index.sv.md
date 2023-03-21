---
title: Konvertera SVG till PNG i PHP
url: /sv/php-java/conversion/svg-to-png/
keywords: SVG till PNG, Konvertera SVG till PNG, PHP API, PHP Library, SVG, PNG
description: Konvertera SVG till PNG i PHP. Använd PowerPoint PHP API för att konvertera SVG-filer till PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera SVG till PNG i PHP" h2="Kraftfullt PowerPoint PHP-bibliotek som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera SVG till PNG i PHP" %}}

[**Aspose.Slides för PHP via Java**](https://products.aspose.com/slides/sv/php-java/) är ett kraftfullt PHP-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera SVG till PNG. Genom att använda **Aspose.Slides för PHP via Java**, kan vilken utvecklare eller applikation som helst konvertera filer från SVG till PNG med bara några rader PHP-kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för PHP snabbt SVG-filer till PNG-filformat. Aspose PowerPoint-bibliotek låter dig konvertera SVG till PNG och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera SVG till PNG med PHP" %}}
För att konvertera SVG till PNG måste du skapa en presentation från filen SVG och spara den som PNG.

{{% blocks/products/pf/agp/code-block title="PHP-kod för att konvertera SVG till PNG" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.svg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $svgImage = new SvgImage($contents);
    $image = $pres->getImages()->addImage($svgImage);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar SVG till PNG med Aspose.Slides för PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att konvertera SVG till PNG i PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides för PHP via Java**](https://products.aspose.com/slides/sv/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt PHP-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilen SVG i PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som PNG-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Gratis onlinekonverterare" sectionDescription="[Hur man konverterar PPT till HTML i Python](https://products.aspose.com/slides/sv/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera SVG till andra format som stöds" subTitle="Du kan också konvertera SVG och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/svg-to-ppt/" name="SVG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/svg-to-pptx/" name="SVG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}