---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSX to POT in PHP
weight: 1990
url: /php-java/conversion/ppsx-to-pot/
keywords: "Convert, PowerPoint, PPSX, POT, Presentation, PHP"
description: Convert PPSX files to POT in PHP with Aspose.Slides. Use the sample code to save a PowerPoint slide show as a PowerPoint 97-2003 template.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPSX to POT in PHP" h2="Powerful PowerPoint PHP library for converting PPSX to POT"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family/"
  downloadLink="https://releases.aspose.com/slides/php-java/"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSX to POT in PHP" %}}

Convert PPSX files to POT programmatically with [*Aspose.Slides for PHP via Java*](/slides/php-java/). Load a PowerPoint Open XML Slide Show and save it as a PowerPoint 97-2003 Template with a few lines of PHP code.

Aspose.Slides performs the conversion through the `Presentation` class and its `save` method. You can also try the PPSX-to-POT conversion in your [browser](https://products.aspose.app/slides/conversion) before integrating it into your application.

You can install the library from [Composer](https://packagist.org/packages/aspose/slides) using the following command:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
composer require aspose/slides
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Save PPSX as POT in PHP" %}}

Use the free app to see a demonstration of the PPSX-to-POT conversion process.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="This sample code shows PPSX-to-POT conversion in PHP" >}}
```php
$presentation = new Presentation("input.ppsx");
try {
    $presentation->save("output.pot", SaveFormat::Pot);
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PPSX to POT in PHP" intro="These are the steps to convert a PPSX file to POT using PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPSX file into a `Presentation` instance.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with the output file path and `SaveFormat::Pot`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}The presentation is written to the specified POT file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the PHP conversion sample, make sure that you have the following prerequisites." %}}

1. Install PHP 7 or later, add the PHP directory to the system `PATH`, and set `allow_url_include` to `On` in `php.ini`.
1. Install JRE 8 and set the `JAVA_HOME` environment variable to the installed JRE directory.
1. Install Apache Tomcat 8.0 as described in the [installation guide](https://docs.aspose.com/slides/php-java/installation/).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPSX to POT"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PPSX to many other file formats. See other supported conversions below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
