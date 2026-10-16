---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PNG to SVG in PHP
url: /php-java/conversion/png-to-svg/
keywords: PNG to SVG, Convert PNG to SVG, PHP API, PHP Library, PNG, SVG
description: Place a PNG image on a slide and export the slide as SVG in PHP with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PNG to SVG in PHP" h2="Place a PNG image on a slide and export the slide as SVG with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to SVG using PHP" variant="code" %}}

Create a `Presentation`, load the PNG with `Images::fromFile`, match the slide size to the image with `setSize`, add it with `addPictureFrame`, and call `writeAsSvg` for that slide.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP code for converting PNG into SVG" >}}
```php
$presentation = new Presentation();
try {
    $slide = $presentation->getSlides()->get_Item(0);

    $sourceImage = Images::fromFile("input.png");
    try {
        $embeddedImage = $presentation->getImages()->addImage($sourceImage);
    } finally {
        $sourceImage->dispose();
    }

    $imageWidth = java_values($embeddedImage->getWidth());
    $imageHeight = java_values($embeddedImage->getHeight());

    $presentation->getSlideSize()->setSize(
        $imageWidth, $imageHeight, SlideSizeScaleType::DoNotScale);

    $slide->getShapes()->addPictureFrame(
        ShapeType::Rectangle, 0, 0, $imageWidth, $imageHeight, $embeddedImage);

    $outputStream = new Java("java.io.FileOutputStream", "output.svg");
    try {
        $slide->writeAsSvg($outputStream);
    } finally {
        $outputStream->close();
    }
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to SVG in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can place a PNG image on a presentation slide and write the slide as SVG markup.

The exported SVG preserves the slide layout and contains the raster PNG image; this process does not trace or convert the PNG pixels into vector paths.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PNG to SVG using Aspose.Slides for PHP API" intro="These are the steps to convert PNG to SVG in PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation`, access its first slide, and load the PNG with `Images::fromFile`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Set the slide dimensions with `setSize`, then place the image on the slide with `addPictureFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create an output stream and call `writeAsSvg` for the slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PNG To Other Supported Formats" subTitle="You can also convert PNG and save to other file formats. See all supported formats below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
