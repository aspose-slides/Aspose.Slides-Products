---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie PPSX in HTML in PHP
weight: 1930
url: /de/php-java/conversion/ppsx-to-html/ 
keywords: "Convert, PowerPoint, PPSX, HTML, Presentation, PHP"
description: Beispielcode für die PHP-Konvertierung von PPSX nach HTML. Verwenden Sie die PowerPoint-PHP-API für die Stapelkonvertierung von PPSX-Dateien in HTML-Dateien.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie PPSX in HTML in PHP" h2="Leistungsstarke PowerPoint-PHP-Bibliothek zum Konvertieren von PPSX in HTML"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie PPSX in HTML in PHP" %}}

Müssen Sie PPSX-Dateien programmgesteuert in HTML konvertieren? Mit [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/de/php-java/) kann jeder Entwickler mit nur wenigen Zeilen PHP-Code das Format PPSX in das Format HTML konvertieren .

Als moderne Präsentationsverarbeitungs-API erstellt Aspose.Slides für PHP schnell HTML aus PPSX. Testen Sie die Qualität der Umwandlung von PPSX in HTML direkt in Ihrem [Browser](https://products.aspose.app/slides/conversion). Mit der Aspose PowerPoint PPTX-Bibliothek können Sie PPSX-Dateien in viele gängige Formate konvertieren.

Sie können die Bibliothek von [Composer](https://packagist.org/packages/aspose/slides) mit dem folgenden Befehl installieren:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsole/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Speichern Sie PPSX als HTML in PHP" %}}

Verwenden Sie die kostenlose App, um eine Demonstration des Umwandlungsprozesses von PPSX in HTML zu sehen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Dieser Beispielcode zeigt die PHP-Konvertierung von PPSX nach HTML" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsx");
try
{
    $pres->save("output.html", SaveFormat::Html5);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie PPSX in HTML in PHP" intro="Dies sind die Schritte zum Konvertieren einer PPSX-Datei in HTML mit PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die PPSX-Datei mit einer Instanz der Presentation-Klasse{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die `save`-Methode auf, während Sie den Pfad der Ausgabedatei und SaveFormat.HTML als Parameter angeben{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Die Datei PPSX wird unter dem angegebenen Pfad gespeichert{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="System Anforderungen" intro="Stellen Sie vor dem Ausführen des Beispielquellcodes für die PHP-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie PHP 7, fügen Sie den Pfad zu PHP zur Systemvariablen „PATH“ hinzu und setzen Sie „allow_url_include“ in der Datei „php.ini“ auf „On“.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie JRE 8. Legen Sie die Umgebungsvariable „JAVA_HOME“ als Pfad zum installierten JRE-Speicherort fest.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie Apache Tomcat 8.0 (siehe [mehr](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPSX to HTML"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere unterstützte Konvertierungen" subTitle="Sie können PPSX auch in viele andere Dateiformate konvertieren. Weitere unterstützte Konvertierungen finden Sie weiter unten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmap-Bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" description="OpenDocument Flat XML-Präsentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Grafisches Austauschformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" description="JPEG-Bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument-Präsentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument-Standardformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Portables Dokumentenformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Portable Netzwerkgrafiken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Makrofähige Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="Makrofähige Präsentationsdatei" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Offenes XML-Präsentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Skalierbare Vektorgrafiken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="SWF-Format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Markiertes Bildformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML-Papierspezifikationen" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
