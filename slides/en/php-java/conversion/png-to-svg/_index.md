---
title: Convert PNG to SVG in PHP
url: /php-java/conversion/png-to-svg/
keywords: PNG to SVG, Convert PNG to SVG, PHP API, PHP Library, PNG, SVG
description: Place a PNG image on a slide and export the slide as SVG in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PNG to SVG in PHP" h2="Place a PNG image on a slide and export the slide as SVG with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PNG to SVG in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can place a PNG image on a presentation slide and write the slide as SVG markup.

The exported SVG preserves the slide layout and contains the raster PNG image; this process does not trace or convert the PNG pixels into vector paths.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PNG to SVG using PHP" %}}
Create a `Presentation`, load the PNG with `Images::fromFile`, match the slide size to the image with `setSize`, add it with `addPictureFrame`, and call `writeAsSvg` for that slide.

{{% blocks/products/pf/agp/code-block title="PHP code for converting PNG into SVG" offSpacer="true" %}}

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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PNG to SVG using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PNG to SVG in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation`, access its first slide, and load the PNG with `Images::fromFile`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Set the slide dimensions with `setSize`, then place the image on the slide with `addPictureFrame`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create an output stream and call `writeAsSvg` for the slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PNG To Other Supported Formats" subTitle="You can also convert PNG and save to other file formats. See all supported formats below:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-html/" name="PNG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
