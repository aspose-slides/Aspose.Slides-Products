---
lastmod: 2026-07-13
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSX to GIF in Node.js
url: /nodejs-java/conversion/ppsx-to-gif/
keywords: PPSX to GIF, Convert PPSX to GIF, Node.js API, Node.js Library, PPSX, GIF
description: Convert PPSX to GIF in Node.js. Use the Node.js API to convert PPSX files to GIF files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPSX to GIF in Node.js" h2="Convert PowerPoint Open XML Slide Show files to GIF with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSX to GIF using Node.js" variant="code" %}}

To convert `PPSX` to `GIF`, create a `Presentation` from the source file and export it to a `GIF` file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert PPSX to GIF" >}}
```javascript
const presentation = new aspose.slides.Presentation("sourceFile.ppsx");
try {
    presentation.save("output.gif", aspose.slides.SaveFormat.Gif);
}
finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSX to GIF in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `PPSX` file with the `Presentation` class and export it to a `GIF` file by using the presentation API.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPSX to GIF using Aspose.Slides for Node.js via Java API" intro="To convert PPSX to GIF using Aspose.Slides for Node.js via Java, import the package, load the source file, and export it in the required format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.java` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `PPSX` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `save` method with the output file path and `SaveFormat.Gif`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
