---
lastmod: 2026-07-09
title: View PPSM in Java
url: /java/viewer/ppsm/
keywords: View PPSM, Open PPSM, PPSM Viewer, PPSM, Java API, Java Library
description: View PPSM files in Java. Use Aspose.Slides for Java to open macro-enabled PowerPoint slide show files and save them as HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="View PPSM in Java" h2="Java API for opening PPSM files and saving them as HTML." related="ODP,OTP,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="View PPSM in Java" variant="code" %}}

Using [**Aspose.Slides for Java**](/slides/java/), you can load a PPSM presentation and save it as responsive HTML with a few lines of code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java code for viewing PPSM" >}}
```java
Presentation presentation = new Presentation("presentation.ppsm");
try {
    ResponsiveHtmlController controller = new ResponsiveHtmlController();
    HtmlOptions htmlOptions = new HtmlOptions();
    htmlOptions.setHtmlFormatter(HtmlFormatter.createCustomFormatter(controller));

    presentation.save("index.html", SaveFormat.Html, htmlOptions);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="View PPSM using Aspose.Slides" %}}

[**Aspose.Slides for Java**](/slides/java/) is a Java library for opening, viewing, editing, and converting presentation files. You can load PPSM files and save them as HTML for viewing in a browser.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to view PPSM in Java" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for Java**. See [**Installation**](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the library as a reference in your project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the `PPSM` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `ResponsiveHtmlController` object for responsive HTML output.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create an `HtmlOptions` object and set the `HtmlFormatter` property.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the PPSM presentation as HTML with `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="View other files" subTitle="You can also open and view presentations in other formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/viewer/odp/" name="View ODP Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/viewer/otp/" name="View OTP Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/viewer/pot/" name="View POT Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/viewer/potm/" name="View POTM Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/viewer/potx/" name="View POTX Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/viewer/pps/" name="View PPS Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/viewer/ppsx/" name="View PPSX Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/viewer/ppt/" name="View PPT Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/viewer/pptm/" name="View PPTM Presentation" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/viewer/pptx/" name="View PPTX Presentation" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
