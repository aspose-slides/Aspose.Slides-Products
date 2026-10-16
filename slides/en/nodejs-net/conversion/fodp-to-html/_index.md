---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert FODP to HTML in Node.js
url: /nodejs-net/conversion/fodp-to-html/
keywords: FODP to HTML, Convert FODP to HTML, Node.js API, JavaScript Library, FODP, HTML
description: Convert FODP to HTML in Node.js. Use a Node.js library API to convert FODP files to HTML files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert FODP to HTML in Node.js" h2="Convert flat OpenDocument presentation files to HTML files with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert FODP to HTML using Node.js" variant="code" %}}

To convert `FODP` to `HTML`, create a `Presentation` from the source file and export it to an `HTML` file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert FODP to HTML" >}}
```javascript
const presentation = new asposeSlides.Presentation("sourceFile.fodp");
try {
    presentation.save("output.html", asposeSlides.SaveFormat.Html);
}
finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert FODP to HTML in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load an `FODP` file with the `Presentation` class and export it to an `HTML` file by using the presentation API.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert FODP to HTML using Aspose.Slides for Node.js via .NET API" intro="To convert FODP to HTML using Aspose.Slides for Node.js via .NET, import the package, load the source file, and export it in the required format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.net` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source FODP file with the Presentation class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the save method with the output file path and SaveFormat.Html.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert FODP to Other Supported Formats" subTitle="You can also convert FODP files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
