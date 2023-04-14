---
title: Converteer PNG naar PPT in Java
url: /nl/java/conversion/png-to-ppt/
keywords: Converteer PNG naar PPT, PNG naar PPT, PowerPoint, PNG, PPT, Java API, Java Library
description: Converteer PNG naar PPT in Java. Gebruik de Java-bibliotheek-API om PNG-afbeeldingen naar PowerPoint te converteren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converteer PNG naar PPT in Java" h2="Krachtige cross-platform Java API voor het converteren van PNG naar PPT met behulp van Java-code" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer PNG naar PPT met Aspose.Slides" %}}

[**Aspose.Slides voor Java**](https://products.aspose.com/slides/nl/java/) is een krachtige Java-bibliotheek die wordt gebruikt om PowerPoint-presentaties, pdf's, HTML-documenten en andere bestanden. Wanneer u PNG naar PPT converteert, maakt u in wezen een PowerPoint-presentatie met dia's op basis van PNG-afbeeldingen.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Converteer PNG naar PPT in Java" %}}
Met [**Aspose.Slides for Java**](https://products.aspose.com/slides/nl/java/) kunt u een PNG-afbeelding converteren naar een PowerPoint-presentatie met slechts een paar regels code:

{{% blocks/products/pf/agp/code-block title="Java-code voor het converteren van PNG naar PPT" offSpacer="true" %}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

	pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
	if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hoe PNG naar PPT in Java te converteren" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installeer **Aspose.Slides voor Java**. Zie [**Installatie**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg de bibliotheek toe als referentie in uw project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Maak een instantie van de klasse Presentatie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad de PNG-afbeelding die u naar PPT wilt converteren.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla het resulterende bestand op als een PPT-presentatie.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Gratis online converter" sectionDescription="[Hoe PPT naar HTML in Python te converteren](https://products.aspose.com/slides/nl/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde PowerPoint-conversies" subTitle="U kunt ook bestanden in andere formaten naar PowerPoint converteren" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}