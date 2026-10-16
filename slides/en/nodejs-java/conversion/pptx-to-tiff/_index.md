---
lastmod: 2026-07-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to TIFF in Node.js
url: /nodejs-java/conversion/pptx-to-tiff/
keywords: PPTX to TIFF, Convert PPTX to TIFF, Node.js API, Node.js Library, PPTX, TIFF
description: Convert PPTX to TIFF in Node.js. Use a Node.js library API to convert PPTX files to TIFF files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTX to TIFF in Node.js" h2="Convert PowerPoint Open XML presentation files to TIFF files with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTX to TIFF using Node.js" variant="code" %}}

To convert ``PPTX`` to ``TIFF``, create a ``Presentation`` from the source file and export it to a ``TIFF`` file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert PPTX to TIFF" >}}
```javascript
const presentation = new aspose.slides.Presentation("sourceFile.pptx");
try {
    presentation.save("output.tiff", aspose.slides.SaveFormat.Tiff);
}
finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTX to TIFF in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `PPTX` file with the `Presentation` class and export it to a `TIFF` file by using the presentation API.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PPTX to TIFF using Aspose.Slides for Node.js via Java API" intro="To convert PPTX to TIFF using Aspose.Slides for Node.js via Java, import the package, load the source file, and export it in the required format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.java` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `PPTX` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the ``save`` method with the output file path and ``SaveFormat.Tiff``.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PPTX to Other Supported Formats" subTitle="You can also convert PPTX files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
