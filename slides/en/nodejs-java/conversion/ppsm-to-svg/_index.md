---
title: Convert PPSM to SVG in Node.js
url: /nodejs-java/conversion/ppsm-to-svg/
keywords: PPSM to SVG, Convert PPSM to SVG, Node.js API, Node.js Library, PPSM, SVG
description: Convert PPSM to SVG in Node.js. Use Node.js library API to convert PPSM files to SVGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSM to SVG in Node.js" h2="Aspose.Slides for Node.js via Java is a powerful and easy-to-use library that allows you to convert PowerPoint presentations to various formats in Node.js. It supports all presentation elements and formats and provides a rich API to access and modify them. It also allows you to export your slides to various formats for further processing or sharing." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSM to SVG in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/nodejs-java/) is a powerful Node.js library for creating and manipulating presentation files. Moreover, it provides flexible ways to convert PPSM to SVG. Using **Aspose.Slides for Node.js via Java**, any developer or application can convert PPSM to SVG files with just a few lines of code.

As a modern document processing API, Aspose.Slides for Node.js exports PPSM files to SVG file formats quickly. Aspose PowerPoint library allows you to convert PPSM to SVGs and many other file formats

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPSM to SVG using Node.js" %}}
To convert the PPSM to SVG, you will need to create Presentation from PPSM file and save it as SVG.

{{% blocks/products/pf/agp/code-block title="Node.js code for convert PPSM into SVG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppsm");
try
{
    var slide = pres.getSlides().get_Item(0);
    var svgStream = java.newInstanceSync("java.io.FileOutputStream", "image.svg");
    slide.writeAsSvg(svgStream);
    svgStream.close();
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPSM to SVG using using Aspose.Slides for Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert PPSM to SVG using Aspose.Slides for Node.js via Java, you need to import the package in your JavaScript file and create an instance of the Presentation class. The Presentation class represents a PowerPoint document and provides methods to access and manipulate its elements." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Node.js project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source PPSM files in Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as SVG file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSM To Other Supported Formats" subTitle="You can also convert PPSM and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-png/" name="PPSM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-bmp/" name="PPSM TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-jpg/" name="PPSM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-potm/" name="PPSM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}