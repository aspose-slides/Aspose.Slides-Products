---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert HTML to XML in PHP
url: /php-java/conversion/html-to-xml/
keywords: HTML to XML, Convert HTML to XML, PHP API, PHP Library, HTML, XML
description: Convert HTML content to PowerPoint XML Presentation format in PHP with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert HTML to XML in PHP" h2="Import HTML content into presentation slides and save the result in PowerPoint XML Presentation format." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert HTML to XML using PHP" variant="code" %}}

To convert HTML content to PowerPoint XML, create a `Presentation`, import the HTML with `addFromHtml`, and call `save` with `SaveFormat::Xml`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP code for converting HTML into XML" >}}
```php
$presentation = new Presentation();
try {
    $slides = $presentation->getSlides();
    $slides->removeAt(0);

    $htmlContent = file_get_contents("input.html");
    $slides->addFromHtml($htmlContent);

    $presentation->save("output.xml", SaveFormat::Xml);
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert HTML to XML in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can import HTML content into presentation slides and save the resulting presentation in PowerPoint XML Presentation format with a few lines of PHP code.

The generated XML represents a presentation rather than a generic transformation of the source HTML markup. Aspose.Slides can also export the imported content to PowerPoint, PDF, images, and other supported formats.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert HTML to XML using Aspose.Slides for PHP API" intro="These are the steps to convert HTML to XML in PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure Aspose.Slides in your PHP project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Read the HTML content with `file_get_contents` and pass it to `addFromHtml`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with the output file path and `SaveFormat::Xml`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert HTML To Other Supported Formats" subTitle="You can also convert HTML and save to other file formats. See all supported formats below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
