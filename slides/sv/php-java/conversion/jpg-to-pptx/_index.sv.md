---
title: Konvertera JPG till PPTX i PHP
url: /sv/php-java/conversion/jpg-to-pptx/
keywords: JPG till PPTX, Konvertera JPG till PPTX, PHP API, PHP Library, JPG, PPTX
description: Konvertera JPG till PPTX i PHP. Använd PowerPoint PHP API för att konvertera JPG-filer till PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera JPG till PPTX i PHP" h2="Kraftfullt PowerPoint PHP-bibliotek som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera JPG till PPTX i PHP" %}}

[**Aspose.Slides för PHP via Java**](https://products.aspose.com/slides/sv/php-java/) är ett kraftfullt PHP-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera JPG till PPTX. Genom att använda **Aspose.Slides för PHP via Java**, kan vilken utvecklare eller applikation som helst konvertera filer från JPG till PPTX med bara några rader PHP-kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för PHP snabbt JPG-filer till PPTX-filformat. Aspose PowerPoint-bibliotek låter dig konvertera JPG till PPTX och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera JPG till PPTX med PHP" %}}
För att konvertera JPG till PPTX måste du skapa en presentation från filen JPG och spara den som PPTX.

{{% blocks/products/pf/agp/code-block title="PHP-kod för att konvertera JPG till PPTX" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.jpg';
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

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar JPG till PPTX med Aspose.Slides för PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att konvertera JPG till PPTX i PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides för PHP via Java**](https://products.aspose.com/slides/sv/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt PHP-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilen JPG i PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som PPTX-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera JPG till andra format som stöds" subTitle="Du kan också konvertera JPG och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/jpg-to-html/" name="JPG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/php-java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}