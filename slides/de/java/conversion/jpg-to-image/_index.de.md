---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie JPG in Image in Java
url: /de/java/conversion/jpg-to-image/
keywords: JPG in Image, Konvertiere JPG in Image, Java-API, Java-Bibliothek, JPG, Image
description: Konvertieren Sie JPG in Image in Java. Verwenden Sie die Java-Bibliotheks-API, um JPG-Dateien in Images zu konvertieren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie JPG in Image in Java" h2="Hochgeschwindigkeits- und plattformübergreifende Java-Bibliothek, die bei der Entwicklung von Anwendungen mit der Fähigkeit hilft, Microsoft PowerPoint- und OpenOffice-Präsentationsdateien ohne die Verwendung von Software wie Microsoft oder Open Office, Adobe PDF zu erstellen, zusammenzuführen, zu überprüfen oder zu konvertieren." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie JPG in Image mit Java" variant="code" %}}

Um das JPG in Image zu konvertieren, müssen Sie eine Präsentation aus der JPG-Datei erstellen und sie als Image speichern.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java-Code zum Konvertieren von JPG in Image" >}}
```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie JPG in Image in Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/de/java/) ist eine leistungsstarke Java-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten, JPG in Image zu konvertieren. Mit **Aspose.Slides for Java** kann jeder Entwickler oder jede Anwendung JPG-Dateien mit nur wenigen Zeilen Java-Code in Image-Dateien konvertieren.

Als moderne Dokumentverarbeitungs-API exportiert Aspose.Slides für Java schnell JPG-Dateien in Image-Dateiformate. Mit der Aspose PowerPoint-Bibliothek können Sie JPG in Images und viele andere Dateiformate konvertieren

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie JPG in Image mit Aspose.Slides for Java API" intro="Dies sind die Schritte zum Konvertieren von JPG in Image in Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie [**Aspose.Slides für Java**](https://products.aspose.com/slides/de/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie Ihrem Java-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öffnen Sie die Quelldateien JPG in Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ergebnis als Image-Datei speichern.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Kostenloser Online-Konverter"
  description="[So konvertieren Sie PPT in HTML in Python](https://products.aspose.com/slides/de/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konvertieren Sie JPG in andere unterstützte Formate" subTitle="Sie können JPG auch konvertieren und in anderen Dateiformaten speichern. Siehe unten alle unterstützten Formate" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
