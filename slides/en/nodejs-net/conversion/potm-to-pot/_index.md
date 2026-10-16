---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTM to POT in Node.js
url: /nodejs-net/conversion/potm-to-pot/
keywords: POTM to POT, Convert POTM to POT, Node.js API, JavaScript Library, POTM, POT
description: Convert POTM to POT in Node.js. Use a Node.js library API to convert POTM files to POT files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert POTM to POT in Node.js" h2="Convert macro-enabled PowerPoint template files to POT files with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTM to POT using Node.js" variant="code" %}}

To convert `POTM` to `POT`, create a `Presentation` from the source file and export it to a `POT` file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert POTM to POT" >}}
```javascript
const presentation = new asposeSlides.Presentation("sourceFile.potm");
try {
    presentation.save("output.pot", asposeSlides.SaveFormat.Pot);
}
finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTM to POT in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `POTM` file with the `Presentation` class and export it to a `POT` file by using the presentation API.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert POTM to POT using Aspose.Slides for Node.js via .NET API" intro="To convert POTM to POT using Aspose.Slides for Node.js via .NET, import the package, load the source file, and export it in the required format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.net` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `POTM` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `save` method with the output file path and `SaveFormat.Pot`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert POTM To Other Supported Formats" subTitle="You can also convert POTM and save to other file formats. See all supported formats below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
