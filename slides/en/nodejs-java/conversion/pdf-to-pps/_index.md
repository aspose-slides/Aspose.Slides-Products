---
title: Convert PDF to PPS in Node.js
url: /nodejs-java/conversion/pdf-to-pps/
keywords: PDF to PPS, Convert PDF to PPS, Node.js API, Node.js Library, PDF, PPS
description: Convert PDF to PPS in Node.js. Use the Node.js API to convert PDF files to PPS files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PDF to PPS in Node.js" h2="Convert PDF files to PPS with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to PPS in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets you import `PDF` files into a presentation and save the result as `PPS`. With this Node.js API, you can convert `PDF` content without Adobe Acrobat.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to PPS using Node.js" %}}
To convert `PDF` to `PPS`, create a `Presentation`, import the source file with `addFromPdf`, and save the presentation with `SaveFormat.Pps`.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert PDF to PPS" offSpacer="true" %}}

```javascript
const presentation = new aspose.slides.Presentation();
try {
    presentation.getSlides().removeAt(0);
    presentation.getSlides().addFromPdf("sourceFile.pdf");
    presentation.save("output.pps", aspose.slides.SaveFormat.Pps);
}
finally {
    presentation.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PDF to PPS using Aspose.Slides for Node.js via Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert PDF to PPS using Aspose.Slides for Node.js via Java, import the package, import the source file into a presentation, and export it in the required format." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.java` package in your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the source `PDF` file with `addFromPdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call the `save` method with the output file path and `SaveFormat.Pps`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF files to other supported presentation and export formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/nodejs-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}