---
title: Convert PPSM to JPG in Node.js
url: /nodejs-net/conversion/ppsm-to-jpg/
keywords: PPSM to JPG, Convert PPSM to JPG, Node.js API, JavaScript Library, PPSM, JPG
description: Convert PPSM to JPG in Node.js. Use a Node.js library API to convert PPSM files to JPG images.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSM to JPG in Node.js" h2="Convert PowerPoint slideshow slides to JPG images with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSM to JPG in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `PPSM` file with the `Presentation` class and export each slide to a `JPG` image by using the presentation API.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPSM to JPG in Node.js" %}}
To convert `PPSM` to `JPG`, create a `Presentation` from the source file and export each slide to a `JPG` image.

{{% blocks/products/pf/agp/code-block title="JavaScript code to convert PPSM into JPG" offSpacer="true" %}}

```javascript
const presentation = new asposeSlides.Presentation("sourceFile.ppsm");
try {
    const slideCount = presentation.slides.length;
    for (let slideIndex = 0; slideIndex < slideCount; slideIndex++) {
        const slide = presentation.slides.get(slideIndex);
        const slideImage = slide.getImageWithScale(2, 2);
        try {
            const filePath = "slide_" + slideIndex + ".jpg";
            slideImage.save(filePath, asposeSlides.ImageFormat.Jpeg);
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

{{< blocks/products/pf/feature-page-section  h2="How to convert PPSM to JPG using Aspose.Slides for Node.js via .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert PPSM to JPG using Aspose.Slides for Node.js via .NET, you need to import the package in your JavaScript file and create an instance of the Presentation class. The Presentation class represents a PowerPoint document and provides methods to access and manipulate its elements." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.net` package into your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `PPSM` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `getImageWithScale` for each slide and save the result as a `JPG` image.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSM to Other Supported Formats" subTitle="You can also convert PPSM files to other supported presentation and export formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-png/" name="PPSM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-potm/" name="PPSM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-svg/" name="PPSM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
