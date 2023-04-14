---
title: Převést PPTX na Word v Javě
url: /cs/java/conversion/pptx-to-word/
keywords: Převod PPTX do Wordu, PPTX do Wordu, PPTX do DOC, PowerPoint do Wordu, Java API, Java Library
description: Převést PPTX na Word v Javě. K převodu PowerPointu do Wordu použijte API knihovny Java
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převést PPTX na Word v Javě" h2="Výkonné multiplatformní Java API pro převod PowerPointu do Wordu pomocí kódu Java bez aplikace Microsoft PowerPoint nebo Office" >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte PowerPoint do Wordu pomocí Aspose.Slides a Aspose.Words" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/) a [**Aspose.Words for Java**](https://products.aspose.com/ words/java/) jsou výkonné Java knihovny používané k manipulaci a převodu PowerPoint prezentací, dokumentů Word a dalších souborů. Při převodu PowerPointu do Wordu v podstatě přesouváte obsah snímků prezentace na stránky v dokumentu Wordu.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Převeďte PowerPoint do Wordu v Javě" %}}
PPTX můžete rychle převést na Word pomocí několika řádků kódu

{{% blocks/products/pf/agp/code-block title="Java kód pro převod PowerPointu do Wordu" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Jak převést PPTX na Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte **Aspose.Slides for Java** a **Aspose.Words for Java** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvořte instanci třídy Presentation a třídy Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte prezentaci PPTX, kterou chcete převést do aplikace Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvářejte obrázky a texty na základě obsahu snímků.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte výsledný dokument aplikace Word.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Zdarma online konvertor" sectionDescription="[Jak převést PPT na HTML v Pythonu](https://products.aspose.com/slides/cs/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="PowerPoint můžete také převést na soubory v jiných formátech" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}