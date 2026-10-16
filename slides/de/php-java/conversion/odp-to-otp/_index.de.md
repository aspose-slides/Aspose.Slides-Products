---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie ODP in OTP in PHP
weight: 270
url: /de/php-java/conversion/odp-to-otp/ 
keywords: "Convert, PowerPoint, ODP, OTP, Presentation, PHP"
description: Beispielcode für die PHP-Konvertierung von ODP nach OTP. Verwenden Sie die PowerPoint-PHP-API für die Stapelkonvertierung von ODP-Dateien in OTP-Dateien.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie ODP in OTP in PHP" h2="Leistungsstarke PowerPoint-PHP-Bibliothek zum Konvertieren von ODP in OTP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie ODP in OTP in PHP" %}}

Müssen Sie ODP-Dateien programmgesteuert in OTP konvertieren? Mit [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/de/php-java/) kann jeder Entwickler mit nur wenigen Zeilen PHP-Code das Format ODP in das Format OTP konvertieren .

Als moderne Präsentationsverarbeitungs-API erstellt Aspose.Slides für PHP schnell OTP aus ODP. Testen Sie die Qualität der Umwandlung von ODP in OTP direkt in Ihrem [Browser](https://products.aspose.app/slides/conversion). Mit der Aspose PowerPoint PPTX-Bibliothek können Sie ODP-Dateien in viele gängige Formate konvertieren.

Sie können die Bibliothek von [Composer](https://packagist.org/packages/aspose/slides) mit dem folgenden Befehl installieren:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsole/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Speichern Sie ODP als OTP in PHP" %}}

Verwenden Sie die kostenlose App, um eine Demonstration des Umwandlungsprozesses von ODP in OTP zu sehen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Dieser Beispielcode zeigt die PHP-Konvertierung von ODP nach OTP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.odp");
try
{
    $pres->save("output.otp", SaveFormat::Otp);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie ODP in OTP in PHP" intro="Dies sind die Schritte zum Konvertieren einer ODP-Datei in OTP mit PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die ODP-Datei mit einer Instanz der Presentation-Klasse{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die `save`-Methode auf, während Sie den Pfad der Ausgabedatei und SaveFormat.OTP als Parameter angeben{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Die Datei ODP wird unter dem angegebenen Pfad gespeichert{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="System Anforderungen" intro="Stellen Sie vor dem Ausführen des Beispielquellcodes für die PHP-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie PHP 7, fügen Sie den Pfad zu PHP zur Systemvariablen „PATH“ hinzu und setzen Sie „allow_url_include“ in der Datei „php.ini“ auf „On“.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie JRE 8. Legen Sie die Umgebungsvariable „JAVA_HOME“ als Pfad zum installierten JRE-Speicherort fest.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie Apache Tomcat 8.0 (siehe [mehr](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert ODP to OTP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere unterstützte Konvertierungen" subTitle="Sie können ODP auch in viele andere Dateiformate konvertieren. Weitere unterstützte Konvertierungen finden Sie weiter unten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-bmp/" name="ODP TO BMP" description="Bitmap-Bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-fodp/" name="ODP TO FODP" description="OpenDocument Flat XML-Präsentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-gif/" name="ODP TO GIF" description="Grafisches Austauschformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-html/" name="ODP TO HTML" description="Hypertext-Auszeichnungssprache" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-jpg/" name="ODP TO JPG" description="JPEG-Bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-pdf/" name="ODP TO PDF" description="Portables Dokumentenformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-png/" name="ODP TO PNG" description="Portable Netzwerkgrafiken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-pot/" name="ODP TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-potm/" name="ODP TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-potx/" name="ODP TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-pps/" name="ODP TO PPS" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Makrofähige Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Makrofähige Präsentationsdatei" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Offenes XML-Präsentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-svg/" name="ODP TO SVG" description="Skalierbare Vektorgrafiken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-swf/" name="ODP TO SWF" description="SWF-Format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Markiertes Bildformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/odp-to-xps/" name="ODP TO XPS" description="XML-Papierspezifikationen" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
