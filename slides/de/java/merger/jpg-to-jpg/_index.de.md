---
title: JPG-Bilder in Java zusammenführen
url: /de/java/merger/jpg-to-jpg/
keywords: JPG, JPEG zu JPG zusammenführen, JPG verbinden, JPG kombinieren, Java-API, Java-Bibliothek
description: JPG mit JPG in Java zusammenführen. Verwenden Sie die Java-Bibliotheks-API, um JPG-Dateien zu kombinieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="JPG in Java zusammenführen" h2="Hochgeschwindigkeits- und plattformübergreifende Java-Bibliothek zum Zusammenführen von JPG-Bildern mit Java-Code" >}}

{{% blocks/products/pf/feature-page-section h2="JPG mit Aspose.Slides zu JPG zusammenführen" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/de/java/) ist eine leistungsstarke Java-Bibliothek zum Zusammenführen und Bearbeiten von Präsentationen, Bildern und anderen Dateien. Wenn Sie JPG zu JPG zusammenführen, kombinieren Sie effektiv zwei Bilder, um ein Bild zu erhalten.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="JPG mit JPG in Java zusammenführen" %}}
Mit [**Aspose.Slides for Java**](https://products.aspose.com/slides/de/java/) können Sie JPG-Dateien schnell mit nur wenigen Codezeilen zusammenführen

{{% blocks/products/pf/agp/code-block title="Java-Code zum Zusammenführen von JPG zu JPG" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    IPPImage image1 = pres.getImages().addImage(Files.readAllBytes("image1.jpg"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image1);

    IPPImage image2 = pres.getImages().addImage(Files.readAllBytes("image2.jpg"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail();
        ImageIO.write(bufferedImage, "JPEG", new File("image_java_" + index + ".jpg"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="So führen Sie JPG in Java zusammen" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie **Aspose.Slides für Java**. Siehe [**Installation**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie die Bibliothek als Referenz in Ihrem Projekt hinzu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Erstellen Sie eine Instanz der Presentation-Klasse.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie die JPG-Dateien, die Sie als Bilderrahmen zusammenführen möchten.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie das resultierende JPG-Bild.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Andere Dateien zusammenführen" subTitle="Sie können auch Dateien in anderen Formaten kombinieren, um eine einzige Datei zu erhalten" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}