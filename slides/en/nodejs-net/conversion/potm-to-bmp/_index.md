---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTM to BMP in Node.js
url: /nodejs-net/conversion/potm-to-bmp/
keywords: POTM to BMP, Convert POTM to BMP, Node.js API, JavaScript Library, POTM, BMP
description: Convert POTM to BMP in Node.js. Use a Node.js library API to convert POTM files to BMP files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert POTM to BMP in Node.js" h2="Convert PowerPoint template files to BMP images with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/feature-page-section h2="Convert POTM to BMP in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `POTM` file with the `Presentation` class and render each slide as a `BMP` image.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convert POTM to BMP using Node.js" %}}
To convert `POTM` to `BMP`, create a `Presentation` from the source file and render each slide as a `BMP` image.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert POTM to BMP" offSpacer="true" %}}

```javascript
const presentation = new asposeSlides.Presentation("sourceFile.potm");
try {
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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section h2="How to convert POTM to BMP using Aspose.Slides for Node.js via .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert POTM to BMP using Aspose.Slides for Node.js via .NET, import the package, load the source file, and export it in the required format." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.net` package in your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `POTM` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `getImageWithScale` for each `slide` and save the result as a `BMP` image.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert POTM To Other Supported Formats" subTitle="You can also convert POTM and save to other file formats. See all supported formats below:" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
