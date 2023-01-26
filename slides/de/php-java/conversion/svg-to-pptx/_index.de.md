---
title: Konvertieren Sie SVG in PPTX in PHP
url: /de/php-java/conversion/svg-to-pptx/
keywords: SVG in PPTX, Konvertiere SVG in PPTX, PHP-API, PHP-Bibliothek, SVG, PPTX
description: Konvertieren Sie SVG in PPTX in PHP. Verwenden Sie die PowerPoint-PHP-API, um SVG-Dateien in PPTX zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie SVG in PPTX in PHP" h2="Leistungsstarke PowerPoint-PHP-Bibliothek, die bei der Entwicklung von Anwendungen mit der Fähigkeit hilft, Microsoft PowerPoint- und OpenOffice-Präsentationsdateien ohne die Verwendung von Software wie Microsoft oder Open Office, Adobe PDF zu erstellen, zusammenzuführen, zu überprüfen oder zu konvertieren." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie SVG in PPTX in PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/de/php-java/) ist eine leistungsstarke PHP-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten, SVG in PPTX zu konvertieren. Mit **Aspose.Slides for PHP via Java** kann jeder Entwickler oder jede Anwendung SVG-Dateien mit nur wenigen Zeilen PHP-Code in PPTX-Dateien konvertieren.

Als moderne Dokumentverarbeitungs-API exportiert Aspose.Slides für PHP schnell SVG-Dateien in PPTX-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie SVG in PPTXs und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie SVG in PPTX mit PHP" %}}
Um das SVG in PPTX zu konvertieren, müssen Sie eine Präsentation aus der SVG-Datei erstellen und sie als PPTX speichern.

{{% blocks/products/pf/agp/code-block title="PHP-Code zum Konvertieren von SVG in PPTX" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.svg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $svgImage = new SvgImage($contents);
    $image = $pres->getImages()->addImage($svgImage);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.pptx", SaveFormat::Pptx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So konvertieren Sie SVG in PPTX mit Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Konvertieren von SVG in PPTX in PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie [**Aspose.Slides für PHP über Java**](https://products.aspose.com/slides/de/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Ihrem PHP-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öffnen Sie die Quelldateien SVG in PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis als PPTX-Datei speichern.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertieren Sie SVG in andere unterstützte Formate" subTitle="Sie können SVG auch konvertieren und in anderen Dateiformaten speichern. Siehe unten alle unterstützten Formate" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/svg-to-ppt/" name="SVG TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}