---
title: Convert PDF to HTML in Java
url: /java/conversion/pdf-to-html/
keywords: PDF to HTML, Convert PDF to HTML, Java API, Java Library, PDF, HTML
description: Convert PDF to HTML in Java. Use Aspose.Slides for Java to save PDF files as HTML files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PDF to HTML in Java" h2="Convert PDF files to HTML with Aspose.Slides for Java without Adobe Acrobat." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to HTML in Java" %}}

[**Aspose.Slides for Java**](/slides/java/) lets you import `PDF` files into a presentation and save the result as `HTML`. With this Java API, you can convert `PDF` content without Adobe Acrobat.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to HTML using Java" %}}
To convert `PDF` to `HTML`, create a `Presentation`, import the source file with `ISlideCollection.addFromPdf`, and save the presentation with `SaveFormat.Html`.

{{% blocks/products/pf/agp/code-block title="Java code for converting PDF into HTML" offSpacer="true" %}}

```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().addFromPdf("input.pdf");
    presentation.save("output.html", SaveFormat.Html);
} finally {
    presentation.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PDF to HTML using Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PDF to HTML in Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](/slides/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source `PDF` file in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the result as an `HTML` file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="Convert presentations and slides online." >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PDF To Other Supported Formats" subTitle="You can also convert PDF and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}