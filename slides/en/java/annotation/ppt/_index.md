---
title: Remove PPT Annotations using Java
weight: 3630
url: /java/annotation/ppt/
description: Remove comments and comment authors from PPT presentations in Java with Aspose.Slides for Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Remove Comments and Comment Authors from PPT in Java" h2="Use Aspose.Slides for Java to remove comments and comment authors from presentation files." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="PPT" fileiconsmall3="ODP" fileiconsmall4="PDF" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="Remove Comments from PPT via Java" %}}
Aspose.Slides for Java lets you remove comments and comment authors from PPT presentations. Load a file with the `Presentation` class, iterate through `ICommentAuthor` objects from `getCommentAuthors`, clear their comments, and save the updated presentation.
{{% blocks/products/pf/agp/code-block title="Delete Annotations from PPT - Java" offSpacer="true" %}}

```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="How to Remove Comments from PPT via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install Aspose.Slides for Java. See [Installation](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the PPT file with the `Presentation` class.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterate through the `ICommentAuthor` objects from `getCommentAuthors`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Clear each author's comments with `getComments().clear()`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Clear the comment author collection and save the updated PPT file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Annotation Formats" subTitle="You can also remove comments from other presentation formats with Java." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
