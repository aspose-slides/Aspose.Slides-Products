---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera Image till PPTX i PHP
url: /sv/php-java/conversion/image-to-pptx/
keywords: Image till PPTX, Konvertera Image till PPTX, PHP API, PHP Library, Image, PPTX
description: Konvertera Image till PPTX i PHP. Använd PowerPoint PHP API för att konvertera Image-filer till PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera Image till PPTX i PHP" h2="Kraftfullt PowerPoint PHP-bibliotek som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera Image till PPTX med PHP" variant="code" %}}

För att konvertera Image till PPTX måste du skapa en presentation från filen Image och spara den som PPTX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP-kod för att konvertera Image till PPTX" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera Image till PPTX i PHP" %}}

[**Aspose.Slides för PHP via Java**](https://products.aspose.com/slides/sv/php-java/) är ett kraftfullt PHP-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera Image till PPTX. Genom att använda **Aspose.Slides för PHP via Java**, kan vilken utvecklare eller applikation som helst konvertera filer från Image till PPTX med bara några rader PHP-kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för PHP snabbt Image-filer till PPTX-filformat. Aspose PowerPoint-bibliotek låter dig konvertera Image till PPTX och många andra filformat

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man konverterar Image till PPTX med Aspose.Slides för PHP API" intro="Det här är stegen för att konvertera Image till PPTX i PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera [**Aspose.Slides för PHP via Java**](https://products.aspose.com/slides/sv/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till en biblioteksreferens (importera biblioteket) till ditt PHP-projekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öppna källfilen Image i PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara resultatet som PPTX-fil.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Byggd med Aspose.Slides" title="Konvertera Bild till PPTX online" description="Den kostnadsfria appen Aspose.Slides Conversion är byggd med [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/sv/php-java/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna Bild-filer." button="Öppna Aspose.Slides Conversion" note="[Alla gratisappar](https://products.aspose.app/slides/family)" upload="Släpp eller ladda upp din fil" saveAs="Spara som" convert="Konvertera" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides konverterar filer innan du skriver kod.
- Ladda upp Bild-filer och spara dem som PPTX.
- Ladda ned resultatet eller konvertera fler filer.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konvertera Image till andra format som stöds" subTitle="Du kan också konvertera Image och spara till andra filformat. Se alla format som stöds nedan" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/image-to-html/" name="IMAGE TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
