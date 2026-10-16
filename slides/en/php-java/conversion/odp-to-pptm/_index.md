---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert ODP to PPTM in PHP 
weight: 370
url: /php-java/conversion/odp-to-pptm/ 
keywords: "Convert, PowerPoint, ODP, PPTM, Presentation, PHP"
description: Convert ODP presentations to macro-enabled PowerPoint PPTM files in PHP with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert ODP to PPTM in PHP" h2="Export ODP presentations as macro-enabled PowerPoint PPTM files with Aspose.Slides for PHP via Java"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family/"
  downloadLink="https://releases.aspose.com/slides/php-java/"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert ODP to PPTM in PHP" %}}

Use [*Aspose.Slides for PHP via Java*](/slides/php-java/) to load an ODP presentation and export it as a macro-enabled PowerPoint PPTM file.

Call `save` with `SaveFormat::Pptm` to create the output file. You can also test ODP conversion in your [browser](https://products.aspose.app/slides/conversion).

You can install the library from [Composer](https://packagist.org/packages/aspose/slides) using the following command:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
composer require aspose/slides
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Save ODP as PPTM in PHP" %}}

Use the free app to see a demonstration of the ODP-to-PPTM conversion process.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="This sample code shows ODP to PPTM PHP Conversion" >}}
```php
$presentation = new Presentation("input.odp");
try {
    $presentation->save("output.pptm", SaveFormat::Pptm);
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert ODP to PPTM in PHP" intro="These are the steps to convert an ODP file to PPTM using PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the ODP file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with the output file path and `SaveFormat::Pptm`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}The PPTM file is written to the specified path.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the PHP conversion example, make sure that you have the following prerequisites." %}}

1. Install PHP 7 or later, add the PHP directory to the system `PATH`, and set `allow_url_include` to `On` in the `php.ini` file.
1. Install JRE 8 and set the `JAVA_HOME` environment variable to the installed JRE directory.
1. Install and configure Apache Tomcat with PHP/Java Bridge as described in the [installation guide](https://docs.aspose.com/slides/php-java/installation/).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert ODP to PPTM"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert ODP to many other file formats. See other supported conversions below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
