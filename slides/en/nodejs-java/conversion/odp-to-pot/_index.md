---
lastmod: 2026-07-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert ODP to POT in Node.js
url: /nodejs-java/conversion/odp-to-pot/
keywords: ODP to POT, Convert ODP to POT, Node.js API, Node.js Library, ODP, POT
description: Convert ODP to POT in Node.js. Use the Node.js API to convert ODP files to POT files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert ODP to POT in Node.js" h2="Convert OpenDocument Presentation files to POT with Aspose.Slides for Node.js via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert ODP to POT using Node.js" variant="code" %}}

To convert `ODP` to `POT`, create a `Presentation` from the source file and export it to a `POT` file.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Node.js code to convert ODP to POT" >}}
```javascript
const presentation = new aspose.slides.Presentation("sourceFile.odp");
try {
    presentation.save("output.pot", aspose.slides.SaveFormat.Pot);
}
finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert ODP to POT in Node.js" %}}

[**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/) lets developers create, read, edit, and convert presentation files in Node.js applications. You can load an `ODP` file with the `Presentation` class and export it to a `POT` file by using the presentation API.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert ODP to POT using Aspose.Slides for Node.js via Java API" intro="To convert ODP to POT using Aspose.Slides for Node.js via Java, import the package, load the source file with the Presentation class, and export it in the required format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for Node.js via Java**](/slides/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Import the `aspose.slides.via.java` package in your Node.js project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `ODP` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `save` method with the output file path and `SaveFormat.Pot`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert ODP to Other Supported Formats" subTitle="You can also convert ODP files to other supported presentation and export formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
