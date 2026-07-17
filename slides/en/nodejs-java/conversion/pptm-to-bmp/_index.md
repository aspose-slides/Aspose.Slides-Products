---
title: Convert PPTM to BMP in Node.js
url: /nodejs-java/conversion/pptm-to-bmp/
keywords: PPTM to BMP, Convert PPTM to BMP, Node.js API, Node.js Library, PPTM, BMP
description: Convert PPTM to BMP in Node.js. Use a Node.js library API to convert PPTM files to BMP images.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPTM to BMP in Node.js" h2="Convert PowerPoint macro-enabled presentation files to BMP images with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPTM to BMP in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `PPTM` file with the `Presentation` class and export its slides to `BMP` images.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convert PPTM to BMP using Node.js" %}}
To convert `PPTM` to `BMP`, create a `Presentation` from the source file and export each slide to a `BMP` image.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert PPTM to BMP" offSpacer="true" %}}

```javascript
const presentation = new aspose.slides.Presentation("sourceFile.pptm");
try {
    const slideCount = presentation.getSlides().size();
    for (let slideIndex = 0; slideIndex < slideCount; slideIndex++) {
        const slide = presentation.getSlides().get_Item(slideIndex);
        const slideImage = slide.getImage(2, 2);
        try {
            const filePath = "slide_" + slide.getSlideNumber() + ".bmp";
            slideImage.save(filePath, aspose.slides.ImageFormat.Bmp);
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

{{< blocks/products/pf/feature-page-section h2="How to convert PPTM to BMP using Aspose.Slides for Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert PPTM to BMP using Aspose.Slides for Node.js via Java, import the package, load the source file with the Presentation class, and export slides as images." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.java` package in your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `PPTM` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each slide with `getImage` and save it with `ImageFormat.Bmp`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPTM to Other Supported Formats" subTitle="You can also convert PPTM files to other supported presentation and export formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-html/" name="PPTM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-png/" name="PPTM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-jpg/" name="PPTM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-gif/" name="PPTM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-odp/" name="PPTM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-otp/" name="PPTM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-pot/" name="PPTM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-potm/" name="PPTM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-potx/" name="PPTM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-pps/" name="PPTM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-svg/" name="PPTM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}