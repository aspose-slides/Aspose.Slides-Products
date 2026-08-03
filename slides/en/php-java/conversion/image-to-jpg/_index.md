---
title: Convert Image to JPG in PHP
url: /php-java/conversion/image-to-jpg/
keywords: Image to JPG, Convert Image to JPG, PHP API, PHP Library, Image, JPG
description: Convert an image to JPG in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert Image to JPG in PHP" h2="Add an image to a slide and render it in JPEG format with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert Image to JPG in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can add supported raster or vector images to presentation slides and render the slides in JPEG format.

The modern image API uses `Images::fromFile` to load the source image, `getImage` to render the slide, and `ImageFormat::Jpeg` to select JPEG output.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Image to JPG using PHP" %}}
To convert an image to JPG, add it to a `Presentation`, place it on a slide, render the slide with `getImage`, and save the rendered image with `ImageFormat::Jpeg`.

{{% blocks/products/pf/agp/code-block title="PHP code for converting Image into JPG" offSpacer="true" %}}

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

    $slide->getShapes()->addPictureFrame(
        ShapeType::Rectangle, 0, 0, $imageWidth, $imageHeight, $embeddedImage);

    $slideImage = $slide->getImage(1.0, 1.0);
    try {
        $slideImage->save("output.jpg", ImageFormat::Jpeg);
    } finally {
        $slideImage->dispose();
    }
} finally {
    $presentation->dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert Image to JPG using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert Image to JPG in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation`, access its first slide, and load the source image with `Images::fromFile`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Add the image to the presentation, place it on the slide with `addPictureFrame`, render it with `getImage`, and save it with `ImageFormat::Jpeg`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert Image To Other Supported Formats" subTitle="You can also convert Image and save to other file formats. See all supported formats below:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/image-to-html/" name="IMAGE TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
