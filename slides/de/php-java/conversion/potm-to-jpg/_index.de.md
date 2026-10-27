---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie POTM in JPG in PHP
weight: 1100
url: /de/php-java/conversion/potm-to-jpg/ 
keywords: "Convert, PowerPoint, POTM, JPG, Presentation, PHP"
description: Beispielcode für die PHP-Konvertierung von POTM nach JPG. Verwenden Sie die PowerPoint-PHP-API für die Stapelkonvertierung von POTM-Dateien in JPG-Dateien.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie POTM in JPG in PHP" h2="Leistungsstarke PowerPoint-PHP-Bibliothek zum Konvertieren von POTM in JPG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie POTM in JPG in PHP" %}}

Müssen Sie POTM-Dateien programmgesteuert in JPG konvertieren? Mit [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/de/php-java/) kann jeder Entwickler mit nur wenigen Zeilen PHP-Code das Format POTM in das Format JPG konvertieren .

Als moderne Präsentationsverarbeitungs-API erstellt Aspose.Slides für PHP schnell JPG aus POTM. Testen Sie die Qualität der Umwandlung von POTM in JPG direkt in Ihrem [Browser](https://products.aspose.app/slides/conversion). Mit der Aspose PowerPoint PPTX-Bibliothek können Sie POTM-Dateien in viele gängige Formate konvertieren.

Sie können die Bibliothek von [Composer](https://packagist.org/packages/aspose/slides) mit dem folgenden Befehl installieren:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsole/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Speichern Sie POTM als JPG in PHP" %}}

Verwenden Sie die kostenlose App, um eine Demonstration des Umwandlungsprozesses von POTM in JPG zu sehen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Dieser Beispielcode zeigt die PHP-Konvertierung von POTM nach JPG" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potm");
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie POTM in JPG in PHP" intro="Dies sind die Schritte zum Konvertieren einer POTM-Datei in JPG mit PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die POTM-Datei mit einer Instanz der Presentation-Klasse{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die `save`-Methode auf, während Sie den Pfad der Ausgabedatei und SaveFormat.JPG als Parameter angeben{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Die Datei POTM wird unter dem angegebenen Pfad gespeichert{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="System Anforderungen" intro="Stellen Sie vor dem Ausführen des Beispielquellcodes für die PHP-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie PHP 7, fügen Sie den Pfad zu PHP zur Systemvariablen „PATH“ hinzu und setzen Sie „allow_url_include“ in der Datei „php.ini“ auf „On“.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie JRE 8. Legen Sie die Umgebungsvariable „JAVA_HOME“ als Pfad zum installierten JRE-Speicherort fest.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie Apache Tomcat 8.0 (siehe [mehr](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Entwickelt mit Aspose.Slides" title="POTM online in JPG konvertieren" description="Die kostenlose App Aspose.Slides Conversion basiert auf [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/de/php-java/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen POTM-Dateien leisten kann." button="Aspose.Slides Conversion öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" upload="Datei ablegen oder hochladen" saveAs="Speichern als" convert="Konvertieren" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Dateien konvertiert, bevor Sie Code schreiben.
- Laden Sie POTM-Dateien hoch und speichern Sie sie als JPG.
- Laden Sie das Ergebnis herunter oder konvertieren Sie weitere Dateien.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere unterstützte Konvertierungen" subTitle="Sie können POTM auch in viele andere Dateiformate konvertieren. Weitere unterstützte Konvertierungen finden Sie weiter unten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-bmp/" name="POTM TO BMP" description="Bitmap-Bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-fodp/" name="POTM TO FODP" description="OpenDocument Flat XML-Präsentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-gif/" name="POTM TO GIF" description="Grafisches Austauschformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-html/" name="POTM TO HTML" description="Hypertext-Auszeichnungssprache" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-odp/" name="POTM TO ODP" description="OpenDocument-Präsentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-otp/" name="POTM TO OTP" description="OpenDocument-Standardformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-pdf/" name="POTM TO PDF" description="Portables Dokumentenformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-png/" name="POTM TO PNG" description="Portable Netzwerkgrafiken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-pot/" name="POTM TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-potx/" name="POTM TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-pps/" name="POTM TO PPS" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Makrofähige Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Makrofähige Präsentationsdatei" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Offenes XML-Präsentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-svg/" name="POTM TO SVG" description="Skalierbare Vektorgrafiken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-swf/" name="POTM TO SWF" description="SWF-Format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Markiertes Bildformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/potm-to-xps/" name="POTM TO XPS" description="XML-Papierspezifikationen" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
