---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera POTX till TIFF i PHP
weight: 1460
url: /sv/php-java/conversion/potx-to-tiff/ 
keywords: "Convert, PowerPoint, POTX, TIFF, Presentation, PHP"
description: Exempelkod för PHP-konvertering från POTX till TIFF. Använd PowerPoint PHP API för batchkonvertering av POTX-filer till TIFF-filer.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera POTX till TIFF i PHP" h2="Kraftfullt PowerPoint PHP-bibliotek för att konvertera POTX till TIFF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera POTX till TIFF i PHP" %}}

Behöver du konvertera POTX-filer till TIFF programmatiskt? Genom att använda [*Aspose.Slides för PHP via Java*](https://products.aspose.com/slides/sv/php-java/) kan alla utvecklare konvertera POTX till TIFF-format med bara några rader PHP-kod .

Som ett modernt presentationsbearbetnings-API skapar Aspose.Slides för PHP snabbt TIFF från POTX. Testa kvaliteten på konverteringen från POTX till TIFF direkt i din [webbläsare](https://products.aspose.app/slides/conversion). Aspose PowerPoint PPTX-bibliotek låter dig konvertera POTX-filer till många populära format.

Du kan installera biblioteket från [Composer](https://packagist.org/packages/aspose/slides) med följande kommando:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Spara POTX som TIFF i PHP" %}}

Använd gratisappen för att se en demonstration av konverteringsprocessen från POTX till TIFF.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Den här exempelkoden visar PHP-konvertering från POTX till TIFF" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potx");
try
{
    $pres->save("output.tiff", SaveFormat::Tiff);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man konverterar POTX till TIFF i PHP" intro="Det här är stegen för att konvertera en POTX-fil till TIFF med PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda filen POTX med en instans av presentationsklassen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa "spara"-metoden samtidigt som du anger sökväg för utdatafil och SaveFormat.TIFF som parametrar{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Filen POTX kommer att sparas på den angivna sökvägen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Systemkrav" intro="Innan du kör källkoden för PHP-konverteringsexemplet, se till att du har följande förutsättningar." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera PHP 7, lägg till sökväg till PHP till systemvariabeln "PATH" och ställ in "allow_url_include" till "På" i filen "php.ini".{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera JRE 8. Ställ in miljövariabeln `JAVA_HOME` som en sökväg till den installerade JRE-platsen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera Apache Tomcat 8.0 (se [mer](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert POTX to TIFF"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera POTX till många andra filformat. Se andra omvandlingar som stöds nedan" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-bmp/" name="POTX TO BMP" description="Bitmappsbild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-fodp/" name="POTX TO FODP" description="OpenDocument platt XML-presentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-gif/" name="POTX TO GIF" description="Grafiskt utbytesformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-html/" name="POTX TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-jpg/" name="POTX TO JPG" description="JPEG-bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-odp/" name="POTX TO ODP" description="OpenDocument presentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-otp/" name="POTX TO OTP" description="OpenDocument standardformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-pdf/" name="POTX TO PDF" description="Portabelt dokumentformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-png/" name="POTX TO PNG" description="Bärbar nätverksgrafik" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-pot/" name="POTX TO POT" description="Microsoft PowerPoint-mallfiler" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-potm/" name="POTX TO POTM" description="Microsoft PowerPoint-mallfil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-pps/" name="POTX TO PPS" description="PowerPoint-bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-ppsm/" name="POTX TO PPSM" description="Makroaktiverat bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-ppsx/" name="POTX TO PPSX" description="PowerPoint-bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-ppt/" name="POTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-pptm/" name="POTX TO PPTM" description="Makroaktiverad presentationsfil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-pptx/" name="POTX TO PPTX" description="Öppna XML-presentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-svg/" name="POTX TO SVG" description="Skalbar vektorgrafik" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-swf/" name="POTX TO SWF" description="SWF-format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/potx-to-xps/" name="POTX TO XPS" description="XML-pappersspecifikationer" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
