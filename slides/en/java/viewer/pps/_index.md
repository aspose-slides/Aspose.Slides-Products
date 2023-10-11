---
title:  View PPS in Java
url: /java/viewer/pps/
keywords: View PPS, View PowerPoint Slideshow, Play Slideshow, Open PPS, PPS Viewer, PPS, PowerPoint, Java API, Java Library
description: View PPS in Java. Use Java library API to open and view PowerPoint Slideshow
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="View PPS in Java" h2="Powerful cross-platform Java API for opening and viewing PPS using Java code" >}}

{{% blocks/products/pf/feature-page-section h2="View PPS using Aspose.Slides" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/java/) is a powerful Java library used to open and view, manipulate or edit presentations, import presentations from images or documents, and convert presentations to files in other formats.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="View PPS in Java" %}}
Using [**Aspose.Slides for Java**](https://products.aspose.com/slides/java/), you can load and view a presentation with a few lines of code.

{{% blocks/products/pf/agp/code-block title="Java code for viewing PPS" offSpacer="true" %}}
```java
// Instantiate a Presentation object that represents a presentation file
Presentation pres = new Presentation("presentation.pps");
try {
    ResponsiveHtmlController controller = new ResponsiveHtmlController();
    HtmlOptions htmlOptions = new HtmlOptions();
    htmlOptions.setHtmlFormatter(HtmlFormatter.createCustomFormatter(controller));

    // Saving the presentation to HTML
    pres.save("index.html", SaveFormat.Html, htmlOptions);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to view PPS in Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Java**. See [**Installation**](https://docs.aspose.com/slides/java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add the library as a reference in your project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instantiate a Presentation object and load the PPS file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create an instance of the ResponsiveHtmlController for formatting.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create an instance of HtmlOptions and set the HtmlFormatter property.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the PPS presentation as HTML.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Call Process.Start with path to resulting HTML to load PPS content.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}





{{< blocks/products/pf/agp/other-supported-section title="View other files" subTitle="You can also open and view presentations in other formats" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/viewer/ppt/" name="View PPT Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/viewer/pptx/" name="View PPTX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/viewer/odp/" name="View ODP Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/viewer/otp/" name="View OTP Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/viewer/pot/" name="View POT Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/viewer/potm/" name="View POTM Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/viewer/potx/" name="View POTX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/viewer/ppsm/" name="View PPSM Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/viewer/ppsx/" name="View PPSX Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/viewer/pptm/" name="View PPTM Presentation" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}