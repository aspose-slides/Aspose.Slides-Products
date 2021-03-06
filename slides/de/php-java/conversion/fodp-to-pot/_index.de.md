---
title: Konvertieren Sie FODP in POT in PHP
weight: 90
url: /de/php-java/conversion/fodp-to-pot/ 
keywords: "Convert, PowerPoint, FODP, POT, Presentation, PHP"
description: Beispielcode für die PHP-Konvertierung von FODP nach POT. Verwenden Sie die PowerPoint-PHP-API für die Stapelkonvertierung von FODP-Dateien in POT-Dateien.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie FODP in POT in PHP" h2="Leistungsstarke PowerPoint-PHP-Bibliothek zum Konvertieren von FODP in POT" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konvertieren Sie FODP in POT in PHP" %}}

Müssen Sie FODP-Dateien programmgesteuert in POT konvertieren? Mit [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/de/php-java/) kann jeder Entwickler mit nur wenigen Zeilen PHP-Code das Format FODP in das Format POT konvertieren .

Als moderne Präsentationsverarbeitungs-API erstellt Aspose.Slides für PHP schnell POT aus FODP. Testen Sie die Qualität der Umwandlung von FODP in POT direkt in Ihrem [Browser](https://products.aspose.app/slides/conversion). Mit der Aspose PowerPoint PPTX-Bibliothek können Sie FODP-Dateien in viele gängige Formate konvertieren.

Sie können die Bibliothek von [Composer](https://packagist.org/packages/aspose/slides) mit dem folgenden Befehl installieren:

{{% blocks/products/pf/agp/code-block title="Konsole/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="So konvertieren Sie FODP in POT in PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Konvertieren einer FODP-Datei in POT mit PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie die FODP-Datei mit einer Instanz der Presentation-Klasse
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Rufen Sie die `save`-Methode auf, während Sie den Pfad der Ausgabedatei und SaveFormat.POT als Parameter angeben
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Die Datei FODP wird unter dem angegebenen Pfad gespeichert
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Stellen Sie vor dem Ausführen des Beispielquellcodes für die PHP-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind.

{{% /blocks/products/pf/agp/text %}}

1. Installieren Sie PHP 7, fügen Sie den Pfad zu PHP zur Systemvariablen „PATH“ hinzu und setzen Sie „allow_url_include“ in der Datei „php.ini“ auf „On“.
1. Installieren Sie JRE 8. Legen Sie die Umgebungsvariable „JAVA_HOME“ als Pfad zum installierten JRE-Speicherort fest.
1. Installieren Sie Apache Tomcat 8.0 (siehe [mehr](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dieser Beispielcode zeigt die PHP-Konvertierung von FODP nach POT" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.fodp");
try
{
    $pres->save("output.pot", SaveFormat::Pot);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Speichern Sie FODP als POT in PHP" %}}
Verwenden Sie die kostenlose App, um eine Demonstration des Umwandlungsprozesses von FODP in POT zu sehen. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert FODP to POT" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können FODP auch in viele andere Dateiformate konvertieren. Weitere unterstützte Konvertierungen finden Sie weiter unten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-bmp/" name="FODP TO BMP" description="Bitmap-Bild" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-gif/" name="FODP TO GIF" description="Grafisches Austauschformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-html/" name="FODP TO HTML" description="Hypertext-Auszeichnungssprache" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-jpg/" name="FODP TO JPG" description="JPEG-Bild" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-odp/" name="FODP TO ODP" description="OpenDocument-Präsentationsformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-otp/" name="FODP TO OTP" description="OpenDocument-Standardformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-pdf/" name="FODP TO PDF" description="Portables Dokumentenformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-png/" name="FODP TO PNG" description="Portable Netzwerkgrafiken" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-potm/" name="FODP TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-potx/" name="FODP TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-pps/" name="FODP TO PPS" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" description="Makrofähige Diashow" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-ppt/" name="FODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" description="Makrofähige Präsentationsdatei" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" description="Offenes XML-Präsentationsformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-svg/" name="FODP TO SVG" description="Skalierbare Vektorgrafiken" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-swf/" name="FODP TO SWF" description="SWF-Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" description="Markiertes Bildformat" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/fodp-to-xps/" name="FODP TO XPS" description="XML-Papierspezifikationen" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}