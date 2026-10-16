---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converteer JPG naar PNG in Java
url: /nl/java/conversion/jpg-to-png/
keywords: JPG naar PNG, Converteer JPG naar PNG, Java API, Java Library, JPG, PNG
description: Converteer JPG naar PNG in Java. Gebruik de Java-bibliotheek-API om JPG-bestanden naar PNG-bestanden te converteren
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converteer JPG naar PNG in Java" h2="Snelle en platformonafhankelijke Java-bibliotheek die helpt bij het ontwikkelen van toepassingen met de mogelijkheid om Microsoft PowerPoint- en OpenOffice-presentatiebestanden te maken, samen te voegen, te inspecteren of te converteren zonder het gebruik van software zoals Microsoft of Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer JPG naar PNG met behulp van Java" variant="code" %}}

Om de JPG naar PNG te converteren, moet u een presentatie maken van het JPG-bestand en deze opslaan als PNG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java-code voor het converteren van JPG naar PNG" >}}
```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converteer JPG naar PNG in Java" %}}

[**Aspose.Slides voor Java**](https://products.aspose.com/slides/nl/java/) is een krachtige Java-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om JPG naar PNG te converteren. Met **Aspose.Slides voor Java** kan elke ontwikkelaar of toepassing JPG naar PNG bestanden converteren met slechts een paar regels Java-code.

Aspose.Slides voor Java is een moderne documentverwerkings-API en exporteert snel JPG-bestanden naar PNG-bestandsindelingen. Met de Aspose PowerPoint-bibliotheek kunt u JPG naar PNGs en vele andere bestandsindelingen converteren

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hoe JPG naar PNG te converteren met Aspose.Slides voor Java API" intro="Dit zijn de stappen om JPG naar PNG in Java te converteren." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installeer [**Aspose.Slides voor Java**](https://products.aspose.com/slides/nl/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Voeg een bibliotheekreferentie toe (importeer de bibliotheek) aan uw Java-project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open de bronbestanden JPG in Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sla resultaat op als PNG bestand.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Gratis online converter"
  description="[Hoe PPT naar HTML in Python te converteren](https://products.aspose.com/slides/nl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Converteer JPG naar andere ondersteunde formaten" subTitle="U kunt JPG ook converteren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/nl/java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
