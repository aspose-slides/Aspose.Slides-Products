---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPT to POTX in PHP
weight: 2220
url: /php-java/conversion/ppt-to-potx/
keywords: "Convert, PowerPoint, PPT, POTX, Presentation, PHP"
description: Convert PPT files to POTX in PHP with Aspose.Slides. Use the sample code to save a PowerPoint 97-2003 presentation as an Open XML PowerPoint template.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPT to POTX in PHP" h2="Powerful PowerPoint PHP library for converting PPT to POTX"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family/"
  downloadLink="https://releases.aspose.com/slides/php-java/"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPT to POTX in PHP" %}}

Convert PPT files to POTX programmatically with [*Aspose.Slides for PHP via Java*](/slides/php-java/). Load a PowerPoint 97-2003 presentation and save it as an Open XML PowerPoint template with a few lines of PHP code.

Aspose.Slides performs the conversion through the `Presentation` class and its `save` method. You can also try the PPT-to-POTX conversion in your [browser](https://products.aspose.app/slides/conversion) before integrating it into your application.

You can install the library from [Composer](https://packagist.org/packages/aspose/slides) using the following command:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
composer require aspose/slides
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Save PPT as POTX in PHP" %}}

Use the free app to see a demonstration of the PPT-to-POTX conversion process.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="This sample code shows PPT-to-POTX conversion in PHP" >}}
```php
$presentation = new Presentation("input.ppt");
try {
    $presentation->save("output.potx", SaveFormat::Potx);
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PPT to POTX in PHP" intro="These are the steps to convert a PPT file to POTX using PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPT file into a `Presentation` instance.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with the output file path and `SaveFormat::Potx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}The presentation is written to the specified POTX file.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the PHP conversion sample, make sure that you have the following prerequisites." %}}

1. Install PHP 7 or later, add the PHP directory to the system `PATH`, and set `allow_url_include` to `On` in `php.ini`.
1. Install JRE 8 and set the `JAVA_HOME` environment variable to the installed JRE directory.
1. Install Apache Tomcat 8.0 as described in the [installation guide](https://docs.aspose.com/slides/php-java/installation/).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPT to POTX"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PPT to many other file formats. See other supported conversions below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
