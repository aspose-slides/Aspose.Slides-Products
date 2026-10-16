---
lastmod: 2026-07-13
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to PPS in Node.js
url: /nodejs-java/conversion/pdf-to-pps/
keywords: PDF to PPS, Convert PDF to PPS, Node.js API, Node.js Library, PDF, PPS
description: Convert PDF to PPS in Node.js. Use the Node.js API to convert PDF files to PPS files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to PPS in Node.js" h2="Convert PDF files to PPS with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to PPS using Node.js" variant="code" %}}

To convert `PDF` to `PPS`, create a `Presentation`, import the source file with `addFromPdf`, and save the presentation with `SaveFormat.Pps`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert PDF to PPS" >}}
```javascript
const presentation = new aspose.slides.Presentation();
try {
    presentation.getSlides().removeAt(0);
    presentation.getSlides().addFromPdf("sourceFile.pdf");
    presentation.save("output.pps", aspose.slides.SaveFormat.Pps);
}
finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to PPS in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets you import `PDF` files into a presentation and save the result as `PPS`. With this Node.js API, you can convert `PDF` content without Adobe Acrobat.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PDF to PPS using Aspose.Slides for Node.js via Java API" intro="To convert PDF to PPS using Aspose.Slides for Node.js via Java, import the package, import the source file into a presentation, and export it in the required format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.java` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the source `PDF` file with `addFromPdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `save` method with the output file path and `SaveFormat.Pps`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
