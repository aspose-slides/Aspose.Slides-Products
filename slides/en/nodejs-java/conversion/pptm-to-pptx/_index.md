---
lastmod: 2026-07-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTM to PPTX in Node.js
url: /nodejs-java/conversion/pptm-to-pptx/
keywords: PPTM to PPTX, Convert PPTM to PPTX, Node.js API, Node.js Library, PPTM, PPTX
description: Convert PPTM to PPTX in Node.js. Use a Node.js library API to convert PPTM files to PPTX files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTM to PPTX in Node.js" h2="Convert PowerPoint macro-enabled presentation files to PPTX files with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to PPTX using Node.js" variant="code" %}}

To convert `PPTM` to `PPTX`, create a `Presentation` from the source file and export it to a `PPTX` file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert PPTM to PPTX" >}}
```javascript
const presentation = new aspose.slides.Presentation("sourceFile.pptm");
try {
    presentation.save("output.pptx", aspose.slides.SaveFormat.Pptx);
}
finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to PPTX in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `PPTM` file with the `Presentation` class and export it to a `PPTX` file by using the presentation API.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPTM to PPTX using Aspose.Slides for Node.js via Java API" intro="To convert PPTM to PPTX using Aspose.Slides for Node.js via Java, import the package, load the source file, and export it in the required format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.java` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `PPTM` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `save` method with the output file path and `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPTM to Other Supported Formats" subTitle="You can also convert PPTM files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
