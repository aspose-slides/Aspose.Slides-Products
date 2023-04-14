---
title: Konvertera PPTX till Word i Java
url: /sv/java/conversion/pptx-to-word/
keywords: Konvertera PPTX till Word, PPTX till Word, PPTX till DOC, PowerPoint till Word, Java API, Java Library
description: Konvertera PPTX till Word i Java. Använd Java-bibliotekets API för att konvertera PowerPoint till Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera PPTX till Word i Java" h2="Kraftfull plattformsoberoende Java API för att konvertera PowerPoint till Word med Java-kod utan Microsoft PowerPoint eller Office" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera PowerPoint till Word med Aspose.Slides och Aspose.Words" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/sv/java/) och [**Aspose.Words for Java**](https://products.aspose.com/ words/java/) är kraftfulla Java-bibliotek som används för att manipulera och konvertera PowerPoint-presentationer, Word-dokument och andra filer. När du konverterar PowerPoint till Word flyttar du i huvudsak innehållet i en presentations bilder till sidor i ett Word-dokument.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Konvertera PowerPoint till Word i Java" %}}
Du kan konvertera PPTX till Word snabbt med bara några rader kod

{{% blocks/products/pf/agp/code-block title="Java-kod för att konvertera PowerPoint till Word" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar PPTX till Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installera **Aspose.Slides för Java** och **Aspose.Words för Java** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skapa en instans av klassen Presentation och Doc-klassen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPTX-presentationen du vill konvertera till Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skapa bilder och texter baserat på bildernas innehåll.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara det resulterande Word-dokumentet.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Gratis onlinekonverterare" sectionDescription="[Hur man konverterar PPT till HTML i Python](https://products.aspose.com/slides/sv/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera PowerPoint till filer i andra format" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}