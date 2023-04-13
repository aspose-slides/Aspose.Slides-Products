---
title: Konvertieren Sie JPG in PPT in Java
url: /de/java/conversion/jpg-to-ppt/
keywords: Konvertieren Sie JPG in PPT, JPG in PPT, PowerPoint, JPG, PPT, Java-API, Java-Bibliothek
description: Konvertieren Sie JPG in PPT in Java. Verwenden Sie die Java-Bibliotheks-API, um JPG-Bilder in PowerPoint zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie JPG in PPT in Java" h2="Leistungsstarke plattformübergreifende Java-API zum Konvertieren von JPG in PPT mithilfe von Java-Code" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie JPG mit Aspose.Slides in PPT" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/de/java/) ist eine leistungsstarke Java-Bibliothek zum Erstellen, Konvertieren und Bearbeiten von PowerPoint-Präsentationen, PDFs, HTML-Dokumenten und anderen Dateien. Wenn Sie JPG in PPT konvertieren, erstellen Sie im Wesentlichen eine PowerPoint-Präsentation, die Folien enthält, die auf JPG-Bildern basieren.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie JPG in PPT in Java" %}}
Mit [**Aspose.Slides for Java**](https://products.aspose.com/slides/de/java/) können Sie JPG-Bilder mit nur wenigen Codezeilen in eine PowerPoint-Präsentation konvertieren:

{{% blocks/products/pf/agp/code-block title="Java-Code zum Konvertieren von JPG in PPT" offSpacer="true" %}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

	pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
	if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="So konvertieren Sie JPG in PPT in Java" >}}


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
Laden Sie das JPG-Bild, das Sie in PPT konvertieren möchten.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie die resultierende Datei als PPT-Präsentation.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Kostenloser Online-Konverter" sectionDescription="[So konvertieren Sie PPT in HTML in Python](https://products.aspose.com/slides/de/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte PowerPoint-Konvertierungen" subTitle="Sie können auch Dateien in anderen Formaten in PowerPoint konvertieren" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}