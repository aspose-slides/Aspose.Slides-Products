---
title: Führen Sie PDF, PPT, PPTX und viele andere Dateiformate mit PHP zusammen
url: /de/php-java/merger/
keywords: Zusammenführen, Verbinden, PowerPoint, Präsentation, PHP, Aspose
description: Führen Sie mehrere Dateien in PHP PPT, PPTX, ODP, PDF, PNG, JPG und vielen mehr zusammen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Führen Sie Powerpoint, PDF, PPT oder andere Dokumente in PHP zusammen" h2="Hochgeschwindigkeits-PHP-Bibliothek zum Zusammenführen von PPT, PPTX, PDF, PNG, JPEG und anderen Formaten." >}}

{{% blocks/products/pf/feature-page-section h2="PPT, PPTX, PDF mit PHP zusammenführen" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/de/php-java/) ist eine leistungsstarke PHP-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten, mehrere PPT/PPTX-Präsentationen zu kombinieren. Wenn Sie eine Präsentation mit einer anderen zusammenführen, kombinieren Sie effektiv ihre Folien in einer einzigen Präsentation, um eine Datei zu erhalten. Mit Aspose.Slides können Sie zwei Präsentationen auf unterschiedliche Weise zusammenführen. Sie können Präsentationen mit all ihren Formen, Stilen, Texten, Formatierungen, Kommentaren, Animationen usw. zusammenführen, ohne sich um Qualitäts- oder Datenverluste sorgen zu müssen.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint-Präsentationen in PHP zusammenführen" %}}
Um die PowerPoint-Präsentationen zusammenzuführen, müssen Sie die Folien von einer Präsentation zur anderen klonen.

{{% blocks/products/pf/agp/code-block title="PPTX-Dateien mit PHP zusammenführen" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres1 = new Presentation("document1.ppt");
$pres2 = new Presentation("document2.ppt");
try
{
    for ($i = 0; $i < java_values($pres2->getSlides()->size()); $i++) 
    {
        $pres1->getSlides()->addClone($pres2->getSlides()->get_Item($i));
    }

    $pres1->save("merged.ppt", SaveFormat::Ppt);
}
finally
{
    if ($pres1 != null) $pres1->dispose();
    if ($pres2 != null) $pres2->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So führen Sie Präsentationen mit Aspose.Slides for PHP API zusammen" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte, um zwei PPTX-Dateien zusammenzuführen und das Ergebnis als PDF in PHP zu speichern." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie [**Aspose.Slides für PHP über Java**](https://docs.aspose.com/slides/php-java/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Ihrem PHP-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öffnen Sie die Quell-PPTX-Dateien in PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinieren Sie PPTX-Dateien mit der Methode **addClone**.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Präsentation speichern und Ergebnis als einzelne PDF-Datei erhalten.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Formate zum Zusammenführen" subTitle="Sie können auch andere Dateiformate kombinieren. Weitere unterstützte Formate finden Sie weiter unten." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/merger/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/merger/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/merger/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/merger/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/merger/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/merger/potm/" name="POTM" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/merger/potx/" name="POTX" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/merger/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/merger/ppsm/" name="PPSM" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/merger/ppsx/" name="PPSX" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/merger/pptm/" name="PPTM" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/merger/fodp/" name="FODP" >}}        
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/php-java/merger/pdf-to-pdf/" name="PDF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}