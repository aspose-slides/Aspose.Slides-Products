---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert POTX to JPG in PHP
weight: 1310
url: /php-java/conversion/potx-to-jpg/
keywords: "Convert, PowerPoint, POTX, JPG, Presentation, PHP"
description: Render the slides in a POTX template as JPG images in PHP with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert POTX to JPG in PHP" h2="Render PowerPoint POTX template slides as JPG images"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/php-java/"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert POTX to JPG in PHP" %}}

[*Aspose.Slides for PHP via Java*](/slides/php-java/) can load a PowerPoint POTX template and render each slide as a JPG image without Microsoft PowerPoint.

Call `getImage` for each slide and save the rendered image with `ImageFormat::Jpeg`. A scale factor of `2.0` produces an image at twice the slide's default rendering dimensions.

You can install the library from [Composer](https://packagist.org/packages/aspose/slides) using the following command:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> composer require aspose/slides
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Save POTX as JPG in PHP" %}}

Use the free app to see a demonstration of the POTX to JPG conversion process.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="This sample code shows POTX to JPG PHP Conversion" >}}
```php
$presentation = new Presentation("input.potx");
try {
    $slideCount = java_values($presentation->getSlides()->size());

    for ($slideIndex = 0; $slideIndex < $slideCount; $slideIndex++) {
        $slide = $presentation->getSlides()->get_Item($slideIndex);
        $slideImage = $slide->getImage(2.0, 2.0);

        try {
            $filePath = "slide_" . ($slideIndex + 1) . ".jpg";
            $slideImage->save($filePath, ImageFormat::Jpeg);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert POTX to JPG in PHP" intro="These are the steps to convert a POTX file to JPG using PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the POTX file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render each slide by calling `getImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save each rendered slide with `ImageFormat::Jpeg`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the PHP conversion example, make sure that you have the following prerequisites." %}}

1. Install PHP 7 or later, add the PHP directory to the system `PATH`, and set `allow_url_include` to `On` in the `php.ini` file.
1. Install JRE 8 and set the `JAVA_HOME` environment variable to the installed JRE directory.
1. Install and configure Apache Tomcat with PHP/Java Bridge as described in the [installation guide](https://docs.aspose.com/slides/php-java/installation/).

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert POTX to JPG"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert POTX to many other file formats. See other supported conversions below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
