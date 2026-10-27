---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPSM to PPT in PHP
weight: 1830
url: /php-java/conversion/ppsm-to-ppt/
keywords: "Convert, PowerPoint, PPSM, PPT, Presentation, PHP"
description: Sample PHP code for converting PPSM presentations to PPT files with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPSM to PPT in PHP" h2="Powerful PowerPoint PHP library for converting PPSM to PPT"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family/"
  downloadLink="https://releases.aspose.com/slides/php-java/"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPSM to PPT in PHP" %}}

Need to convert PPSM files to PPT programmatically? With [*Aspose.Slides for PHP via Java*](/slides/php-java/), you can export a PPSM presentation as a PPT file with a few lines of PHP code.

Aspose.Slides provides a straightforward presentation-processing API for PPSM-to-PPT conversion. You can also test presentation conversions in your [browser](https://products.aspose.app/slides/conversion) or export PPSM files to many other supported formats.

You can install the library from [Composer](https://packagist.org/packages/aspose/slides) using the following command:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
composer require aspose/slides
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Save PPSM as PPT in PHP" %}}

Use the free app to see a demonstration of the PPSM-to-PPT conversion process.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="This sample code shows PPSM to PPT PHP Conversion" >}}
```php
$presentation = new Presentation("input.ppsm");
try {
    $presentation->save("output.ppt", SaveFormat::Ppt);
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PPSM to PPT in PHP" intro="These are the steps to convert a PPSM file to PPT using PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPSM file into a `Presentation` instance.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with the output file path and `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}The presentation is written to the specified PPT file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the PHP conversion sample, make sure that you have the following prerequisites." %}}

1. Install PHP 7, add the PHP directory to the system `PATH`, and set `allow_url_include` to `On` in `php.ini`.
1. Install JRE 8 and set the `JAVA_HOME` environment variable to the installed JRE directory.
1. Install Apache Tomcat 8.0 as described in the [installation guide](https://docs.aspose.com/slides/php-java/installation/).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PPSM to many other file formats. See other supported conversions below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
