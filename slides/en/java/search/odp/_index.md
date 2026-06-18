---
title: Search Text in ODP Presentation Files using Java
url: /java/search/odp/
keywords: search words in ODP, search text in ODP, search text ODP Presentation
description: Search text in ODP presentations in Java using Aspose.Slides for Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Search Text in ODP using Java" h2="Build Java applications that search text in presentation files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Search Text in ODP Presentation via Java" %}}
Using [Aspose.Slides for Java](/slides/java/), you can search text in ODP presentations. Use the `SlideUtil.getAllTextBoxes` method to collect text frames and then inspect `ITextFrame`, `IParagraph`, and `IPortion` objects.
{{% blocks/products/pf/agp/code-block title="Search Text in ODP Presentation using Java" offSpacer="true" %}}

```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to Search Text in ODP via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to search text in ODP files." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the `ODP` file with the `Presentation` class.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Call the `SlideUtil.getAllTextBoxes` method to collect text frames from each slide.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Inspect `ITextFrame`, `IParagraph`, and `IPortion` objects to find matching text.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Search Live Demos" sectionDescription="Search text in ODP documents online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Search Formats" subTitle="Using Java, you can also search text in the following formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
