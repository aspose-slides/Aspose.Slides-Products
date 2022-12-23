---
title: PDF bewerken in Java
url: /nl/java/editor/pdf/
keywords: PDF, PDF, Java API, Java-bibliotheek bewerken
description: PDF bewerken in Java. Gebruik Java-bibliotheek-API om PDF-document te bewerken
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PDF bewerken in Java" h2="Snelle en platformonafhankelijke Java-bibliotheek voor het bewerken van PDF met behulp van Java-code" >}}

{{% blocks/products/pf/feature-page-section h2="PDF bewerken met Aspose.Slides" %}}

[**Aspose.Slides voor Java**](https://products.aspose.com/slides/nl/java/) is een krachtige Java-bibliotheek die wordt gebruikt voor het manipuleren en bewerken van presentaties, PDF-documenten en andere bestanden. U kunt een PDF-document bewerken door er een nieuwe regel tekst aan toe te voegen. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PDF bewerken in Java" %}}
Met [**Aspose.Slides for Java**](https://products.aspose.com/slides/nl/java/) kunt u met slechts een paar regels code een nieuwe regel tekst toevoegen aan een PDF-document.

{{% blocks/products/pf/agp/code-block title="Java-code voor het bewerken van pdf" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("document.pdf");

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("document.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Hoe PDF in Java te bewerken" >}}


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
Laad het PDF-document dat u wilt bewerken.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg een nieuwe regel tekst toe.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla het gewijzigde PDF-bestand op.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Bewerk andere bestanden" subTitle="U kunt ook bestanden in andere indelingen bewerken" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}