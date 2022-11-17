---
title: Konvertera PNG till JPG i Java
url: /sv/java/conversion/png-to-jpg/
keywords: PNG till JPG, Konvertera PNG till JPG, Java API, Java Library, PNG, JPG
description: Konvertera PNG till JPG i Java. Använd Java-bibliotekets API för att konvertera PNG-filer till JPGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertera PNG till JPG i Java" h2="Höghastighets- och plattformsoberoende Java-bibliotek som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera PNG till JPG i Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/sv/java/) är ett kraftfullt Java-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera PNG till JPG. Genom att använda **Aspose.Slides för Java** kan alla utvecklare eller applikationer konvertera PNG till JPG-filer med bara några rader Java-kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för Java snabbt PNG-filer till JPG-filformat. Aspose PowerPoint-bibliotek låter dig konvertera PNG till JPG och många andra filformat

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera PNG till JPG med Java" %}}
För att konvertera PNG till JPG måste du skapa en presentation från filen PNG och spara den som JPG.

{{% blocks/products/pf/agp/code-block title="Java-kod för att konvertera PNG till JPG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "jpeg", new File("image_java_" + index + ".jpg"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hur man konverterar PNG till JPG med Aspose.Slides för Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att konvertera PNG till JPG i Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera [**Aspose.Slides for Java**](https://products.aspose.com/slides/sv/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en biblioteksreferens (importera biblioteket) till ditt Java-projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öppna källfilerna PNG i Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet som JPG-fil.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konvertera PNG till andra format som stöds" subTitle="Du kan också konvertera PNG och spara till andra filformat. Se alla format som stöds nedan" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}