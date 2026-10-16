---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertera PNG till SVG i Java
url: /sv/java/conversion/png-to-svg/
keywords: PNG till SVG, Konvertera PNG till SVG, Java API, Java Library, PNG, SVG
description: Konvertera PNG till SVG i Java. Använd Java-bibliotekets API för att konvertera PNG-filer till SVGs
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertera PNG till SVG i Java" h2="Höghastighets- och plattformsoberoende Java-bibliotek som hjälper till att utveckla applikationer med möjligheten att skapa, slå samman, inspektera eller konvertera Microsoft PowerPoint- och OpenOffice-presentationsfiler utan användning av någon programvara som Microsoft eller Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera PNG till SVG med Java" variant="code" %}}

För att konvertera PNG till SVG måste du skapa en presentation från filen PNG och spara den som SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java-kod för att konvertera PNG till SVG" >}}
```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);

        FileOutputStream fileStream = new FileOutputStream("slide-" + index + ".svg");
        try {
            slide.writeAsSvg(fileStream);
        } finally {
            fileStream.close();
        }
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertera PNG till SVG i Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/sv/java/) är ett kraftfullt Java-bibliotek för att skapa och manipulera presentationsfiler. Dessutom ger det flexibla sätt att konvertera PNG till SVG. Genom att använda **Aspose.Slides för Java** kan alla utvecklare eller applikationer konvertera PNG till SVG-filer med bara några rader Java-kod.

Som ett modernt dokumentbearbetnings-API exporterar Aspose.Slides för Java snabbt PNG-filer till SVG-filformat. Aspose PowerPoint-bibliotek låter dig konvertera PNG till SVG och många andra filformat

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man konverterar PNG till SVG med Aspose.Slides för Java API" intro="Det här är stegen för att konvertera PNG till SVG i Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera [**Aspose.Slides for Java**](https://products.aspose.com/slides/sv/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till en biblioteksreferens (importera biblioteket) till ditt Java-projekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Öppna källfilerna PNG i Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara resultatet som SVG-fil.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis onlinekonverterare"
  description="[Hur man konverterar PPT till HTML i Python](https://products.aspose.com/slides/sv/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konvertera PNG till andra format som stöds" subTitle="Du kan också konvertera PNG och spara till andra filformat. Se alla format som stöds nedan" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
