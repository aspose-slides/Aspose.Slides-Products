---
title: Konvertera HTML till PNG i Java
url: /sv/java/conversion/html-to-png/
keywords: HTML till PNG, Konvertera HTML till PNG, Java API, Java Library, HTML, PNG
description: Konvertera HTML till PNG i Java. Använd Java-bibliotekets API för att konvertera HTML-filer till PNGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera HTML till PNG i Java" h2="Höghastighets- och plattformsoberoende Java-bibliotek som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera HTML till PNG i Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/sv/java/) är ett kraftfullt Java-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera HTML till PNG. Genom att använda **Aspose.Slides för Java** kan alla utvecklare eller applikationer konvertera HTML till PNG-filer med bara några rader Java-kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för Java snabbt HTML-filer till PNG-filformat. Aspose PowerPoint-bibliotek låter dig konvertera HTML till PNG och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera HTML till PNG med Java" %}}
För att konvertera HTML till PNG måste du skapa en presentation från filen HTML och spara den som PNG.

{{% blocks/products/pf/agp/code-block title="Java-kod för att konvertera HTML till PNG" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar HTML till PNG med Aspose.Slides för Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att konvertera HTML till PNG i Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides for Java**](https://products.aspose.com/slides/sv/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt Java-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilerna HTML i Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som PNG-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera HTML till andra format som stöds" subTitle="Du kan också konvertera HTML och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}