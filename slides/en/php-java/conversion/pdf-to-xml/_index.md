---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PDF to XML in PHP
url: /php-java/conversion/pdf-to-xml/
keywords: PDF to XML, Convert PDF to XML, PowerPoint XML Presentation, PHP API, PHP Library, PDF, XML
description: Import PDF pages and save the result in PowerPoint XML Presentation format in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PDF to XML in PHP" h2="Import PDF pages into presentation slides and save the result in PowerPoint XML Presentation format." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to XML in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can import PDF pages into presentation slides and save the resulting presentation in PowerPoint XML Presentation format.

The generated XML represents a presentation and preserves the imported pages as slide content; it does not extract the PDF's logical structure into a generic XML schema.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to XML using PHP" %}}
Create a `Presentation`, remove its default slide, import the PDF pages with `addFromPdf`, and call `save` with `SaveFormat::Xml`.

{{% blocks/products/pf/agp/code-block title="PHP code for converting PDF into XML" offSpacer="true" %}}

```php
$presentation = new Presentation();
try {
    $presentation->getSlides()->removeAt(0);
    $presentation->getSlides()->addFromPdf("document.pdf");

    $presentation->save("output.xml", SaveFormat::Xml);
} finally {
    $presentation->dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PDF to XML using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PDF to XML in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and remove its default slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the PDF pages with `addFromPdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with the output file path and `SaveFormat::Xml`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PDF To Other Supported Formats" subTitle="You can also convert PDF and save to other file formats. See all supported formats below:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
