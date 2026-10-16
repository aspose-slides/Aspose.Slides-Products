---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie JPG in PPT in PHP
url: /de/php-java/conversion/jpg-to-ppt/
keywords: JPG in PPT, Konvertiere JPG in PPT, PHP-API, PHP-Bibliothek, JPG, PPT
description: Konvertieren Sie JPG in PPT in PHP. Verwenden Sie die PowerPoint-PHP-API, um JPG-Dateien in PPT zu konvertieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie JPG in PPT in PHP" h2="Leistungsstarke PowerPoint-PHP-Bibliothek, die bei der Entwicklung von Anwendungen mit der Fähigkeit hilft, Microsoft PowerPoint- und OpenOffice-Präsentationsdateien ohne die Verwendung von Software wie Microsoft oder Open Office, Adobe PDF zu erstellen, zusammenzuführen, zu überprüfen oder zu konvertieren." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie JPG in PPT mit PHP" variant="code" %}}

Um das JPG in PPT zu konvertieren, müssen Sie eine Präsentation aus der JPG-Datei erstellen und sie als PPT speichern.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP-Code zum Konvertieren von JPG in PPT" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.jpg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.ppt", SaveFormat::Ppt);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie JPG in PPT in PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/de/php-java/) ist eine leistungsstarke PHP-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten, JPG in PPT zu konvertieren. Mit **Aspose.Slides for PHP via Java** kann jeder Entwickler oder jede Anwendung JPG-Dateien mit nur wenigen Zeilen PHP-Code in PPT-Dateien konvertieren.

Als moderne Dokumentverarbeitungs-API exportiert Aspose.Slides für PHP schnell JPG-Dateien in PPT-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie JPG in PPTs und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie JPG in PPT mit Aspose.Slides for PHP API" intro="Dies sind die Schritte zum Konvertieren von JPG in PPT in PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie [**Aspose.Slides für PHP über Java**](https://products.aspose.com/slides/de/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie Ihrem PHP-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die Quelldateien JPG in PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ergebnis als PPT-Datei speichern.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Kostenloser Online-Konverter"
  description="[So konvertieren Sie PPT in HTML in Python](https://products.aspose.com/slides/de/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konvertieren Sie JPG in andere unterstützte Formate" subTitle="Sie können JPG auch konvertieren und in anderen Dateiformaten speichern. Siehe unten alle unterstützten Formate" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/jpg-to-html/" name="JPG TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/php-java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
