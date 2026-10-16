---
lastmod: 2026-07-13
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert OTP to SVG in Node.js
url: /nodejs-java/conversion/otp-to-svg/
keywords: OTP to SVG, Convert OTP to SVG, Node.js API, Node.js Library, OTP, SVG
description: Convert OTP to SVG in Node.js. Use the Node.js API to convert OTP files to SVG files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert OTP to SVG in Node.js" h2="Convert OpenDocument Presentation Template files to SVG with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert OTP to SVG using Node.js" variant="code" %}}

To convert `OTP` to `SVG`, create a `Presentation` from the source file and export the required slide to an `SVG` file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert OTP to SVG" >}}
```javascript
const presentation = new aspose.slides.Presentation("sourceFile.otp");
try {
    const slide = presentation.getSlides().get_Item(0);
    const svgStream = java.newInstanceSync("java.io.FileOutputStream", "slide.svg");
    try {
        slide.writeAsSvg(svgStream);
    }
    finally {
        svgStream.close();
    }
}
finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert OTP to SVG in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load an `OTP` file with the `Presentation` class and export a slide to an `SVG` file by using the presentation API.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert OTP to SVG using Aspose.Slides for Node.js via Java API" intro="To convert OTP to SVG using Aspose.Slides for Node.js via Java, import the package, load the source file, and export the required slide." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.java` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `OTP` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `writeAsSvg` method for the required slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert OTP to Other Supported Formats" subTitle="You can also convert OTP files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
