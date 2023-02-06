---
title: Bearbeiten Sie POTX in PHP
url: /de/php-java/editor/potx/
keywords: POTX bearbeiten, PowerPoint bearbeiten, POTX, PowerPoint, PHP-API, PHP-Bibliothek
description: Bearbeiten Sie POTX in PHP. Verwenden Sie die PHP-Bibliotheks-API, um POTX-Dateien zu bearbeiten
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Bearbeiten Sie POTX in PHP" h2="Hochgeschwindigkeits- und plattformübergreifende PHP-Bibliothek zum Bearbeiten von POTX mithilfe von PHP-Code" >}}

{{% blocks/products/pf/feature-page-section h2="Bearbeiten Sie POTX mit Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/de/php-java/) ist eine leistungsstarke PHP-Bibliothek zum schnellen und einfachen Bearbeiten von Präsentationen. Es bietet Benutzern eine umfangreiche Palette von Funktionen, mit denen sie im Handumdrehen professionell aussehende Folien erstellen können. Mit Aspose können Benutzer Texte bearbeiten, Bilder, Animationen und Übergänge zu ihrer Präsentation hinzufügen sowie verschiedene Formatierungsoptionen wie Schriftart und Farbauswahl anwenden. Darüber hinaus bietet die Bibliothek Unterstützung sowohl für PowerPoint-Dateien (PPT) als auch für OpenOffice-Präsentationsformate (ODP), was es einfacher denn je macht, Präsentationen über verschiedene Plattformen hinweg zu teilen, ohne dass Kompatibilitätsprobleme auftreten. Indem Sie beim Erstellen oder Bearbeiten Ihrer nächsten Präsentation die Leistungsfähigkeit der Aspose-Bibliothek nutzen, können Sie sicher sein, dass Ihre Folien jedes Mal großartig aussehen!
Sie können eine POTX-Datei bearbeiten, indem Sie ihr eine neue Textzeile hinzufügen. 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Bearbeiten Sie POTX in PHP" %}}
Mit [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/de/php-java/) können Sie dem POTX-Dokument mit nur einem eine neue Textzeile hinzufügen paar Zeilen Code.

{{% blocks/products/pf/agp/code-block title="PHP-Code zum Bearbeiten von POTX" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potx");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.potx", SaveFormat::Potx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So bearbeiten Sie POTX in PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie **Aspose.Slides für PHP über Java**. Siehe [**Installation**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie die Bibliothek als Referenz in Ihrem Projekt hinzu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Erstellen Sie eine Instanz der Presentation-Klasse.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie die POTX-Präsentation, die Sie bearbeiten möchten.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie eine neue Textzeile hinzu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie die geänderte Datei.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Bearbeiten Sie andere Dateien" subTitle="Sie können auch Dateien in anderen Formaten bearbeiten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}