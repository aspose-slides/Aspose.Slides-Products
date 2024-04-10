---
title: Konvertieren Sie PPTX in JPG in JavaScript
url: /de/nodejs-net/conversion/pptx-to-jpg/
keywords: PPTX zu JPG, Konvertieren von PPTX zu JPG, Node.js API, JavaScript-Bibliothek, PPTX, JPG
description: Konvertieren Sie PPTX in JPG in JavaScript. Verwenden Sie die Node.js-Bibliotheks-API, um PPTX-Dateien in JPG zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie PPTX in JPG in JavaScript" h2="Aspose.Slides für Node.js über .NET ist eine leistungsstarke und benutzerfreundliche Bibliothek, mit der Sie PowerPoint-Präsentationen in verschiedene Formate in JavaScript konvertieren können. Es unterstützt alle Präsentationselemente und -formate und bietet eine umfangreiche API für den Zugriff und die Änderung dieser. Außerdem können Sie Ihre Folien zur weiteren Verarbeitung oder Weitergabe in verschiedene Formate exportieren." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie PPTX in JPG in Node.js" %}}

[**Aspose.Slides für Node.js über .NET**](https://products.aspose.com/slides/de/nodejs-net/) ist eine leistungsstarke Node.js-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten zur Konvertierung von PPTX in JPG. Mit **Aspose.Slides für Node.js über .NET** kann jeder Entwickler oder jede Anwendung mit nur wenigen Codezeilen PPTX-Dateien in JPG-Dateien konvertieren.

Als moderne API zur Dokumentenverarbeitung exportiert Aspose.Slides für Node.js über .NET schnell PPTX-Dateien in JPG-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie PPTX in JPGs und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PPTX mit JavaScript in JPG" %}}
Um das PPTX in JPG zu konvertieren, müssen Sie eine Präsentation aus der PPTX-Datei erstellen und diese als JPG speichern.

{{% blocks/products/pf/agp/code-block title="JavaScript-Code zum Konvertieren von PPTX in JPG" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.pptx");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".jpg", ImageFormat.Jpeg); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So konvertieren Sie PPTX in JPG mit Aspose.Slides für Node.js über die .NET-API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Um PPTX in JPG mit Aspose.Slides für Node.js über .NET zu konvertieren, müssen Sie das Paket in Ihre JavaScript-Datei importieren und eine Instanz der Presentation-Klasse erstellen. Die Presentation-Klasse stellt ein PowerPoint-Dokument dar und stellt Methoden für den Zugriff und die Bearbeitung seiner Elemente bereit." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie [**Aspose.Slides für Node.js über .NET**](https://products.aspose.com/slides/de/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Ihrem Node.js-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öffnen Sie die Quelldateien PPTX in Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis als JPG-Datei speichern.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertieren Sie PPTX in andere unterstützte Formate" subTitle="Sie können PPTX auch konvertieren und in anderen Dateiformaten speichern. Nachfolgend finden Sie alle unterstützten Formate" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-ppt/" name="PPTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-fodp/" name="PPTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-odp/" name="PPTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-otp/" name="PPTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-pot/" name="PPTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-potm/" name="PPTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-potx/" name="PPTX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-pps/" name="PPTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}