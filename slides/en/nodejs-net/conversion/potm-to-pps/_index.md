---
lastmod: 2026-07-15
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTM to PPS in Node.js
url: /nodejs-net/conversion/potm-to-pps/
keywords: POTM to PPS, Convert POTM to PPS, Node.js API, JavaScript Library, POTM, PPS
description: Convert POTM to PPS in Node.js. Use a Node.js library API to convert POTM files to PPS files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert POTM to PPS in Node.js" h2="Convert macro-enabled PowerPoint template files to PPS files with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTM to PPS using Node.js" variant="code" %}}

To convert `POTM` to `PPS`, create a `Presentation` from the source file and export it to a `PPS` file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert POTM to PPS" >}}
```javascript
const presentation = new asposeSlides.Presentation("sourceFile.potm");
try {
    presentation.save("output.pps", asposeSlides.SaveFormat.Pps);
}
finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTM to PPS in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `POTM` file with the `Presentation` class and export it to a `PPS` file by using the presentation API.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert POTM to PPS using Aspose.Slides for Node.js via .NET API" intro="To convert POTM to PPS using Aspose.Slides for Node.js via .NET, import the package, load the source file, and export it in the required format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.net` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `POTM` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `save` method with the output file path and `SaveFormat.Pps`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert POTM to Other Supported Formats" subTitle="You can also convert POTM files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
