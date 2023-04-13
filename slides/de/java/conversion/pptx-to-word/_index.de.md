---
title: Konvertieren Sie PPTX in Word in Java
url: /de/java/conversion/pptx-to-word/
keywords: Konvertieren Sie PPTX in Word, PPTX in Word, PPTX in DOC, PowerPoint in Word, Java-API, Java-Bibliothek
description: Konvertieren Sie PPTX in Word in Java. Verwenden Sie die Java-Bibliotheks-API, um PowerPoint in Word zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie PPTX in Word in Java" h2="Leistungsstarke plattformübergreifende Java-API zum Konvertieren von PowerPoint in Word mithilfe von Java-Code ohne Microsoft PowerPoint oder Office" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie PowerPoint mit Aspose.Slides und Aspose.Words in Word" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/de/java/) und [**Aspose.Words for Java**](https://products.aspose.com/ words/java/) sind leistungsstarke Java-Bibliotheken zum Bearbeiten und Konvertieren von PowerPoint-Präsentationen, Word-Dokumenten und anderen Dateien. Wenn Sie PowerPoint in Word konvertieren, verschieben Sie im Wesentlichen die Inhalte der Folien einer Präsentation auf Seiten in einem Word-Dokument.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PowerPoint in Word in Java" %}}
Mit nur wenigen Codezeilen können Sie PPTX schnell in Word konvertieren

{{% blocks/products/pf/agp/code-block title="Java-Code zum Konvertieren von PowerPoint in Word" offSpacer="true" %}}
```java
Presentation pres = new Presentation(inputPres);
try {
    Document doc = new Document();
    DocumentBuilder builder = new DocumentBuilder(doc);
    for (ISlide slide : pres.getSlides())
    {
        // generates and inserts slide image
        BufferedImage bitmap = slide.getThumbnail(1, 1);

        builder.insertImage(bitmap);

        // inserts slide's texts
        for (IShape shape : slide.getShapes())
        {
            if (shape instanceof AutoShape)
            {
                builder.writeln(((AutoShape)shape).getTextFrame().getText());
            }
        }

        builder.insertBreak(BreakType.PAGE_BREAK);
    }
    doc.save(outputDoc);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="So konvertieren Sie PPTX in Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie **Aspose.Slides für Java** und **Aspose.Words für Java** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Erstellen Sie eine Instanz der Presentation-Klasse und der Doc-Klasse.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie die PPTX-Präsentation, die Sie in Word konvertieren möchten.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Generieren Sie Bilder und Texte basierend auf den Inhalten der Folien.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie das resultierende Word-Dokument.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Kostenloser Online-Konverter" sectionDescription="[So konvertieren Sie PPT in HTML in Python](https://products.aspose.com/slides/de/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können PowerPoint auch in Dateien in anderen Formaten konvertieren" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}