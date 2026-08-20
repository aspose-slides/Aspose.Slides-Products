---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert JPG to Image in PHP
url: /php-java/conversion/jpg-to-image/
keywords: JPG to Image, Convert JPG to Image, PHP API, PHP Library, JPG, Image
description: Convert a JPG file to a PNG image in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert JPG to Image in PHP" h2="Place a JPG image on a slide and render the slide as a PNG image with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert JPG to Image in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you add a JPG image to a presentation slide and render the slide in a supported image format. The example below uses PNG output.

Use `Images::fromFile` to load the JPG file, `getImage` to render the slide, and `ImageFormat::Png` to select PNG output.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert JPG to Image using PHP" %}}
To convert JPG to an image, add the source file to a `Presentation`, place it on a slide, render the slide with `getImage`, and save the result with `ImageFormat::Png`.

{{% blocks/products/pf/agp/code-block title="PHP code for converting JPG into Image" offSpacer="true" %}}

```php
$presentation = new Presentation();
try {
    $slide = $presentation->getSlides()->get_Item(0);

    $sourceImage = Images::fromFile("input.jpg");
    try {
        $embeddedImage = $presentation->getImages()->addImage($sourceImage);
    } finally {
        $sourceImage->dispose();
    }

    $imageWidth = java_values($embeddedImage->getWidth());
    $imageHeight = java_values($embeddedImage->getHeight());

    $slide->getShapes()->addPictureFrame(
        ShapeType::Rectangle, 0, 0, $imageWidth, $imageHeight, $embeddedImage);

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

{{< blocks/products/pf/feature-page-section  h2="How to convert JPG to Image using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert JPG to Image in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation`, access its first slide, and load the JPG file with `Images::fromFile`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Add the JPG image with `addPictureFrame`, render the slide with `getImage`, and save it with `ImageFormat::Png`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert JPG To Other Supported Formats" subTitle="You can also convert JPG and save to other file formats. See all supported formats below:" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
