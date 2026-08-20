---
lastmod: 2026-07-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPT to SVG in Node.js
url: /nodejs-java/conversion/ppt-to-svg/
keywords: PPT to SVG, Convert PPT to SVG, Node.js API, Node.js Library, PPT, SVG
description: Convert PPT to SVG in Node.js. Use a Node.js library API to convert PPT files to SVG files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT to SVG in Node.js" h2="Convert PowerPoint binary presentation files to SVG files with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPT to SVG in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load a `PPT` file with the `Presentation` class and export a slide to an `SVG` file.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convert PPT to SVG using Node.js" %}}
To convert `PPT` to `SVG`, create a `Presentation` from the source file and export the required slide to an `SVG` file.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert PPT to SVG" offSpacer="true" %}}

```javascript
const presentation = new aspose.slides.Presentation("sourceFile.ppt");
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

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section h2="How to convert PPT to SVG using Aspose.Slides for Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert PPT to SVG using Aspose.Slides for Node.js via Java, import the package, load the source file with the Presentation class, and export the required slide." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.java` package in your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source `PPT` file with the `Presentation` class.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call the ``writeAsSvg`` method for the required slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPT to Other Supported Formats" subTitle="You can also convert PPT files to other supported presentation and export formats." >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}