---
title: Convert POT to SVG in Node.js
url: /nodejs-net/conversion/pot-to-svg/
keywords: POT to SVG, Convert POT to SVG, Node.js API, JavaScript Library, POT, SVG
description: Convert POT to SVG in Node.js. Use a Node.js library API to convert POT files to SVG files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert POT to SVG in Node.js" h2="Convert OpenDocument presentation template files to SVG files with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/feature-page-section h2="Convert POT to SVG in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load an `POT` file with the `Presentation` class and export each slide to an `SVG` file.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convert POT to SVG using Node.js" %}}
To convert `POT` to `SVG`, create a `Presentation` from the source file and export each slide to an `SVG` file.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert POT to SVG" offSpacer="true" %}}

```javascript
const presentation = new asposeSlides.Presentation("sourceFile.pot");
try {
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

{{< blocks/products/pf/feature-page-section h2="How to convert POT to SVG using Aspose.Slides for Node.js via .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert POT to SVG using Aspose.Slides for Node.js via .NET, import the package, load the source file, and export it in the required format." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.net` package in your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `POT` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call the `getAsSvg` method for each `slide` and save the SVG data with `fs.writeFileSync`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert POT To Other Supported Formats" subTitle="You can also convert POT and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-pptx/" name="POT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-ppt/" name="POT TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-pdf/" name="POT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-html/" name="POT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-png/" name="POT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-bmp/" name="POT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-jpg/" name="POT TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-fodp/" name="POT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-gif/" name="POT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-odp/" name="POT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-otp/" name="POT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-potm/" name="POT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-potx/" name="POT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-pps/" name="POT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-ppsm/" name="POT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-ppsx/" name="POT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-pptm/" name="POT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/pot-to-tiff/" name="POT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}