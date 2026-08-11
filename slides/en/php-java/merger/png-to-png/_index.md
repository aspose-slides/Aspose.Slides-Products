---
lastmod: 2026-07-20
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge PNG Images in PHP
url: /php-java/merger/png-to-png/
keywords: Merge PNG, PNG to PNG, Join PNG, Combine PNG, PHP API, PHP Library
description: Merge multiple PNG images into a single PNG image in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PNG Images in PHP" h2="Arrange multiple PNG images on a slide and render them as one PNG image with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Merge PNG to PNG using Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you place multiple PNG images in a custom layout on a presentation slide and render the composed slide as a single PNG image.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge PNG to PNG in PHP" %}}
Load the source files with `Images::fromFile`, add them to the slide with `addPictureFrame`, render the slide with `getImage`, and save the result with `ImageFormat::Png`.

{{% blocks/products/pf/agp/code-block title="PHP code for merging PNG to PNG" offSpacer="true" %}}
```php
$presentation = new Presentation();
try {
    $slide = $presentation->getSlides()->get_Item(0);

    $firstSourceImage = Images::fromFile("image1.png");
    try {
        $firstPresentationImage = $presentation->getImages()->addImage($firstSourceImage);
    } finally {
        $firstSourceImage->dispose();
    }

    $secondSourceImage = Images::fromFile("image2.png");
    try {
        $secondPresentationImage = $presentation->getImages()->addImage($secondSourceImage);
    } finally {
        $secondSourceImage->dispose();
    }

    $slide->getShapes()->addPictureFrame(
        ShapeType::Rectangle, 0, 0, 360, 540, $firstPresentationImage);
    $slide->getShapes()->addPictureFrame(
        ShapeType::Rectangle, 360, 0, 360, 540, $secondPresentationImage);

    $slideImage = $slide->getImage(1.0, 1.0);
    try {
        $slideImage->save("merged-image.png", ImageFormat::Png);
    } finally {
        $slideImage->dispose();
    }
} finally {
    $presentation->dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge PNG images in PHP" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge multiple PNG images into one PNG image in PHP." >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install **Aspose.Slides for PHP via Java**. See [**Installation**](https://docs.aspose.com/slides/php-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` instance and access its first slide through a variable.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PNG images with `Images::fromFile` and place them on the slide with `addPictureFrame`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render the slide with `getImage` and save it with `ImageFormat::Png`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="png-to-png" sectionTitle="Merge PNG Images Online" sectionDescription="Combine PNG images online with Aspose.Slides Merger." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge Other Files" subTitle="You can also combine files in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
