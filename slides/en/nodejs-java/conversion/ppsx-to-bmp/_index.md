---
title: Convert PPSX to BMP in Node.js
url: /nodejs-java/conversion/ppsx-to-bmp/
keywords: PPSX to BMP, Convert PPSX to BMP, Node.js API, Node.js Library, PPSX, BMP
description: Convert PPSX to BMP in Node.js. Use Node.js library API to convert PPSX files to BMPs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPSX to BMP in Node.js" h2="Aspose.Slides for Node.js via Java is a powerful and easy-to-use library that allows you to convert PowerPoint presentations to various formats in Node.js. It supports all presentation elements and formats and provides a rich API to access and modify them. It also allows you to export your slides to various formats for further processing or sharing." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PPSX to BMP in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/nodejs-java/) is a powerful Node.js library for creating and manipulating presentation files. Moreover, it provides flexible ways to convert PPSX to BMP. Using **Aspose.Slides for Node.js via Java**, any developer or application can convert PPSX to BMP files with just a few lines of code.

As a modern document processing API, Aspose.Slides for Node.js exports PPSX files to BMP file formats quickly. Aspose PowerPoint library allows you to convert PPSX to BMPs and many other file formats

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPSX to BMP using Node.js" %}}
To convert the PPSX to BMP, you will need to create Presentation from PPSX file and save it as BMP.

{{% blocks/products/pf/agp/code-block title="Node.js code for convert PPSX into BMP" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppsx");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".bmp");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "bmp", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PPSX to BMP using using Aspose.Slides for Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert PPSX to BMP using Aspose.Slides for Node.js via Java, you need to import the package in your JavaScript file and create an instance of the Presentation class. The Presentation class represents a PowerPoint document and provides methods to access and manipulate its elements." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Node.js via Java**](https://products.aspose.com/slides/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Node.js project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source PPSX files in Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as BMP file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PPSX To Other Supported Formats" subTitle="You can also convert PPSX and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-png/" name="PPSX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-jpg/" name="PPSX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nodejs-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}