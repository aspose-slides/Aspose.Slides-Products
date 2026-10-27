---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera PPTX till XPS i PHP
weight: 2730
url: /sv/php-java/conversion/pptx-to-xps/ 
keywords: "Convert, PowerPoint, PPTX, XPS, Presentation, PHP"
description: Exempelkod för PHP-konvertering från PPTX till XPS. Använd PowerPoint PHP API för batchkonvertering av PPTX-filer till XPS-filer.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera PPTX till XPS i PHP" h2="Kraftfullt PowerPoint PHP-bibliotek för att konvertera PPTX till XPS"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera PPTX till XPS i PHP" %}}

Behöver du konvertera PPTX-filer till XPS programmatiskt? Genom att använda [*Aspose.Slides för PHP via Java*](https://products.aspose.com/slides/sv/php-java/) kan alla utvecklare konvertera PPTX till XPS-format med bara några rader PHP-kod .

Som ett modernt presentationsbearbetnings-API skapar Aspose.Slides för PHP snabbt XPS från PPTX. Testa kvaliteten på konverteringen från PPTX till XPS direkt i din [webbläsare](https://products.aspose.app/slides/conversion). Aspose PowerPoint PPTX-bibliotek låter dig konvertera PPTX-filer till många populära format.

Du kan installera biblioteket från [Composer](https://packagist.org/packages/aspose/slides) med följande kommando:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Spara PPTX som XPS i PHP" %}}

Använd gratisappen för att se en demonstration av konverteringsprocessen från PPTX till XPS.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Den här exempelkoden visar PHP-konvertering från PPTX till XPS" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptx");
try
{
    $pres->save("output.xps", SaveFormat::Xps);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man konverterar PPTX till XPS i PHP" intro="Det här är stegen för att konvertera en PPTX-fil till XPS med PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda filen PPTX med en instans av presentationsklassen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa "spara"-metoden samtidigt som du anger sökväg för utdatafil och SaveFormat.XPS som parametrar{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Filen PPTX kommer att sparas på den angivna sökvägen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Systemkrav" intro="Innan du kör källkoden för PHP-konverteringsexemplet, se till att du har följande förutsättningar." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera PHP 7, lägg till sökväg till PHP till systemvariabeln "PATH" och ställ in "allow_url_include" till "På" i filen "php.ini".{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera JRE 8. Ställ in miljövariabeln `JAVA_HOME` som en sökväg till den installerade JRE-platsen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera Apache Tomcat 8.0 (se [mer](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Byggd med Aspose.Slides" title="Konvertera PPTX till XPS online" description="Den kostnadsfria appen Aspose.Slides Conversion är byggd med [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/sv/php-java/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPTX-filer." button="Öppna Aspose.Slides Conversion" note="[Alla gratisappar](https://products.aspose.app/slides/family)" upload="Släpp eller ladda upp din fil" saveAs="Spara som" convert="Konvertera" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides konverterar filer innan du skriver kod.
- Ladda upp PPTX-filer och spara dem som XPS.
- Ladda ned resultatet eller konvertera fler filer.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera PPTX till många andra filformat. Se andra omvandlingar som stöds nedan" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Bitmappsbild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-fodp/" name="PPTX TO FODP" description="OpenDocument platt XML-presentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Grafiskt utbytesformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-jpg/" name="PPTX TO JPG" description="JPEG-bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument presentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument standardformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Portabelt dokumentformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-png/" name="PPTX TO PNG" description="Bärbar nätverksgrafik" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-pot/" name="PPTX TO POT" description="Microsoft PowerPoint-mallfiler" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Microsoft PowerPoint-mallfil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Presentation av Microsoft PowerPoint-mall" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPoint-bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Makroaktiverat bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="PowerPoint-bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Makroaktiverad presentationsfil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Skalbar vektorgrafik" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWF-format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Taggad bildformat" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
