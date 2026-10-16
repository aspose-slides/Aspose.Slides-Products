---
lastmod: 2026-07-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to BMP in Node.js
url: /nodejs-net/conversion/pdf-to-bmp/
keywords: PDF to BMP, Convert PDF to BMP, Node.js API, JavaScript Library, PDF, BMP
description: Convert PDF to BMP in Node.js. Use a Node.js library API to convert PDF files to BMP files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to BMP in Node.js" h2="Convert PDF files to BMP images with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to BMP using Node.js" variant="code" %}}

To convert `PDF` to `BMP`, create a `Presentation`, import the source file with `addFromPdf`, and render each slide as a `BMP` image.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert PDF to BMP" >}}
```javascript
const presentation = new asposeSlides.Presentation();
try {
    presentation.slides.removeAt(0);
    presentation.slides.addFromPdf("sourceFile.pdf");

    const slideCount = presentation.slides.length;
    for (let slideIndex = 0; slideIndex < slideCount; slideIndex++) {
        const slide = presentation.slides.get(slideIndex);
        const slideImage = slide.getImageWithScale(2, 2);
        try {
            const filePath = "slide_" + slideIndex + ".bmp";
            slideImage.save(filePath, asposeSlides.ImageFormat.Bmp);
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to BMP in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. Create a `Presentation`, import a `PDF` file with the `addFromPdf` method, and render each slide as a `BMP` image.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PDF to BMP using Aspose.Slides for Node.js via .NET API" intro="To convert PDF to BMP using Aspose.Slides for Node.js via .NET, import the package, load the source file, and export it in the required format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.net` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and import the source `PDF` file with `addFromPdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the source `PDF` file with `addFromPdf`, then call `getImageWithScale` for each `slide` and save the result as a `BMP` file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
