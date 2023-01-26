---
title: Konvertieren Sie PNG in JPG in PHP
url: /de/php-java/conversion/png-to-jpg/
keywords: PNG in JPG, Konvertiere PNG in JPG, PHP-API, PHP-Bibliothek, PNG, JPG
description: Konvertieren Sie PNG in JPG in PHP. Verwenden Sie die PowerPoint-PHP-API, um PNG-Dateien in JPG zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie PNG in JPG in PHP" h2="Leistungsstarke PowerPoint-PHP-Bibliothek, die bei der Entwicklung von Anwendungen mit der Fähigkeit hilft, Microsoft PowerPoint- und OpenOffice-Präsentationsdateien ohne die Verwendung von Software wie Microsoft oder Open Office, Adobe PDF zu erstellen, zusammenzuführen, zu überprüfen oder zu konvertieren." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie PNG in JPG in PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/de/php-java/) ist eine leistungsstarke PHP-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten, PNG in JPG zu konvertieren. Mit **Aspose.Slides for PHP via Java** kann jeder Entwickler oder jede Anwendung PNG-Dateien mit nur wenigen Zeilen PHP-Code in JPG-Dateien konvertieren.

Als moderne Dokumentverarbeitungs-API exportiert Aspose.Slides für PHP schnell PNG-Dateien in JPG-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie PNG in JPGs und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PNG in JPG mit PHP" %}}
Um das PNG in JPG zu konvertieren, müssen Sie eine Präsentation aus der PNG-Datei erstellen und sie als JPG speichern.

{{% blocks/products/pf/agp/code-block title="PHP-Code zum Konvertieren von PNG in JPG" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.png';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So konvertieren Sie PNG in JPG mit Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Konvertieren von PNG in JPG in PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie [**Aspose.Slides für PHP über Java**](https://products.aspose.com/slides/de/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Ihrem PHP-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öffnen Sie die Quelldateien PNG in PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis als JPG-Datei speichern.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertieren Sie PNG in andere unterstützte Formate" subTitle="Sie können PNG auch konvertieren und in anderen Dateiformaten speichern. Siehe unten alle unterstützten Formate" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/png-to-html/" name="PNG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}