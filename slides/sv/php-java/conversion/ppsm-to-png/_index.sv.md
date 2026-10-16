---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera PPSM till PNG i PHP
weight: 1770
url: /sv/php-java/conversion/ppsm-to-png/ 
keywords: "Convert, PowerPoint, PPSM, PNG, Presentation, PHP"
description: Exempelkod för PHP-konvertering från PPSM till PNG. Använd PowerPoint PHP API för batchkonvertering av PPSM-filer till PNG-filer.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera PPSM till PNG i PHP" h2="Kraftfullt PowerPoint PHP-bibliotek för att konvertera PPSM till PNG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera PPSM till PNG i PHP" %}}

Behöver du konvertera PPSM-filer till PNG programmatiskt? Genom att använda [*Aspose.Slides för PHP via Java*](https://products.aspose.com/slides/sv/php-java/) kan alla utvecklare konvertera PPSM till PNG-format med bara några rader PHP-kod .

Som ett modernt presentationsbearbetnings-API skapar Aspose.Slides för PHP snabbt PNG från PPSM. Testa kvaliteten på konverteringen från PPSM till PNG direkt i din [webbläsare](https://products.aspose.app/slides/conversion/ppt-to-png). Aspose PowerPoint PPTX-bibliotek låter dig konvertera PPSM-filer till många populära format.

Du kan installera biblioteket från [Composer](https://packagist.org/packages/aspose/slides) med följande kommando:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Spara PPSM som PNG i PHP" %}}

Använd gratisappen för att se en demonstration av konverteringsprocessen från PPSM till PNG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Den här exempelkoden visar PHP-konvertering från PPSM till PNG" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsm");
try
{
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

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man konverterar PPSM till PNG i PHP" intro="Det här är stegen för att konvertera en PPSM-fil till PNG med PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda filen PPSM med en instans av presentationsklassen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa "spara"-metoden samtidigt som du anger sökväg för utdatafil och SaveFormat.PNG som parametrar{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Filen PPSM kommer att sparas på den angivna sökvägen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Systemkrav" intro="Innan du kör källkoden för PHP-konverteringsexemplet, se till att du har följande förutsättningar." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera PHP 7, lägg till sökväg till PHP till systemvariabeln "PATH" och ställ in "allow_url_include" till "På" i filen "php.ini".{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera JRE 8. Ställ in miljövariabeln `JAVA_HOME` som en sökväg till den installerade JRE-platsen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera Apache Tomcat 8.0 (se [mer](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPSM to PNG"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera PPSM till många andra filformat. Se andra omvandlingar som stöds nedan" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Bitmappsbild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-fodp/" name="PPSM TO FODP" description="OpenDocument platt XML-presentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Grafiskt utbytesformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-jpg/" name="PPSM TO JPG" description="JPEG-bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="OpenDocument presentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="OpenDocument standardformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Portabelt dokumentformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Microsoft PowerPoint-mallfiler" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Microsoft PowerPoint-mallfil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Presentation av Microsoft PowerPoint-mall" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="PowerPoint-bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="PowerPoint-bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Makroaktiverad presentationsfil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Öppna XML-presentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Skalbar vektorgrafik" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="SWF-format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Taggad bildformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="XML-pappersspecifikationer" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
