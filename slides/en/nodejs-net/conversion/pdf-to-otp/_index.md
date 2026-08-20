---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to OTP in Node.js
url: /nodejs-net/conversion/pdf-to-otp/
keywords: PDF to OTP, Convert PDF to OTP, Node.js API, JavaScript Library, PDF, OTP
description: Convert PDF to OTP in Node.js. Use a Node.js library API to convert PDF files to OTP files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PDF to OTP in Node.js" h2="Convert PDF files to OTP files with Aspose.Slides for Node.js via .NET." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to OTP in Node.js" %}}

[**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/) lets developers create, read, edit, and convert presentation files in Node.js applications. Create a `Presentation`, import a `PDF` file with the `addFromPdf` method, and export the presentation to an `OTP` file.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to OTP using Node.js" %}}
To convert `PDF` to `OTP`, create a `Presentation`, import the source file with `addFromPdf`, and export the presentation to an `OTP` file.

{{% blocks/products/pf/agp/code-block title="Node.js code to convert PDF to OTP" offSpacer="true" %}}

```javascript
const presentation = new asposeSlides.Presentation();
try {
    presentation.slides.removeAt(0);
    presentation.slides.addFromPdf("sourceFile.pdf");
    presentation.save("output.otp", asposeSlides.SaveFormat.Otp);
}
finally {
    presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section h2="How to convert PDF to OTP using Aspose.Slides for Node.js via .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="To convert PDF to OTP using Aspose.Slides for Node.js via .NET, import the package, load the source file, and export it in the required format." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for Node.js via .NET**](/slides/nodejs-net/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the `aspose.slides.via.net` package in your Node.js project.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and import the source `PDF` file with `addFromPdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call the `save` method with the output file path and `SaveFormat.Otp`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF files to other supported presentation and export formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}