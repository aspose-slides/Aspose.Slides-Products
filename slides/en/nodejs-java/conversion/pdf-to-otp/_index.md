---
lastmod: 2026-07-13
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to OTP in Node.js
url: /nodejs-java/conversion/pdf-to-otp/
keywords: PDF to OTP, Convert PDF to OTP, Node.js API, Node.js Library, PDF, OTP
description: Convert PDF to OTP in Node.js. Use the Node.js API to convert PDF files to OTP files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PDF to OTP in Node.js" h2="Convert PDF files to OTP with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to OTP using Node.js" variant="code" %}}

To convert `PDF` to `OTP`, create a `Presentation`, import the source file with `addFromPdf`, and save the presentation with `SaveFormat.Otp`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert PDF to OTP" >}}
```javascript
const presentation = new aspose.slides.Presentation();
try {
    presentation.getSlides().removeAt(0);
    presentation.getSlides().addFromPdf("sourceFile.pdf");
    presentation.save("output.otp", aspose.slides.SaveFormat.Otp);
}
finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PDF to OTP in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets you import `PDF` files into a presentation and save the result as `OTP`. With this Node.js API, you can convert `PDF` content without Adobe Acrobat.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PDF to OTP using Aspose.Slides for Node.js via Java API" intro="To convert PDF to OTP using Aspose.Slides for Node.js via Java, import the package, import the source file into a presentation, and export it in the required format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.java` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the source `PDF` file with `addFromPdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `save` method with the output file path and `SaveFormat.Otp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PDF to Other Supported Formats" subTitle="You can also convert PDF files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
