---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert FODP to POTX in Node.js
url: /nodejs-java/conversion/fodp-to-potx/
keywords: FODP to POTX, Convert FODP to POTX, Node.js API, Node.js Library, FODP, POTX
description: Convert FODP to POTX in Node.js. Use the Node.js API to convert FODP files to POTX files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert FODP to POTX in Node.js" h2="Convert Flat OpenDocument Presentation files to POTX with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert FODP to POTX using Node.js" variant="code" %}}

To convert `FODP` to `POTX`, create a `Presentation` from the source file and export it to a `POTX` file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert FODP to POTX" >}}
```javascript
const presentation = new aspose.slides.Presentation("sourceFile.fodp");
try {
    presentation.save("output.potx", aspose.slides.SaveFormat.Potx);
}
finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert FODP to POTX in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load an `FODP` file with the `Presentation` class and export it to a `POTX` file by using the presentation API.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert FODP to POTX using Aspose.Slides for Node.js via Java API" intro="To convert FODP to POTX using Aspose.Slides for Node.js via Java, import the package, load the source file with the Presentation class, and export it in the required format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.java` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `FODP` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `save` method with the output file path and `SaveFormat.Potx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert FODP to Other Supported Formats" subTitle="You can also convert FODP files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
