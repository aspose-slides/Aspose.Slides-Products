---
title: Converti PPT in Word in Java
url: /it/java/conversion/ppt-to-word/
keywords: Converti PPT in Word, PPT in Word, PPT in DOC, PowerPoint in Word, API Java, libreria Java
description: Converti PPT in Word in Java. Usa l'API della libreria Java per convertire PowerPoint in Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converti PPT in Word in Java" h2="Potente API Java multipiattaforma per convertire PowerPoint in Word utilizzando il codice Java senza Microsoft PowerPoint o Office" >}}

{{% blocks/products/pf/feature-page-section h2="Converti PowerPoint in Word utilizzando Aspose.Slides e Aspose.Words" %}}

[**Aspose.Slides per Java**](https://products.aspose.com/slides/it/java/) e [**Aspose.Words per Java**](https://products.aspose.com/ words/java/) sono potenti librerie Java utilizzate per manipolare e convertire presentazioni PowerPoint, documenti Word e altri file. Quando converti PowerPoint in Word, stai essenzialmente spostando il contenuto delle diapositive di una presentazione nelle pagine di un documento Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Converti PowerPoint in Word in Java" %}}
Puoi convertire rapidamente PPT in Word con poche righe di codice

{{% blocks/products/pf/agp/code-block title="Codice Java per convertire PowerPoint in Word" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Come convertire PPT in Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installa **Aspose.Slides per Java** e **Aspose.Words per Java** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea un'istanza della classe Presentation e della classe Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica la presentazione PPT che desideri convertire in Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Genera immagini e testi basati sui contenuti delle diapositive.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il documento Word risultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertitore online gratuito" sectionDescription="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire PowerPoint in file in altri formati" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}