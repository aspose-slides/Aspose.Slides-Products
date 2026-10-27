---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to XML in Java
url: /java/conversion/pdf-to-xml/
keywords: PDF to XML, Convert PDF to XML, PowerPoint XML Presentation, Java API, Java Library, PDF, XML
description: Import PDF pages and save the result in PowerPoint XML Presentation format in Java with Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to XML in Java" h2="Import PDF pages into presentation slides and save the result in PowerPoint XML Presentation format." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to XML using Java" variant="code" %}}

To convert PDF content to PowerPoint XML, create a `Presentation`, remove its default slide, import the source file with `ISlideCollection.addFromPdf`, and call `save` with `SaveFormat.Xml`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java code for converting PDF into XML" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to XML in Java" %}}

[**Aspose.Slides for Java**](/slides/java/) lets you import PDF pages into presentation slides and save the resulting presentation in PowerPoint XML Presentation format without Adobe Acrobat.

The generated XML represents a presentation and preserves the imported pages as slide content; it does not extract the PDF's logical structure into a generic XML schema.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PDF to XML using Aspose.Slides for Java API" intro="These are the steps to convert PDF to XML in Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Java**](/slides/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a library reference (import the library) to your Java project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Open the source `PDF` file in Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with the output file path and `SaveFormat.Xml`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF To Other Supported Formats" subTitle="You can also convert PDF and save to other file formats. See all supported formats below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
