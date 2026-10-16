---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie FODP in PPS in PHP
weight: 120
url: /de/php-java/conversion/fodp-to-pps/ 
keywords: "Convert, PowerPoint, FODP, PPS, Presentation, PHP"
description: Beispielcode für die PHP-Konvertierung von FODP nach PPS. Verwenden Sie die PowerPoint-PHP-API für die Stapelkonvertierung von FODP-Dateien in PPS-Dateien.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie FODP in PPS in PHP" h2="Leistungsstarke PowerPoint-PHP-Bibliothek zum Konvertieren von FODP in PPS"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie FODP in PPS in PHP" %}}

Müssen Sie FODP-Dateien programmgesteuert in PPS konvertieren? Mit [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/de/php-java/) kann jeder Entwickler mit nur wenigen Zeilen PHP-Code das Format FODP in das Format PPS konvertieren .

Als moderne Präsentationsverarbeitungs-API erstellt Aspose.Slides für PHP schnell PPS aus FODP. Testen Sie die Qualität der Umwandlung von FODP in PPS direkt in Ihrem [Browser](https://products.aspose.app/slides/conversion). Mit der Aspose PowerPoint PPTX-Bibliothek können Sie FODP-Dateien in viele gängige Formate konvertieren.

Sie können die Bibliothek von [Composer](https://packagist.org/packages/aspose/slides) mit dem folgenden Befehl installieren:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsole/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Speichern Sie FODP als PPS in PHP" %}}

Verwenden Sie die kostenlose App, um eine Demonstration des Umwandlungsprozesses von FODP in PPS zu sehen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Dieser Beispielcode zeigt die PHP-Konvertierung von FODP nach PPS" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.fodp");
try
{
    $pres->save("output.pps", SaveFormat::Pps);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie FODP in PPS in PHP" intro="Dies sind die Schritte zum Konvertieren einer FODP-Datei in PPS mit PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die FODP-Datei mit einer Instanz der Presentation-Klasse{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die `save`-Methode auf, während Sie den Pfad der Ausgabedatei und SaveFormat.PPS als Parameter angeben{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Die Datei FODP wird unter dem angegebenen Pfad gespeichert{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="System Anforderungen" intro="Stellen Sie vor dem Ausführen des Beispielquellcodes für die PHP-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie PHP 7, fügen Sie den Pfad zu PHP zur Systemvariablen „PATH“ hinzu und setzen Sie „allow_url_include“ in der Datei „php.ini“ auf „On“.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie JRE 8. Legen Sie die Umgebungsvariable „JAVA_HOME“ als Pfad zum installierten JRE-Speicherort fest.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie Apache Tomcat 8.0 (siehe [mehr](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert FODP to PPS"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere unterstützte Konvertierungen" subTitle="Sie können FODP auch in viele andere Dateiformate konvertieren. Weitere unterstützte Konvertierungen finden Sie weiter unten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-bmp/" name="FODP TO BMP" description="Bitmap-Bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-gif/" name="FODP TO GIF" description="Grafisches Austauschformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-html/" name="FODP TO HTML" description="Hypertext-Auszeichnungssprache" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-jpg/" name="FODP TO JPG" description="JPEG-Bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-odp/" name="FODP TO ODP" description="OpenDocument-Präsentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-otp/" name="FODP TO OTP" description="OpenDocument-Standardformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-pdf/" name="FODP TO PDF" description="Portables Dokumentenformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-png/" name="FODP TO PNG" description="Portable Netzwerkgrafiken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-pot/" name="FODP TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-potm/" name="FODP TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-potx/" name="FODP TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Makrofähige Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Makrofähige Präsentationsdatei" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Offenes XML-Präsentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-svg/" name="FODP TO SVG" description="Skalierbare Vektorgrafiken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-swf/" name="FODP TO SWF" description="SWF-Format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Markiertes Bildformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-xps/" name="FODP TO XPS" description="XML-Papierspezifikationen" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
