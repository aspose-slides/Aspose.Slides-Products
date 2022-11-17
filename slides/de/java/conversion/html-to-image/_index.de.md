---
title: Konvertieren Sie HTML in Image in Java
url: /de/java/conversion/html-to-image/
keywords: HTML in Image, Konvertiere HTML in Image, Java-API, Java-Bibliothek, HTML, Image
description: Konvertieren Sie HTML in Image in Java. Verwenden Sie die Java-Bibliotheks-API, um HTML-Dateien in Images zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie HTML in Image in Java" h2="Hochgeschwindigkeits- und plattformübergreifende Java-Bibliothek, die bei der Entwicklung von Anwendungen mit der Fähigkeit hilft, Microsoft PowerPoint- und OpenOffice-Präsentationsdateien ohne die Verwendung von Software wie Microsoft oder Open Office, Adobe PDF zu erstellen, zusammenzuführen, zu überprüfen oder zu konvertieren." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie HTML in Image in Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/de/java/) ist eine leistungsstarke Java-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten, HTML in Image zu konvertieren. Mit **Aspose.Slides for Java** kann jeder Entwickler oder jede Anwendung HTML-Dateien mit nur wenigen Zeilen Java-Code in Image-Dateien konvertieren.

Als moderne Dokumentverarbeitungs-API exportiert Aspose.Slides für Java schnell HTML-Dateien in Image-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie HTML in Images und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie HTML in Image mit Java" %}}
Um das HTML in Image zu konvertieren, müssen Sie eine Präsentation aus der HTML-Datei erstellen und sie als Image speichern.

{{% blocks/products/pf/agp/code-block title="Java-Code zum Konvertieren von HTML in Image" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    TextReader tr = new StreamReader("file.html");
    pres.getSlides().addFromHtml(tr);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So konvertieren Sie HTML in Image mit Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Konvertieren von HTML in Image in Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie [**Aspose.Slides für Java**](https://products.aspose.com/slides/de/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Ihrem Java-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öffnen Sie die Quelldateien HTML in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis als Image-Datei speichern.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertieren Sie HTML in andere unterstützte Formate" subTitle="Sie können HTML auch konvertieren und in anderen Dateiformaten speichern. Siehe unten alle unterstützten Formate" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}