---
title: Convert ODP to PNG in Node.js
url: /nodejs-net/conversion/odp-to-png/
keywords: ODP to PNG, Convert ODP to PNG, Node.js API, JavaScript Library, ODP, PNG
description: Convert ODP to PNG in Node.js. Use a Node.js library API to convert ODP files to PNG images.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert ODP to PNG in Node.js" h2="Convert OpenDocument presentation files to PNG images with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/feature-page-section h2="Convert ODP to PNG in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load an `ODP` file with the `Presentation` class and render each slide as a `PNG` image.

Aspose.Slides supports high-quality presentation conversion and lets you export `ODP` slides to `PNG` images for previews, thumbnails, reports, or other processing workflows.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert ODP to PNG using Node.js" %}}
To convert `ODP` to `PNG`, create a `Presentation` from the source file and render each slide as a `PNG` image.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert ODP to PNG" offSpacer="true" %}}

```javascript
const presentation = new asposeSlides.Presentation("sourceFile.odp");
try {
    const slideCount = presentation.slides.length;
    for (let slideIndex = 0; slideIndex < slideCount; slideIndex++) {
        const slide = presentation.slides.get(slideIndex);
        const slideImage = slide.getImageWithScale(2, 2);
        try {
            const filePath = "slide_" + slideIndex + ".png";
            slideImage.save(filePath, asposeSlides.ImageFormat.Png);
        }
        finally {
            slideImage.dispose();
        }
    }
}
finally {
    presentation.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert ODP to PNG using Aspose.Slides for Node.js via .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert ODP to PNG using Aspose.Slides for Node.js via .NET, import the package, load the source file, and export slides as images." >}}

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
Render each slide with `getImageWithScale` and save it with `ImageFormat.Png`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert ODP to Other Supported Formats" subTitle="You can also convert ODP files to other supported presentation and export formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-pptx/" name="ODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-ppt/" name="ODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-pdf/" name="ODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-html/" name="ODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-bmp/" name="ODP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-jpg/" name="ODP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-fodp/" name="ODP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-gif/" name="ODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-otp/" name="ODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-pot/" name="ODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-potm/" name="ODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-potx/" name="ODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-pps/" name="ODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-ppsm/" name="ODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-ppsx/" name="ODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-pptm/" name="ODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-svg/" name="ODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/odp-to-tiff/" name="ODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
