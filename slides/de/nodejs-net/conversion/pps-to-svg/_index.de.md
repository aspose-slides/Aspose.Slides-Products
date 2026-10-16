---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie PPS in SVG in JavaScript
url: /de/nodejs-net/conversion/pps-to-svg/
keywords: PPS zu SVG, Konvertieren von PPS zu SVG, Node.js API, JavaScript-Bibliothek, PPS, SVG
description: Konvertieren Sie PPS in SVG in JavaScript. Verwenden Sie die Node.js-Bibliotheks-API, um PPS-Dateien in SVG zu konvertieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie PPS in SVG in JavaScript" h2="Aspose.Slides für Node.js über .NET ist eine leistungsstarke und benutzerfreundliche Bibliothek, mit der Sie PowerPoint-Präsentationen in verschiedene Formate in JavaScript konvertieren können. Es unterstützt alle Präsentationselemente und -formate und bietet eine umfangreiche API für den Zugriff und die Änderung dieser. Außerdem können Sie Ihre Folien zur weiteren Verarbeitung oder Weitergabe in verschiedene Formate exportieren." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie PPS mit JavaScript in SVG" variant="code" %}}

Um das PPS in SVG zu konvertieren, müssen Sie eine Präsentation aus der PPS-Datei erstellen und diese als SVG speichern.

{{< blocks/products/pf/slides-design-update-10-2026/code title="JavaScript-Code zum Konvertieren von PPS in SVG" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pps");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slideByteArray = pres.slides.get(i).getAsSvg();
        fs.writeFile('slide" + i + ".svg', Buffer.from(slideByteArray), (err) => {
            if (err)
                console.error(err);
        });
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie PPS in SVG in Node.js" %}}

[**Aspose.Slides für Node.js über .NET**](https://products.aspose.com/slides/de/nodejs-net/) ist eine leistungsstarke Node.js-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten zur Konvertierung von PPS in SVG. Mit **Aspose.Slides für Node.js über .NET** kann jeder Entwickler oder jede Anwendung mit nur wenigen Codezeilen PPS-Dateien in SVG-Dateien konvertieren.

Als moderne API zur Dokumentenverarbeitung exportiert Aspose.Slides für Node.js über .NET schnell PPS-Dateien in SVG-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie PPS in SVGs und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie PPS in SVG mit Aspose.Slides für Node.js über die .NET-API" intro="Um PPS in SVG mit Aspose.Slides für Node.js über .NET zu konvertieren, müssen Sie das Paket in Ihre JavaScript-Datei importieren und eine Instanz der Presentation-Klasse erstellen. Die Presentation-Klasse stellt ein PowerPoint-Dokument dar und stellt Methoden für den Zugriff und die Bearbeitung seiner Elemente bereit." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie [**Aspose.Slides für Node.js über .NET**](https://products.aspose.com/slides/de/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie Ihrem Node.js-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die Quelldateien PPS in Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ergebnis als SVG-Datei speichern.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konvertieren Sie PPS in andere unterstützte Formate" subTitle="Sie können PPS auch konvertieren und in anderen Dateiformaten speichern. Nachfolgend finden Sie alle unterstützten Formate" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-pptx/" name="PPS TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-ppt/" name="PPS TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-pdf/" name="PPS TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-html/" name="PPS TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-png/" name="PPS TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-bmp/" name="PPS TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-jpg/" name="PPS TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-fodp/" name="PPS TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-gif/" name="PPS TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-odp/" name="PPS TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-otp/" name="PPS TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-pot/" name="PPS TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-potm/" name="PPS TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-potx/" name="PPS TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-ppsm/" name="PPS TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-ppsx/" name="PPS TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-pptm/" name="PPS TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-net/conversion/pps-to-tiff/" name="PPS TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
