---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera PPSX till JPG i PHP
weight: 1940
url: /sv/php-java/conversion/ppsx-to-jpg/ 
keywords: "Convert, PowerPoint, PPSX, JPG, Presentation, PHP"
description: Exempelkod för PHP-konvertering från PPSX till JPG. Använd PowerPoint PHP API för batchkonvertering av PPSX-filer till JPG-filer.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera PPSX till JPG i PHP" h2="Kraftfullt PowerPoint PHP-bibliotek för att konvertera PPSX till JPG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera PPSX till JPG i PHP" %}}

Behöver du konvertera PPSX-filer till JPG programmatiskt? Genom att använda [*Aspose.Slides för PHP via Java*](https://products.aspose.com/slides/sv/php-java/) kan alla utvecklare konvertera PPSX till JPG-format med bara några rader PHP-kod .

Som ett modernt presentationsbearbetnings-API skapar Aspose.Slides för PHP snabbt JPG från PPSX. Testa kvaliteten på konverteringen från PPSX till JPG direkt i din [webbläsare](https://products.aspose.app/slides/conversion). Aspose PowerPoint PPTX-bibliotek låter dig konvertera PPSX-filer till många populära format.

Du kan installera biblioteket från [Composer](https://packagist.org/packages/aspose/slides) med följande kommando:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Spara PPSX som JPG i PHP" %}}

Använd gratisappen för att se en demonstration av konverteringsprocessen från PPSX till JPG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Den här exempelkoden visar PHP-konvertering från PPSX till JPG" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsx");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPEG", $javafile);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man konverterar PPSX till JPG i PHP" intro="Det här är stegen för att konvertera en PPSX-fil till JPG med PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda filen PPSX med en instans av presentationsklassen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Anropa "spara"-metoden samtidigt som du anger sökväg för utdatafil och SaveFormat.JPG som parametrar{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Filen PPSX kommer att sparas på den angivna sökvägen{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Systemkrav" intro="Innan du kör källkoden för PHP-konverteringsexemplet, se till att du har följande förutsättningar." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera PHP 7, lägg till sökväg till PHP till systemvariabeln "PATH" och ställ in "allow_url_include" till "På" i filen "php.ini".{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera JRE 8. Ställ in miljövariabeln `JAVA_HOME` som en sökväg till den installerade JRE-platsen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera Apache Tomcat 8.0 (se [mer](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Byggd med Aspose.Slides" title="Konvertera PPSX till JPG online" description="Den kostnadsfria appen Aspose.Slides Conversion är byggd med [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/sv/php-java/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPSX-filer." button="Öppna Aspose.Slides Conversion" note="[Alla gratisappar](https://products.aspose.app/slides/family)" upload="Släpp eller ladda upp din fil" saveAs="Spara som" convert="Konvertera" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides konverterar filer innan du skriver kod.
- Ladda upp PPSX-filer och spara dem som JPG.
- Ladda ned resultatet eller konvertera fler filer.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera PPSX till många andra filformat. Se andra omvandlingar som stöds nedan" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmappsbild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" description="OpenDocument platt XML-presentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Grafiskt utbytesformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument presentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument standardformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Portabelt dokumentformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Bärbar nätverksgrafik" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint-mallfiler" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Microsoft PowerPoint-mallfil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Presentation av Microsoft PowerPoint-mall" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="PowerPoint-bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Makroaktiverat bildspel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Makroaktiverad presentationsfil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Öppna XML-presentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Skalbar vektorgrafik" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="SWF-format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Taggad bildformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/php-java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML-pappersspecifikationer" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
