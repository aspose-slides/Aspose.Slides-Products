---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTX to POTM in Node.js
url: /nodejs-net/conversion/potx-to-potm/
keywords: POTX to POTM, Convert POTX to POTM, Node.js API, JavaScript Library, POTX, POTM
description: Convert POTX to POTM in Node.js. Use a Node.js library API to convert POTX files to POTM files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert POTX to POTM in Node.js" h2="Convert PowerPoint template files to POTM files with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTX to POTM in Node.js" variant="code" %}}

To convert `POTX` to `POTM`, create a `Presentation` from the source file and export it to a `POTM` file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="JavaScript code to convert POTX into POTM" >}}
```javascript
const presentation = new asposeSlides.Presentation("sourceFile.potx");
try {
    presentation.save("output.potm", asposeSlides.SaveFormat.Potm);
}
finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTX to POTM in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `POTX` file with the `Presentation` class and export it to a `POTM` file by using the presentation API.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert POTX to POTM using Aspose.Slides for Node.js via .NET API" intro="To convert POTX to POTM using Aspose.Slides for Node.js via .NET, you need to import the package in your JavaScript file and create an instance of the Presentation class. The Presentation class represents a PowerPoint document and provides methods to access and manipulate its elements." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.net` package into your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `POTX` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` to export the presentation as a `POTM` file with `SaveFormat.Potm`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert POTX to Other Supported Formats" subTitle="You can also convert POTX files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
