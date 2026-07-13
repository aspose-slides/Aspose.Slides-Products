---
title: Convert PPSX to PNG in Node.js
url: /nodejs-java/conversion/ppsx-to-png/
keywords: PPSX to PNG, Convert PPSX to PNG, Node.js API, Node.js Library, PPSX, PNG
description: Convert PPSX to PNG in Node.js. Use the Node.js API to convert PPSX files to PNG images.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSX to PNG in Node.js" h2="Convert PowerPoint Open XML Slide Show files to PNG with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSX to PNG in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `PPSX` file with the `Presentation` class and export its slides to `PNG` images by using the presentation API.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPSX to PNG using Node.js" %}}
To convert `PPSX` to `PNG`, create a `Presentation` from the source file and export each slide to a `PNG` image.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert PPSX to PNG" offSpacer="true" %}}

```javascript
const presentation = new aspose.slides.Presentation("sourceFile.ppsx");
try {
    const slideCount = presentation.getSlides().size();
    for (let slideIndex = 0; slideIndex < slideCount; slideIndex++) {
        const slide = presentation.getSlides().get_Item(slideIndex);
        const slideImage = slide.getImage(2, 2);
        try {
            const filePath = "slide_" + slide.getSlideNumber() + ".png";
            slideImage.save(filePath, aspose.slides.ImageFormat.Png);
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

{{< blocks/products/pf/feature-page-section  h2="How to convert PPSX to PNG using Aspose.Slides for Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert PPSX to PNG using Aspose.Slides for Node.js via Java, import the package, load the source file with the Presentation class, and export slides as images." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.java` package in your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `PPSX` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each slide with `getImage` and save it with `ImageFormat.Png`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSX to Other Supported Formats" subTitle="You can also convert PPSX files to other supported presentation and export formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
