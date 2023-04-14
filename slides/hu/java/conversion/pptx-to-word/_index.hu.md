---
title: Konvertálja a PPTX-t Word-be Java nyelven
url: /hu/java/conversion/pptx-to-word/
keywords: PPTX konvertálása Word-be, PPTX Word-be, PPTX konvertálása DOC-ba, PowerPoint Word-be, Java API, Java Library
description: Konvertálja a PPTX-t Word-be Java nyelven. Használja a Java könyvtár API-t a PowerPoint Wordvé konvertálásához
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertálja a PPTX-t Word-be Java nyelven" h2="Hatékony, többplatformos Java API a PowerPoint Word-be konvertálásához Java kóddal Microsoft PowerPoint vagy Office nélkül" >}}

{{% blocks/products/pf/feature-page-section h2="A PowerPoint konvertálása Word-be az Aspose.Slides és az Aspose.Words használatával" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/hu/java/) és [**Aspose.Words for Java**](https://products.aspose.com/ Words/java/) hatékony Java-könyvtárak, amelyek PowerPoint-bemutatók, Word-dokumentumok és egyéb fájlok kezelésére és konvertálására szolgálnak. A PowerPoint Word-be konvertálásakor lényegében a prezentáció diákjainak tartalmát egy Word-dokumentum oldalaira helyezi át.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="A PowerPoint konvertálása Word-be Java nyelven" %}}
Néhány sornyi kóddal gyorsan konvertálhatja a PPTX-et Word-be

{{% blocks/products/pf/agp/code-block title="Java kód a PowerPoint Word-be konvertálásához" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Hogyan lehet PPTX-et Word-be konvertálni" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Az **Aspose.Slides for Java** és az **Aspose.Words for Java** telepítése 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hozzon létre egy példányt a Presentation osztályból és a Doc osztályból.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be a Word-be konvertálni kívánt PPTX-prezentációt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A diák tartalma alapján képeket és szövegeket generál.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Mentse el a kapott Word-dokumentumot.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ingyenes online konverter" sectionDescription="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A PowerPointot más formátumú fájlokká is konvertálhatja" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}