---
title: Verwijder PPT-annotatie met behulp van Java
weight: 3630
url: /nl/java/annotation/ppt/ 
description: Java-voorbeeldcode om annotaties in PPT-indeling te verwijderen in Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Opmerkingen en auteurs van opmerkingen verwijderen uit PPT in Java" h2="Bouw uw eigen Java-apps om opmerkingen en auteurs in documentbestanden te manipuleren met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="Verwijder opmerkingen van PPT via Java" %}}
Om annotaties uit het PPT-bestand te verwijderen, gebruiken we [Aspose.Slides for Java](https://products.aspose.com/slides/nl/java/) API, een functierijke, krachtige en gebruiksvriendelijke API voor documentmanipulatie voor het Java-platform.
{{% blocks/products/pf/agp/code-block title="Annotaties verwijderen uit PPT - Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.ppt");
try {
    // Deletes all comments from the presentation
    for (ICommentAuthor author : presentation.getCommentAuthors())
    {
        author.getComments().clear();
    }

    // Deletes all authors
    presentation.getCommentAuthors().clear();

    presentation.save("example_out.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Hoe opmerkingen van PPT via Java te verwijderen" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installeer **Aspose.Slides voor Java**. Zie [**Installatie**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad PPT met een exemplaar van de Presentation-klasse
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Herhaal alle auteurs van geladen PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Verwijder alle opmerkingen van een auteur
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Verwijder alle auteurs aan het einde
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde annotatieformaten" subTitle="Met behulp van Java kan men gemakkelijk andere formaten annoteren, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}