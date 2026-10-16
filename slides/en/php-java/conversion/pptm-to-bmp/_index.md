---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PPTM to BMP in PHP
weight: 2320
url: /php-java/conversion/pptm-to-bmp/
keywords: "Convert, PowerPoint, PPTM, BMP, Presentation, PHP"
description: Convert PPTM slides to BMP images in PHP with Aspose.Slides. Use the sample code to render each slide in a macro-enabled PowerPoint presentation as a separate BMP file.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PPTM to BMP in PHP" h2="Powerful PowerPoint PHP library for converting PPTM to BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family/"
  downloadLink="https://releases.aspose.com/slides/php-java/"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PPTM to BMP in PHP" %}}

Convert PPTM slides to BMP programmatically with [*Aspose.Slides for PHP via Java*](/slides/php-java/). Load a macro-enabled PowerPoint presentation and render every slide as an individual bitmap image with a few lines of PHP code.

Aspose.Slides renders a slide through its `getImage` method and saves the result through the image object's `save` method. You can also try the PPTM-to-BMP conversion in your [browser](https://products.aspose.app/slides/conversion) before integrating it into your application.

You can install the library from [Composer](https://packagist.org/packages/aspose/slides) using the following command:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
composer require aspose/slides
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Save PPTM as BMP in PHP" %}}

Use the free app to see a demonstration of the PPTM-to-BMP conversion process.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="This sample code shows PPTM-to-BMP conversion in PHP" >}}
```php
$presentation = new Presentation("input.pptm");
try {
    $slideCount = java_values($presentation->getSlides()->size());

    for ($slideIndex = 0; $slideIndex < $slideCount; $slideIndex++) {
        $slide = $presentation->getSlides()->get_Item($slideIndex);
        $slideImage = $slide->getImage(2.0, 2.0);

        try {
            $filePath = "slide_" . ($slideIndex + 1) . ".bmp";
            $slideImage->save($filePath, ImageFormat::Bmp);
        } finally {
            $slideImage->dispose();
        }
    }
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert PPTM to BMP in PHP" intro="These are the steps to convert a PPTM file to BMP using PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPTM file into a `Presentation` instance.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access each slide through a variable and call its `getImage` method.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save each rendered slide to the generated file path with `ImageFormat::Bmp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the PHP conversion sample, make sure that you have the following prerequisites." %}}

1. Install PHP 7 or later, add the PHP directory to the system `PATH`, and set `allow_url_include` to `On` in `php.ini`.
1. Install JRE 8 and set the `JAVA_HOME` environment variable to the installed JRE directory.
1. Install Apache Tomcat 8.0 as described in the [installation guide](https://docs.aspose.com/slides/php-java/installation/).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPTM to BMP"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert PPTM to many other file formats. See other supported conversions below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
