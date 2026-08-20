---
lastmod: 2026-07-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTX to PPTM in Node.js
url: /nodejs-net/conversion/pptx-to-pptm/
keywords: PPTX to PPTM, Convert PPTX to PPTM, Node.js API, JavaScript Library, PPTX, PPTM
description: Convert PPTX to PPTM in Node.js. Use a Node.js library API to convert PPTX files to PPTM files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTX to PPTM in Node.js" h2="Convert PowerPoint presentation files to PPTM files with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPTX to PPTM in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `PPTX` file with the `Presentation` class and export it to a `PPTM` file by using the presentation API.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPTX to PPTM in Node.js" %}}
To convert `PPTX` to `PPTM`, create a `Presentation` from the source file and export it to a `PPTM` file.

{{% blocks/products/pf/agp/code-block title="JavaScript code to convert PPTX to PPTM" offSpacer="true" %}}

```javascript
const presentation = new asposeSlides.Presentation("sourceFile.pptx");
try {
    presentation.save("output.pptm", asposeSlides.SaveFormat.Pptm);
}
finally {
    presentation.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPTX to PPTM using Aspose.Slides for Node.js via .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert PPTX to PPTM using Aspose.Slides for Node.js via .NET, you need to import the package in your JavaScript file and create an instance of the Presentation class. The Presentation class represents a PowerPoint document and provides methods to access and manipulate its elements." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.net` package into your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `PPTX` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` to export the presentation as a `PPTM` file with `SaveFormat.Pptm`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPTX to Other Supported Formats" subTitle="You can also convert PPTX files to other supported presentation and export formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
