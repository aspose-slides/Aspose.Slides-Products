---
title: Konvertieren Sie ODP in PNG in JavaScript
url: /de/nodejs-net/conversion/odp-to-png/
keywords: ODP zu PNG, Konvertieren von ODP zu PNG, Node.js API, JavaScript-Bibliothek, ODP, PNG
description: Konvertieren Sie ODP in PNG in JavaScript. Verwenden Sie die Node.js-Bibliotheks-API, um ODP-Dateien in PNG zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie ODP in PNG in JavaScript" h2="Aspose.Slides für Node.js über .NET ist eine leistungsstarke und benutzerfreundliche Bibliothek, mit der Sie PowerPoint-Präsentationen in verschiedene Formate in JavaScript konvertieren können. Es unterstützt alle Präsentationselemente und -formate und bietet eine umfangreiche API für den Zugriff und die Änderung dieser. Außerdem können Sie Ihre Folien zur weiteren Verarbeitung oder Weitergabe in verschiedene Formate exportieren." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie ODP in PNG in Node.js" %}}

[**Aspose.Slides für Node.js über .NET**](https://products.aspose.com/slides/de/nodejs-net/) ist eine leistungsstarke Node.js-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten zur Konvertierung von ODP in PNG. Mit **Aspose.Slides für Node.js über .NET** kann jeder Entwickler oder jede Anwendung mit nur wenigen Codezeilen ODP-Dateien in PNG-Dateien konvertieren.

Als moderne API zur Dokumentenverarbeitung exportiert Aspose.Slides für Node.js über .NET schnell ODP-Dateien in PNG-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie ODP in PNGs und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie ODP mit JavaScript in PNG" %}}
Um das ODP in PNG zu konvertieren, müssen Sie eine Präsentation aus der ODP-Datei erstellen und diese als PNG speichern.

{{% blocks/products/pf/agp/code-block title="JavaScript-Code zum Konvertieren von ODP in PNG" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.odp");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".png", ImageFormat.Png); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So konvertieren Sie ODP in PNG mit Aspose.Slides für Node.js über die .NET-API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Um ODP in PNG mit Aspose.Slides für Node.js über .NET zu konvertieren, müssen Sie das Paket in Ihre JavaScript-Datei importieren und eine Instanz der Presentation-Klasse erstellen. Die Presentation-Klasse stellt ein PowerPoint-Dokument dar und stellt Methoden für den Zugriff und die Bearbeitung seiner Elemente bereit." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie [**Aspose.Slides für Node.js über .NET**](https://products.aspose.com/slides/de/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Ihrem Node.js-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öffnen Sie die Quelldateien ODP in Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis als PNG-Datei speichern.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertieren Sie ODP in andere unterstützte Formate" subTitle="Sie können ODP auch konvertieren und in anderen Dateiformaten speichern. Nachfolgend finden Sie alle unterstützten Formate" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-pptx/" name="ODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-ppt/" name="ODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-pdf/" name="ODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-html/" name="ODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-bmp/" name="ODP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-jpg/" name="ODP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-fodp/" name="ODP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-gif/" name="ODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-otp/" name="ODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-pot/" name="ODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-potm/" name="ODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-potx/" name="ODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-pps/" name="ODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-ppsm/" name="ODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-ppsx/" name="ODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-pptm/" name="ODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-svg/" name="ODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-tiff/" name="ODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}