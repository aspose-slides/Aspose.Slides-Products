---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Redigera HTML i Java
url: /sv/java/editor/html/
keywords: Redigera HTML, HTML, Java API, Java Library
description: Redigera HTML i Java. Använd Java library API för att redigera HTML-fil
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Redigera HTML i Java" h2="Höghastighets- och plattformsoberoende Java-bibliotek för redigering av HTML med Java-kod" related="PPT,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Redigera HTML i Java" variant="code" %}}

Med [**Aspose.Slides för Java**](https://products.aspose.com/slides/sv/java/) kan du lägga till en ny textrad i ett HTML-dokument med bara några rader kod.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java-kod för redigering av HTML" >}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        pres.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("page.html", SaveFormat.Html5);
} catch(IOException e) {
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Redigera HTML med Aspose.Slides" %}}

[**Aspose.Slides för Java**](https://products.aspose.com/slides/sv/java/) är ett kraftfullt Java-bibliotek som används för att manipulera och redigera presentationer, HTML-dokument och andra filer. Du kan redigera ett HTML-dokument genom att lägga till en ny textrad till det.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hur man redigerar HTML i Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installera **Aspose.Slides för Java**. Se [**Installation**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till biblioteket som referens i ditt projekt.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Skapa en instans av klassen Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ladda HTML-dokumentet du vill redigera.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lägg till en ny textrad.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den ändrade HTML-filen.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Redigera andra filer" subTitle="Du kan även redigera filer i andra format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/sv/java/editor/pdf/" name="Edit PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
