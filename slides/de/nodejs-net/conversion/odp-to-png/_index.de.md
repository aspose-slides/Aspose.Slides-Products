---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie ODP in PNG in JavaScript
url: /de/nodejs-net/conversion/odp-to-png/
keywords: ODP zu PNG, Konvertieren von ODP zu PNG, Node.js API, JavaScript-Bibliothek, ODP, PNG
description: Konvertieren Sie ODP in PNG in JavaScript. Verwenden Sie die Node.js-Bibliotheks-API, um ODP-Dateien in PNG zu konvertieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie ODP in PNG in JavaScript" h2="Aspose.Slides für Node.js über .NET ist eine leistungsstarke und benutzerfreundliche Bibliothek, mit der Sie PowerPoint-Präsentationen in verschiedene Formate in JavaScript konvertieren können. Es unterstützt alle Präsentationselemente und -formate und bietet eine umfangreiche API für den Zugriff und die Änderung dieser. Außerdem können Sie Ihre Folien zur weiteren Verarbeitung oder Weitergabe in verschiedene Formate exportieren." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie ODP mit JavaScript in PNG" variant="code" %}}

Um das ODP in PNG zu konvertieren, müssen Sie eine Präsentation aus der ODP-Datei erstellen und diese als PNG speichern.

{{< blocks/products/pf/slides-design-update-10-2026/code title="JavaScript-Code zum Konvertieren von ODP in PNG" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie ODP in PNG in Node.js" %}}

[**Aspose.Slides für Node.js über .NET**](https://products.aspose.com/slides/de/nodejs-net/) ist eine leistungsstarke Node.js-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten zur Konvertierung von ODP in PNG. Mit **Aspose.Slides für Node.js über .NET** kann jeder Entwickler oder jede Anwendung mit nur wenigen Codezeilen ODP-Dateien in PNG-Dateien konvertieren.

Als moderne API zur Dokumentenverarbeitung exportiert Aspose.Slides für Node.js über .NET schnell ODP-Dateien in PNG-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie ODP in PNGs und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie ODP in PNG mit Aspose.Slides für Node.js über die .NET-API" intro="Um ODP in PNG mit Aspose.Slides für Node.js über .NET zu konvertieren, müssen Sie das Paket in Ihre JavaScript-Datei importieren und eine Instanz der Presentation-Klasse erstellen. Die Presentation-Klasse stellt ein PowerPoint-Dokument dar und stellt Methoden für den Zugriff und die Bearbeitung seiner Elemente bereit." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie [**Aspose.Slides für Node.js über .NET**](https://products.aspose.com/slides/de/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie Ihrem Node.js-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die Quelldateien ODP in Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ergebnis als PNG-Datei speichern.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konvertieren Sie ODP in andere unterstützte Formate" subTitle="Sie können ODP auch konvertieren und in anderen Dateiformaten speichern. Nachfolgend finden Sie alle unterstützten Formate" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-pptx/" name="ODP TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-ppt/" name="ODP TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-pdf/" name="ODP TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-html/" name="ODP TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-bmp/" name="ODP TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-jpg/" name="ODP TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-fodp/" name="ODP TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-gif/" name="ODP TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-otp/" name="ODP TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-pot/" name="ODP TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-potm/" name="ODP TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-potx/" name="ODP TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-pps/" name="ODP TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-ppsm/" name="ODP TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-ppsx/" name="ODP TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-pptm/" name="ODP TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-svg/" name="ODP TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/odp-to-tiff/" name="ODP TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
