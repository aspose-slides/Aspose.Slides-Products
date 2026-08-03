---
title: Convert HTML to XML in Java
url: /java/conversion/html-to-xml/
keywords: HTML to XML, Convert HTML to XML, PowerPoint XML Presentation, Java API, Java Library, HTML, XML
description: Convert HTML content to PowerPoint XML Presentation format in Java with Aspose.Slides for Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert HTML to XML in Java" h2="Import HTML content into presentation slides and save the result in PowerPoint XML Presentation format." >}}

{{% blocks/products/pf/feature-page-section h2="Convert HTML to XML in Java" %}}

[**Aspose.Slides for Java**](/slides/java/) can import HTML content into presentation slides and save the resulting presentation in PowerPoint XML Presentation format.

The generated XML represents a presentation rather than a generic transformation of the source HTML markup. Aspose.Slides can also export the imported content to PowerPoint, PDF, images, and other supported formats.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert HTML to XML using Java" %}}
To convert HTML content to PowerPoint XML, create a `Presentation`, remove its default slide, import the HTML with `addFromHtml`, and call `save` with `SaveFormat.Xml`.

{{% blocks/products/pf/agp/code-block title="Java code for converting HTML into XML" offSpacer="true" %}}

```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);
    try (FileInputStream htmlStream = new FileInputStream("page.html")) {
        presentation.getSlides().addFromHtml(htmlStream);
    }

    presentation.save("output.xml", SaveFormat.Xml);
} finally {
    presentation.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert HTML to XML using Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert HTML to XML in Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](/slides/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `HTML` file into a `Presentation`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with the output file path and `SaveFormat.Xml`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert HTML To Other Supported Formats" subTitle="You can also convert HTML and save it to other file formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
