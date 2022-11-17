---
title: Converteer Image naar PDF in Java
url: /nl/java/conversion/image-to-pdf/
keywords: Image naar PDF, Converteer Image naar PDF, Java API, Java Library, Image, PDF
description: Converteer Image naar PDF in Java. Gebruik de Java-bibliotheek-API om Image-bestanden naar PDF-bestanden te converteren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converteer Image naar PDF in Java" h2="Snelle en platformonafhankelijke Java-bibliotheek die helpt bij het ontwikkelen van toepassingen met de mogelijkheid om Microsoft PowerPoint- en OpenOffice-presentatiebestanden te maken, samen te voegen, te inspecteren of te converteren zonder het gebruik van software zoals Microsoft of Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converteer Image naar PDF in Java" %}}

[**Aspose.Slides voor Java**](https://products.aspose.com/slides/nl/java/) is een krachtige Java-bibliotheek voor het maken en manipuleren van presentatiebestanden. Bovendien biedt het flexibele manieren om Image naar PDF te converteren. Met **Aspose.Slides voor Java** kan elke ontwikkelaar of toepassing Image naar PDF bestanden converteren met slechts een paar regels Java-code.

Aspose.Slides voor Java is een moderne documentverwerkings-API en exporteert snel Image-bestanden naar PDF-bestandsindelingen. Met de Aspose PowerPoint-bibliotheek kunt u Image naar PDFs en vele andere bestandsindelingen converteren

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer Image naar PDF met behulp van Java" %}}
Om de Image naar PDF te converteren, moet u een presentatie maken van het Image-bestand en deze opslaan als PDF.

{{% blocks/products/pf/agp/code-block title="Java-code voor het converteren van Image naar PDF" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Hoe Image naar PDF te converteren met Aspose.Slides voor Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om Image naar PDF in Java te converteren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installeer [**Aspose.Slides voor Java**](https://products.aspose.com/slides/nl/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een bibliotheekreferentie toe (importeer de bibliotheek) aan uw Java-project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open de bronbestanden Image in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op als PDF bestand.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converteer Image naar andere ondersteunde formaten" subTitle="U kunt Image ook converteren en opslaan in andere bestandsindelingen. Bekijk hieronder alle ondersteunde formaten" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}