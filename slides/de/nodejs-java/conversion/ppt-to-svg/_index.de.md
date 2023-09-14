---
title: Konvertieren Sie PPT in SVG in Node.js
url: /de/nodejs-java/conversion/ppt-to-svg/
keywords: PPT zu SVG, Konvertieren von PPT zu SVG, Node.js API, Node.js-Bibliothek, PPT, SVG
description: Konvertieren Sie PPT in SVG in Node.js. Verwenden Sie die Node.js-Bibliotheks-API, um PPT-Dateien in SVGs zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie PPT in SVG in Node.js" h2="Aspose.Slides für Node.js über Java ist eine leistungsstarke und benutzerfreundliche Bibliothek, mit der Sie PowerPoint-Präsentationen in verschiedene Formate in Node.js konvertieren können. Es unterstützt alle Präsentationselemente und -formate und bietet eine umfangreiche API für den Zugriff und die Änderung dieser. Außerdem können Sie Ihre Folien zur weiteren Verarbeitung oder Weitergabe in verschiedene Formate exportieren." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie PPT in SVG in Node.js" %}}

[**Aspose.Slides für Node.js über Java**](https://products.aspose.com/slides/de/nodejs-java/) ist eine leistungsstarke Node.js-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten zur Konvertierung von PPT in SVG. Mit **Aspose.Slides für Node.js über Java** kann jeder Entwickler oder jede Anwendung mit nur wenigen Codezeilen PPT-Dateien in SVG-Dateien konvertieren.

Als moderne API zur Dokumentenverarbeitung exportiert Aspose.Slides für Node.js schnell PPT-Dateien in SVG-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie PPT in SVGs und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PPT in SVG mit Node.js" %}}
Um das PPT in SVG zu konvertieren, müssen Sie eine Präsentation aus der PPT-Datei erstellen und diese als SVG speichern.

{{% blocks/products/pf/agp/code-block title="Node.js-Code zum Konvertieren von PPT in SVG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppt");
try
{
    var slide = pres.getSlides().get_Item(0);
    var svgStream = java.newInstanceSync("java.io.FileOutputStream", "image.svg");
    slide.writeAsSvg(svgStream);
    svgStream.close();
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So konvertieren Sie PPT in SVG mithilfe von Aspose.Slides für Node.js über die Java-API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Um PPT in SVG mit Aspose.Slides für Node.js über Java zu konvertieren, müssen Sie das Paket in Ihre JavaScript-Datei importieren und eine Instanz der Presentation-Klasse erstellen. Die Presentation-Klasse stellt ein PowerPoint-Dokument dar und stellt Methoden für den Zugriff und die Bearbeitung seiner Elemente bereit." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie [**Aspose.Slides für Node.js über Java**](https://products.aspose.com/slides/de/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Ihrem Node.js-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öffnen Sie die Quelldateien PPT in Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis als SVG-Datei speichern.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertieren Sie PPT in andere unterstützte Formate" subTitle="Sie können PPT auch konvertieren und in anderen Dateiformaten speichern. Nachfolgend finden Sie alle unterstützten Formate" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-jpg/" name="PPT TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-fodp/" name="PPT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-odp/" name="PPT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-otp/" name="PPT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-pot/" name="PPT TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-potm/" name="PPT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-potx/" name="PPT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-pps/" name="PPT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}