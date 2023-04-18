---
title: Remove PPT Annotation using Java 
weight: 3630
url: /java/annotation/ppt/ 
description: Java sample code to delete PPT format annotations on Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Remove Comments & Comment Authors from PPT in Java" h2="Build your own Java apps to manipulate comments & authors in document files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="Remove Comments from PPT via Java" %}}
In order to remove annotations from the PPT file, we’ll use  [Aspose.Slides for Java](https://products.aspose.com/slides/java/) API which is a feature-rich, powerful and easy to use document manipulation API for Java platform.
{{% blocks/products/pf/agp/code-block title="Delete Annotations from PPT - Java" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="How to Remove Comments from PPT via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Java**. See [**Installation**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load PPT with an instance of Presentation class
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterate over all Authors of loaded PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Remove all Comments of an author
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Remove all Authors at the end
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Annotation Formats" subTitle="Using Java, one can easily annotate other formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}