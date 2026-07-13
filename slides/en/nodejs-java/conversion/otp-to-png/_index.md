---
title: Convert OTP to PNG in Node.js
url: /nodejs-java/conversion/otp-to-png/
keywords: OTP to PNG, Convert OTP to PNG, Node.js API, Node.js Library, OTP, PNG
description: Convert OTP to PNG in Node.js. Use the Node.js API to convert OTP files to PNG images.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert OTP to PNG in Node.js" h2="Convert OpenDocument Presentation Template files to PNG with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert OTP to PNG in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load an `OTP` file with the `Presentation` class and export its slides to `PNG` images by using the presentation API.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert OTP to PNG using Node.js" %}}
To convert `OTP` to `PNG`, create a `Presentation` from the source file and export each slide to a `PNG` image.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert OTP to PNG" offSpacer="true" %}}

```javascript
const presentation = new aspose.slides.Presentation("sourceFile.otp");
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

{{< blocks/products/pf/feature-page-section  h2="How to convert OTP to PNG using Aspose.Slides for Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert OTP to PNG using Aspose.Slides for Node.js via Java, import the package, load the source file, and export slides as images." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.java` package in your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `OTP` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each slide with `getImage` and save it with `ImageFormat.Png`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert OTP to Other Supported Formats" subTitle="You can also convert OTP files to other supported presentation and export formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-pptx/" name="OTP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-ppt/" name="OTP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-pdf/" name="OTP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-html/" name="OTP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-bmp/" name="OTP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-jpg/" name="OTP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-fodp/" name="OTP TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-gif/" name="OTP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-odp/" name="OTP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-pot/" name="OTP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-potm/" name="OTP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-potx/" name="OTP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-pps/" name="OTP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-pptm/" name="OTP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-svg/" name="OTP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/otp-to-tiff/" name="OTP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}