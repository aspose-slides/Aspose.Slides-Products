---
lastmod: 2026-07-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert ODP to PDF in Node.js
url: /nodejs-java/conversion/odp-to-pdf/
keywords: ODP to PDF, Convert ODP to PDF, Node.js API, Node.js Library, ODP, PDF
description: Convert ODP to PDF in Node.js. Use the Node.js API to convert ODP files to PDF files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert ODP to PDF in Node.js" h2="Convert OpenDocument Presentation files to PDF with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert ODP to PDF using Node.js" variant="code" %}}

To convert `ODP` to `PDF`, create a `Presentation` from the source file and export it to a `PDF` file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert ODP to PDF" >}}
```javascript
const presentation = new aspose.slides.Presentation("sourceFile.odp");
try {
    presentation.save("output.pdf", aspose.slides.SaveFormat.Pdf);
}
finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert ODP to PDF in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load an `ODP` file with the `Presentation` class and export it to a `PDF` file by using the presentation API.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert ODP to PDF using Aspose.Slides for Node.js via Java API" intro="To convert ODP to PDF using Aspose.Slides for Node.js via Java, import the package, load the source file with the Presentation class, and export it in the required format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.java` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `ODP` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `save` method with the output file path and `SaveFormat.Pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert ODP to Other Supported Formats" subTitle="You can also convert ODP files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
