---
lastmod: 2026-07-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert OTP to PNG in Node.js
url: /nodejs-net/conversion/otp-to-png/
keywords: OTP to PNG, Convert OTP to PNG, Node.js API, JavaScript Library, OTP, PNG
description: Convert OTP to PNG in Node.js. Use a Node.js library API to convert OTP files to PNG images.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert OTP to PNG in Node.js" h2="Convert OpenDocument template files to PNG images with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert OTP to PNG using Node.js" variant="code" %}}

To convert `OTP` to `PNG`, create a `Presentation` from the source file and render each slide as a `PNG` image.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert OTP to PNG" >}}
```javascript
const presentation = new asposeSlides.Presentation("sourceFile.otp");
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert OTP to PNG in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load an `OTP` file with the `Presentation` class and render each slide as a `PNG` image.

Aspose.Slides supports high-quality presentation conversion and lets you export `OTP` slides to `PNG` images for previews, thumbnails, reports, or other processing workflows.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert OTP to PNG using Aspose.Slides for Node.js via .NET API" intro="To convert OTP to PNG using Aspose.Slides for Node.js via .NET, import the package, load the source file, and export slides as images." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.net` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `OTP` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render each slide with `getImageWithScale` and save it with `ImageFormat.Png`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert OTP to Other Supported Formats" subTitle="You can also convert OTP files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
