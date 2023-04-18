---
title: Ta bort ODP Annotation med Java
weight: 1790
url: /sv/java/annotation/odp/ 
description: Java-exempelkod för att ta bort ODP-formatkommentarer i Java Runtime Environment för JSP/JSF Application och Desktop Applications.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Ta bort kommentarer och kommentarsförfattare från ODP i Java" h2="Bygg dina egna Java-appar för att manipulera kommentarer och författare i dokumentfiler med hjälp av API:er på serversidan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="Ta bort kommentarer från ODP via Java" %}}
För att ta bort anteckningar från ODP-filen använder vi [Aspose.Slides for Java](https://products.aspose.com/slides/sv/java/) API som är en funktionsrik, kraftfull och lättanvänd API för dokumentmanipulation för Java-plattformen.
{{% blocks/products/pf/agp/code-block title="Ta bort anteckningar från ODP - Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.odp");
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

{{< blocks/products/pf/feature-page-section  h2="Hur man tar bort kommentarer från ODP via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera **Aspose.Slides för Java**. Se [**Installation**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda ODP med en instans av presentationsklassen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterera över alla författare av laddad ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ta bort alla kommentarer från en författare
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ta bort alla författare i slutet
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra anteckningsformat som stöds" subTitle="Med Java kan man enkelt kommentera andra format inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}