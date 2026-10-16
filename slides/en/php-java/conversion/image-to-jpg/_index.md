---
lastmod: 2026-09-30
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert Image to JPG in PHP
url: /php-java/conversion/image-to-jpg/
keywords: Image to JPG, Convert Image to JPG, PHP API, PHP Library, Image, JPG
description: Convert an image to JPG in PHP with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert Image to JPG in PHP" h2="Load an image and save it in JPEG format with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert Image to JPG using PHP" variant="code" %}}

To convert an image to JPG, load it with `Images::fromFile`, save it with `ImageFormat::Jpeg`, and dispose of it when you are done.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP code for converting Image into JPG" >}}
```php
$image = Images::fromFile("input.png");
try {
    $image->save("output.jpg", ImageFormat::Jpeg);
} finally {
    $image->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert Image to JPG in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can load an image file and save it in JPEG format, keeping the image's width and height.

The image API uses `Images::fromFile` to load the source image, `save` to write it, and `ImageFormat::Jpeg` to select JPEG output.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert Image to JPG using Aspose.Slides for PHP API" intro="These are the steps to convert Image to JPG in PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure Aspose.Slides in your PHP project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source image with `Images::fromFile`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the image with `save` and `ImageFormat::Jpeg`, then call `dispose` to release it.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert Image To Other Supported Formats" subTitle="You can also convert Image and save to other file formats. See all supported formats below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
