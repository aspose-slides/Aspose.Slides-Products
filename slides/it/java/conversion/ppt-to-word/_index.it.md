---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converti PPT in Word in Java
url: /it/java/conversion/ppt-to-word/
keywords: Converti PPT in Word, PPT in Word, PPT in DOC, PowerPoint in Word, API Java, libreria Java
description: Converti PPT in Word in Java. Usa l'API della libreria Java per convertire PowerPoint in Word
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converti PPT in Word in Java" h2="Potente API Java multipiattaforma per convertire PowerPoint in Word utilizzando il codice Java senza Microsoft PowerPoint o Office" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti PowerPoint in Word in Java" variant="code" %}}

Puoi convertire rapidamente PPT in Word con poche righe di codice

{{< blocks/products/pf/slides-design-update-10-2026/code title="Codice Java per convertire PowerPoint in Word" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converti PowerPoint in Word utilizzando Aspose.Slides e Aspose.Words" %}}

[**Aspose.Slides per Java**](https://products.aspose.com/slides/it/java/) e [**Aspose.Words per Java**](https://products.aspose.com/ words/java/) sono potenti librerie Java utilizzate per manipolare e convertire presentazioni PowerPoint, documenti Word e altri file. Quando converti PowerPoint in Word, stai essenzialmente spostando il contenuto delle diapositive di una presentazione nelle pagine di un documento Word.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Come convertire PPT in Word" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installa **Aspose.Slides per Java** e **Aspose.Words per Java**{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Crea un'istanza della classe Presentation e della classe Doc.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carica la presentazione PPT che desideri convertire in Word.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Genera immagini e testi basati sui contenuti delle diapositive.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salva il documento Word risultante.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Convertitore online gratuito"
  description="[Come convertire PPT in HTML in Python](https://products.aspose.com/slides/it/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Altre conversioni supportate" subTitle="Puoi anche convertire PowerPoint in file in altri formati" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/it/java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
