---
lastmod: 2026-07-13
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POT to SVG in Node.js
url: /nodejs-java/conversion/pot-to-svg/
keywords: POT to SVG, Convert POT to SVG, Node.js API, Node.js Library, POT, SVG
description: Convert POT to SVG in Node.js. Use the Node.js API to convert POT files to SVG files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert POT to SVG in Node.js" h2="Convert PowerPoint Template files to SVG with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert POT to SVG in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `POT` file with the `Presentation` class and export its slides to `SVG` files by using the presentation API.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert POT to SVG using Node.js" %}}
To convert `POT` to `SVG`, create a `Presentation` from the source file and export each slide with `writeAsSvg`.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert POT to SVG" offSpacer="true" %}}

```javascript
const presentation = new aspose.slides.Presentation("sourceFile.pot");
try {
    const slideCount = presentation.getSlides().size();
    for (let slideIndex = 0; slideIndex < slideCount; slideIndex++) {
        const slide = presentation.getSlides().get_Item(slideIndex);
        const filePath = "slide_" + slide.getSlideNumber() + ".svg";
        const svgStream = java.newInstanceSync("java.io.FileOutputStream", filePath);
        try {
            slide.writeAsSvg(svgStream);
        }
        finally {
            svgStream.close();
        }
    }
}
finally {
    presentation.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert POT to SVG using Aspose.Slides for Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert POT to SVG using Aspose.Slides for Node.js via Java, import the package, load the source file, and export slides as SVG files." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.java` package in your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `POT` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call the `writeAsSvg` method for each slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert POT to Other Supported Formats" subTitle="You can also convert POT files to other supported presentation and export formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
