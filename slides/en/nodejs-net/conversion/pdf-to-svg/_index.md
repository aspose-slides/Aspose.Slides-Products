---
lastmod: 2026-07-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to SVG in Node.js
url: /nodejs-net/conversion/pdf-to-svg/
keywords: PDF to SVG, Convert PDF to SVG, Node.js API, JavaScript Library, PDF, SVG
description: Convert PDF to SVG in Node.js. Use a Node.js library API to convert PDF files to SVG files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PDF to SVG in Node.js" h2="Convert PDF files to SVG files with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to SVG in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. Create a `Presentation`, import a `PDF` file with the `addFromPdf` method, and export each slide to an `SVG` file.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to SVG using Node.js" %}}
To convert `PDF` to `SVG`, create a `Presentation`, import the source file with `addFromPdf`, and export each slide to an `SVG` file.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert PDF to SVG" offSpacer="true" %}}

```javascript
const presentation = new asposeSlides.Presentation();
try {
    presentation.slides.removeAt(0);
    presentation.slides.addFromPdf("sourceFile.pdf");

    const slideCount = presentation.slides.length;
    for (let slideIndex = 0; slideIndex < slideCount; slideIndex++) {
        const slide = presentation.slides.get(slideIndex);
        const svgData = slide.getAsSvg();
        const filePath = "slide_" + slideIndex + ".svg";
        fs.writeFileSync(filePath, svgData);
    }
}
finally {
    presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section h2="How to convert PDF to SVG using Aspose.Slides for Node.js via .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert PDF to SVG using Aspose.Slides for Node.js via .NET, import the package, load the source file, and export it in the required format." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.net` package in your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and import the source `PDF` file with `addFromPdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the source `PDF` file with `addFromPdf`, then call `getAsSvg` for each `slide` and save the SVG data with `fs.writeFileSync`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF files to other supported presentation and export formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}