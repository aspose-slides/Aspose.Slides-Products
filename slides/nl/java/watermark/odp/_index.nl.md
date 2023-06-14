---
title: Watermerk toevoegen aan ODP presentatiebestanden met Java
url: /nl/java/watermark/odp/
keywords: Watermerk toevoegen ODP, Tekstwatermerk toevoegen ODP, Afbeeldingswatermerk toevoegen ODP
description: Java broncode voor het toevoegen van watermerk aan ODP presentatie.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Watermerk toevoegen aan presentatie ODP met behulp van Java" h2="Bouw uw eigen Java-apps om tekst- of afbeeldingswatermerken in PPT-, PPTX- of ODP-presentaties in te voegen met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Watermerk toevoegen aan presentatie ODP via Java" %}}
Met Aspose.Slides for Java kunt u een watermerk toevoegen aan de ODP-presentatie. Watermerken zijn een essentieel onderdeel van elke presentatie. Ze worden gebruikt om te voorkomen dat de inhoud van de presentatie zonder toestemming wordt gekopieerd of gebruikt. Een watermerk is een zichtbare of onzichtbare afbeelding of tekst die bovenop de presentatie wordt geplaatst. Het kan worden gebruikt om de eigenaar van de presentatie te identificeren en ongeoorloofd gebruik te voorkomen. Watermerken kunnen ook worden gebruikt om een ​​professionele toets aan de presentatie te geven en deze er verzorgder uit te laten zien. 
{{% blocks/products/pf/agp/code-block title="Voeg tekstwatermerk toe aan ODP met Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IMasterSlide master = pres.getMasters().get_Item(0);
    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");

    pres.save("watermark.odp", SaveFormat.Odp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Afbeeldingswatermerk toevoegen aan presentatie ODP met behulp van Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("watermark.png")));

    IMasterSlide master = pres.getMasters().get_Item(0);

    IAutoShape watermarkShape = master.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 100, 100);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(image);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    pres.save("watermark2.odp", SaveFormat.Odp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Watermerk toevoegen aan ODP via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om een ​​tekstwatermerk toe te voegen aan ODP-bestanden." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad ODP met een instantie van Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Selecteer de masterpresentatie
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vormtype toevoegen met de methode AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Voeg watermerktekst toe met de methode AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in ODP formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde formaten" subTitle="Met Java kunt u ook een watermerk toevoegen aan de volgende indelingen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}