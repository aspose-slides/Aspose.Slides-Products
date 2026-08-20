---
lastmod: 2026-07-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert ODP to PPS in Node.js
url: /nodejs-net/conversion/odp-to-pps/
keywords: ODP to PPS, Convert ODP to PPS, Node.js API, JavaScript Library, ODP, PPS
description: Convert ODP to PPS in Node.js. Use a Node.js library API to convert ODP files to PPS files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert ODP to PPS in Node.js" h2="Convert OpenDocument presentation files to PPS files with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/feature-page-section h2="Convert ODP to PPS in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load an `ODP` file with the `Presentation` class and export it to a `PPS` file by using the presentation API.

Aspose.Slides supports high-quality presentation conversion and lets you save `ODP` files as `PPS` slide shows for PowerPoint-compatible playback workflows.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert ODP to PPS using Node.js" %}}
To convert `ODP` to `PPS`, create a `Presentation` from the source file and export it to a `PPS` file.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert ODP to PPS" offSpacer="true" %}}

```javascript
const presentation = new asposeSlides.Presentation("sourceFile.odp");
try {
    presentation.save("output.pps", asposeSlides.SaveFormat.Pps);
}
finally {
    presentation.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert ODP to PPS using Aspose.Slides for Node.js via .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert ODP to PPS using Aspose.Slides for Node.js via .NET, import the package, load the source file, and export it in the required format." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.net` package in your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `ODP` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call the `save` method with the output file path and `SaveFormat.Pps`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert ODP to Other Supported Formats" subTitle="You can also convert ODP files to other supported presentation and export formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
