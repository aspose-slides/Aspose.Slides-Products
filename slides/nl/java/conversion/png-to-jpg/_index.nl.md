---
title: Converteer PNG naar JPG in Java
url: /nl/java/conversion/png-to-jpg/
keywords: PNG naar JPG, Converteer PNG naar JPG, Java API, Java Library, PNG, JPG
description: Converteer PNG naar JPG in Java. Gebruik de Java-bibliotheek-API om PNG-bestanden naar JPG-bestanden te converteren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converteer PNG naar JPG in Java" h2="Snelle en platformonafhankelijke Java-bibliotheek die helpt bij het ontwikkelen van toepassingen met de mogelijkheid om Microsoft PowerPoint- en OpenOffice-presentatiebestanden te maken, samen te voegen, te inspecteren of te converteren zonder het gebruik van software zoals Microsoft of Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converteer PNG naar JPG in Java" %}}

[**Aspose.Slides voor Java**](https://products.aspose.com/slides/nl/java/) is een krachtige Java-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om PNG naar JPG te converteren. Met **Aspose.Slides voor Java** kan elke ontwikkelaar of toepassing PNG naar JPG bestanden converteren met slechts een paar regels Java-code.

Aspose.Slides voor Java is een moderne documentverwerkings-API en exporteert snel PNG-bestanden naar JPG-bestandsindelingen. Met de Aspose PowerPoint-bibliotheek kunt u PNG naar JPGs en vele andere bestandsindelingen converteren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer PNG naar JPG met behulp van Java" %}}
Om de PNG naar JPG te converteren, moet u een presentatie maken van het PNG-bestand en deze opslaan als JPG.

{{% blocks/products/pf/agp/code-block title="Java-code voor het converteren van PNG naar JPG" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Hoe PNG naar JPG te converteren met Aspose.Slides voor Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om PNG naar JPG in Java te converteren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installeer [**Aspose.Slides voor Java**](https://products.aspose.com/slides/nl/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een bibliotheekreferentie toe (importeer de bibliotheek) aan uw Java-project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open de bronbestanden PNG in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op als JPG bestand.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converteer PNG naar andere ondersteunde formaten" subTitle="U kunt PNG ook converteren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}