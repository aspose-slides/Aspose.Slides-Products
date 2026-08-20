---
lastmod: 2026-07-20
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert SVG to PNG in PHP
url: /php-java/conversion/svg-to-png/
keywords: SVG to PNG, Convert SVG to PNG, PHP API, PHP Library, SVG, PNG
description: Convert SVG files to PNG images in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert SVG to PNG in PHP" h2="Add an SVG file to a slide and render it as a PNG image with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert SVG to PNG in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can add an `SVG` image to a presentation slide and render that slide in `PNG` format.

Load the SVG content into a `SvgImage`, add it to the presentation image collection, and save the rendered slide image with `ImageFormat::Png`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert SVG to PNG using PHP" %}}
To convert `SVG` to `PNG`, add the source image to a `Presentation`, match the slide size to the image, and render the slide with `getImage`.

{{% blocks/products/pf/agp/code-block title="PHP code for converting SVG into PNG" offSpacer="true" %}}

```php
$presentation = new Presentation();
try {
    $slide = $presentation->getSlides()->get_Item(0);

    $svgContent = file_get_contents("image.svg");
    $svgImage = new SvgImage($svgContent);
    $presentationImage = $presentation->getImages()->addImage($svgImage);

    $imageWidth = java_values($presentationImage->getWidth());
    $imageHeight = java_values($presentationImage->getHeight());

    $presentation->getSlideSize()->setSize(
        $imageWidth, $imageHeight, SlideSizeScaleType::DoNotScale);

    $slide->getShapes()->addPictureFrame(
        ShapeType::Rectangle, 0, 0, $imageWidth, $imageHeight, $presentationImage);

    $slideImage = $slide->getImage(1.0, 1.0);
    try {
        $slideImage->save("output.png", ImageFormat::Png);
    } finally {
        $slideImage->dispose();
    }
} finally {
    $presentation->dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert SVG to PNG using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert SVG to PNG in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation`, access its first slide, and load the SVG content into a `SvgImage`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Add the SVG image with `addPictureFrame`, render the slide with `getImage`, and save it with `ImageFormat::Png`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert SVG to Other Supported Formats" subTitle="You can also convert SVG files and save them to other supported formats." >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
