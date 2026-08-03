---
title: Convert PDF to XML in Java
url: /java/conversion/pdf-to-xml/
keywords: PDF to XML, Convert PDF to XML, PowerPoint XML Presentation, Java API, Java Library, PDF, XML
description: Import PDF pages and save the result in PowerPoint XML Presentation format in Java with Aspose.Slides for Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PDF to XML in Java" h2="Import PDF pages into presentation slides and save the result in PowerPoint XML Presentation format." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to XML in Java" %}}

[**Aspose.Slides for Java**](/slides/java/) lets you import PDF pages into presentation slides and save the resulting presentation in PowerPoint XML Presentation format without Adobe Acrobat.

The generated XML represents a presentation and preserves the imported pages as slide content; it does not extract the PDF's logical structure into a generic XML schema.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to XML using Java" %}}
To convert PDF content to PowerPoint XML, create a `Presentation`, remove its default slide, import the source file with `ISlideCollection.addFromPdf`, and call `save` with `SaveFormat.Xml`.

{{% blocks/products/pf/agp/code-block title="Java code for converting PDF into XML" offSpacer="true" %}}

```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);
    presentation.getSlides().addFromPdf("input.pdf");
    presentation.save("output.xml", SaveFormat.Xml);
} finally {
    presentation.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PDF to XML using Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PDF to XML in Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](/slides/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Open the source `PDF` file in Java.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with the output file path and `SaveFormat.Xml`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PDF To Other Supported Formats" subTitle="You can also convert PDF and save to other file formats. See all supported formats below:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
