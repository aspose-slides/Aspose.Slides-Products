---
title: Konvertieren Sie ODP in BMP in Node.js
url: /de/nodejs-java/conversion/odp-to-bmp/
keywords: ODP zu BMP, Konvertieren von ODP zu BMP, Node.js API, Node.js-Bibliothek, ODP, BMP
description: Konvertieren Sie ODP in BMP in Node.js. Verwenden Sie die Node.js-Bibliotheks-API, um ODP-Dateien in BMPs zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie ODP in BMP in Node.js" h2="Aspose.Slides für Node.js über Java ist eine leistungsstarke und benutzerfreundliche Bibliothek, mit der Sie PowerPoint-Präsentationen in verschiedene Formate in Node.js konvertieren können. Es unterstützt alle Präsentationselemente und -formate und bietet eine umfangreiche API für den Zugriff und die Änderung dieser. Außerdem können Sie Ihre Folien zur weiteren Verarbeitung oder Weitergabe in verschiedene Formate exportieren." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie ODP in BMP in Node.js" %}}

[**Aspose.Slides für Node.js über Java**](https://products.aspose.com/slides/de/nodejs-java/) ist eine leistungsstarke Node.js-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten zur Konvertierung von ODP in BMP. Mit **Aspose.Slides für Node.js über Java** kann jeder Entwickler oder jede Anwendung mit nur wenigen Codezeilen ODP-Dateien in BMP-Dateien konvertieren.

Als moderne API zur Dokumentenverarbeitung exportiert Aspose.Slides für Node.js schnell ODP-Dateien in BMP-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie ODP in BMPs und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie ODP in BMP mit Node.js" %}}
Um das ODP in BMP zu konvertieren, müssen Sie eine Präsentation aus der ODP-Datei erstellen und diese als BMP speichern.

{{% blocks/products/pf/agp/code-block title="Node.js-Code zum Konvertieren von ODP in BMP" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.odp");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".bmp");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "bmp", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So konvertieren Sie ODP in BMP mithilfe von Aspose.Slides für Node.js über die Java-API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Um ODP in BMP mit Aspose.Slides für Node.js über Java zu konvertieren, müssen Sie das Paket in Ihre JavaScript-Datei importieren und eine Instanz der Presentation-Klasse erstellen. Die Presentation-Klasse stellt ein PowerPoint-Dokument dar und stellt Methoden für den Zugriff und die Bearbeitung seiner Elemente bereit." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie [**Aspose.Slides für Node.js über Java**](https://products.aspose.com/slides/de/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Ihrem Node.js-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öffnen Sie die Quelldateien ODP in Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis als BMP-Datei speichern.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertieren Sie ODP in andere unterstützte Formate" subTitle="Sie können ODP auch konvertieren und in anderen Dateiformaten speichern. Nachfolgend finden Sie alle unterstützten Formate" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-pptx/" name="ODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-ppt/" name="ODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-pdf/" name="ODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-html/" name="ODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-png/" name="ODP TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-jpg/" name="ODP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-fodp/" name="ODP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-gif/" name="ODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-otp/" name="ODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-pot/" name="ODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-potm/" name="ODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-potx/" name="ODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-pps/" name="ODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-ppsm/" name="ODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-ppsx/" name="ODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-pptm/" name="ODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-svg/" name="ODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/nodejs-java/conversion/odp-to-tiff/" name="ODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}