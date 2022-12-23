---
title: Redigera PPT i Java
url: /sv/java/editor/ppt/
keywords: Redigera PPT, Redigera PowerPoint, PPT, PowerPoint, Java API, Java Library
description: Redigera PPT i Java. Använd Java-bibliotekets API för att redigera PowerPoint-presentation
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Redigera PPT i Java" h2="Höghastighets- och plattformsoberoende Java-bibliotek för redigering av PPT med Java-kod" >}}

{{% blocks/products/pf/feature-page-section h2="Redigera PPT med Aspose.Slides" %}}

[**Aspose.Slides för Java**](https://products.aspose.com/slides/sv/java/) är ett kraftfullt Java-bibliotek som används för att manipulera och redigera presentationer. Du kan redigera en PPT-presentation genom att lägga till en ny textrad till den. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Redigera PPT i Java" %}}
Med [**Aspose.Slides för Java**](https://products.aspose.com/slides/sv/java/) kan du lägga till en ny textrad till ett PPT-dokument med bara några rader kod.

{{% blocks/products/pf/agp/code-block title="Java-kod för redigering av PPT" offSpacer="true" %}}
```java

Presentation pres = new Presentation("pres.ppt");
try {
    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hur man redigerar PPT i Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installera **Aspose.Slides för Java**. Se [**Installation**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till biblioteket som referens i ditt projekt.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skapa en instans av klassen Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPT-presentationen du vill redigera.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lägg till en ny textrad.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara den ändrade PowerPoint-filen.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Redigera andra filer" subTitle="Du kan även redigera filer i andra format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}