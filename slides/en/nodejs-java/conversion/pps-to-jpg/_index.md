---
title: Convert PPS to JPG in Node.js
url: /nodejs-java/conversion/pps-to-jpg/
keywords: PPS to JPG, Convert PPS to JPG, Node.js API, Node.js Library, PPS, JPG
description: Convert PPS to JPG in Node.js. Use the Node.js API to convert PPS files to JPG images.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPS to JPG in Node.js" h2="Convert PowerPoint Slide Show files to JPG with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPS to JPG in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `PPS` file with the `Presentation` class and export its slides to `JPG` images by using the presentation API.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPS to JPG using Node.js" %}}
To convert `PPS` to `JPG`, create a `Presentation` from the source file and export each slide to a `JPG` image.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert PPS to JPG" offSpacer="true" %}}

```javascript
const presentation = new aspose.slides.Presentation("sourceFile.pps");
try {
    const slideCount = presentation.getSlides().size();
    for (let slideIndex = 0; slideIndex < slideCount; slideIndex++) {
        const slide = presentation.getSlides().get_Item(slideIndex);
        const slideImage = slide.getImage(2, 2);
        try {
            const filePath = "slide_" + slide.getSlideNumber() + ".jpg";
            slideImage.save(filePath, aspose.slides.ImageFormat.Jpeg);
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

{{< blocks/products/pf/feature-page-section  h2="How to convert PPS to JPG using Aspose.Slides for Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert PPS to JPG using Aspose.Slides for Node.js via Java, import the package, load the source file with the Presentation class, and export slides as images." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.java` package in your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `PPS` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each slide with `getImage` and save it with `ImageFormat.Jpeg`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPS to Other Supported Formats" subTitle="You can also convert PPS files to other supported presentation and export formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-pptx/" name="PPS TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-ppt/" name="PPS TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-pdf/" name="PPS TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-html/" name="PPS TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-png/" name="PPS TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-bmp/" name="PPS TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-fodp/" name="PPS TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-gif/" name="PPS TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-odp/" name="PPS TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-otp/" name="PPS TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-pot/" name="PPS TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-potm/" name="PPS TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-potx/" name="PPS TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-pptm/" name="PPS TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-svg/" name="PPS TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pps-to-tiff/" name="PPS TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
