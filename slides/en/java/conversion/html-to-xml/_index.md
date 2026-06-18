---
title: Convert HTML to XML in Java
url: /java/conversion/html-to-xml/
keywords: HTML to XML, Convert HTML to XML, Java API, Java Library, HTML, XML
description: Convert HTML to XML in Java. Use Java library API to convert HTML files to XML-based output.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert HTML to XML in Java" h2="Convert HTML files to XML-based output using Aspose.Slides for Java without Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Convert HTML to XML in Java" %}}

[**Aspose.Slides for Java**](/slides/java/) is a presentation processing API that can import `HTML` content and save slide output as XML-based files.

Aspose.Slides for Java can convert `HTML` content to XML-based output and other presentation-related formats.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert HTML to XML using Java" %}}
To convert `HTML` to XML-based output, create a `Presentation` from the source file and write each slide as an XML-based file.

{{% blocks/products/pf/agp/code-block title="Java code for converting HTML into XML" offSpacer="true" %}}

```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);
    try (FileInputStream htmlStream = new FileInputStream("page.html")) {
        presentation.getSlides().addFromHtml(htmlStream);
    }

    for (int slideIndex = 0; slideIndex < presentation.getSlides().size(); slideIndex++) {
        ISlide slide = presentation.getSlides().get_Item(slideIndex);
        try (FileOutputStream fileStream = new FileOutputStream("slide_" + (slideIndex + 1) + ".xml")) {
            slide.writeAsSvg(fileStream);
        }
    }
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

{{< blocks/products/pf/agp/step-autogen >}}
Load the source `HTML` file into a `Presentation`.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Write each `ISlide` as an XML-based file.
{{< /blocks/products/pf/agp/step-autogen >}}

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
