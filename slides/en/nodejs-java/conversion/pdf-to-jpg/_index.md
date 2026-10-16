---
lastmod: 2026-07-13
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to JPG in Node.js
url: /nodejs-java/conversion/pdf-to-jpg/
keywords: PDF to JPG, Convert PDF to JPG, Node.js API, Node.js Library, PDF, JPG
description: Convert PDF to JPG in Node.js. Use the Node.js API to convert PDF files to JPG images.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to JPG in Node.js" h2="Convert PDF files to JPG with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to JPG using Node.js" variant="code" %}}

To convert `PDF` to `JPG`, create a `Presentation`, import the source file with `addFromPdf`, and render the imported slides as images.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert PDF to JPG" >}}
```javascript
const presentation = new aspose.slides.Presentation();
try {
    presentation.getSlides().removeAt(0);
    presentation.getSlides().addFromPdf("sourceFile.pdf");

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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to JPG in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets you import `PDF` files into a presentation and render the imported slides as `JPG` images. With this Node.js API, you can convert `PDF` content without Adobe Acrobat.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PDF to JPG using Aspose.Slides for Node.js via Java API" intro="To convert PDF to JPG using Aspose.Slides for Node.js via Java, import the package, import the source file into a presentation, and export slides as images." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.java` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the source `PDF` file with `addFromPdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render each slide with `getImage` and save it with `ImageFormat.Jpeg`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
