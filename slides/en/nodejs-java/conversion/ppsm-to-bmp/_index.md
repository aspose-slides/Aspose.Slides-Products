---
title: Convert PPSM to BMP in Node.js
url: /nodejs-java/conversion/ppsm-to-bmp/
keywords: PPSM to BMP, Convert PPSM to BMP, Node.js API, Node.js Library, PPSM, BMP
description: Convert PPSM to BMP in Node.js. Use the Node.js API to convert PPSM files to BMP images.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSM to BMP in Node.js" h2="Convert PowerPoint Macro-Enabled Slide Show files to BMP with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSM to BMP in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `PPSM` file with the `Presentation` class and export its slides to `BMP` images by using the presentation API.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPSM to BMP using Node.js" %}}
To convert `PPSM` to `BMP`, create a `Presentation` from the source file and export each slide to a `BMP` image.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert PPSM to BMP" offSpacer="true" %}}

```javascript
const presentation = new aspose.slides.Presentation("sourceFile.ppsm");
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

{{< blocks/products/pf/feature-page-section  h2="How to convert PPSM to BMP using Aspose.Slides for Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert PPSM to BMP using Aspose.Slides for Node.js via Java, import the package, load the source file with the Presentation class, and export slides as images." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.java` package in your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `PPSM` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each slide with `getImage` and save it with `ImageFormat.Bmp`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSM to Other Supported Formats" subTitle="You can also convert PPSM files to other supported presentation and export formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-png/" name="PPSM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-jpg/" name="PPSM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-potm/" name="PPSM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-svg/" name="PPSM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
