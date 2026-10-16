---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie PPSM in PNG in Node.js
url: /de/nodejs-java/conversion/ppsm-to-png/
keywords: PPSM zu PNG, Konvertieren von PPSM zu PNG, Node.js API, Node.js-Bibliothek, PPSM, PNG
description: Konvertieren Sie PPSM in PNG in Node.js. Verwenden Sie die Node.js-Bibliotheks-API, um PPSM-Dateien in PNGs zu konvertieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie PPSM in PNG in Node.js" h2="Aspose.Slides für Node.js über Java ist eine leistungsstarke und benutzerfreundliche Bibliothek, mit der Sie PowerPoint-Präsentationen in verschiedene Formate in Node.js konvertieren können. Es unterstützt alle Präsentationselemente und -formate und bietet eine umfangreiche API für den Zugriff und die Änderung dieser. Außerdem können Sie Ihre Folien zur weiteren Verarbeitung oder Weitergabe in verschiedene Formate exportieren." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie PPSM in PNG mit Node.js" variant="code" %}}

Um das PPSM in PNG zu konvertieren, müssen Sie eine Präsentation aus der PPSM-Datei erstellen und diese als PNG speichern.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js-Code zum Konvertieren von PPSM in PNG" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppsm");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".png");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "png", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie PPSM in PNG in Node.js" %}}

[**Aspose.Slides für Node.js über Java**](https://products.aspose.com/slides/de/nodejs-java/) ist eine leistungsstarke Node.js-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten zur Konvertierung von PPSM in PNG. Mit **Aspose.Slides für Node.js über Java** kann jeder Entwickler oder jede Anwendung mit nur wenigen Codezeilen PPSM-Dateien in PNG-Dateien konvertieren.

Als moderne API zur Dokumentenverarbeitung exportiert Aspose.Slides für Node.js schnell PPSM-Dateien in PNG-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie PPSM in PNGs und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie PPSM in PNG mithilfe von Aspose.Slides für Node.js über die Java-API" intro="Um PPSM in PNG mit Aspose.Slides für Node.js über Java zu konvertieren, müssen Sie das Paket in Ihre JavaScript-Datei importieren und eine Instanz der Presentation-Klasse erstellen. Die Presentation-Klasse stellt ein PowerPoint-Dokument dar und stellt Methoden für den Zugriff und die Bearbeitung seiner Elemente bereit." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie [**Aspose.Slides für Node.js über Java**](https://products.aspose.com/slides/de/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie Ihrem Node.js-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die Quelldateien PPSM in Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ergebnis als PNG-Datei speichern.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konvertieren Sie PPSM in andere unterstützte Formate" subTitle="Sie können PPSM auch konvertieren und in anderen Dateiformaten speichern. Nachfolgend finden Sie alle unterstützten Formate" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-bmp/" name="PPSM TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-jpg/" name="PPSM TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-potm/" name="PPSM TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-svg/" name="PPSM TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/nodejs-java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
