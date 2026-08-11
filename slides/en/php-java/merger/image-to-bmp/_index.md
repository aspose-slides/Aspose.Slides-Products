---
lastmod: 2026-07-20
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge Images to BMP in PHP
url: /php-java/merger/image-to-bmp/
keywords: Image to BMP, Merge image to BMP, Join image to BMP, Combine images, Image, BMP, PHP API, PHP Library
description: Merge multiple images into a single BMP file in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge Images to BMP in PHP" h2="Arrange multiple images on a slide and render them as a single BMP file with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Merge Images to BMP using Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you place multiple images on one presentation slide and render the composed slide as a single BMP file. The example below arranges two images side by side, but you can use the same approach for other layouts.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge Images to BMP in PHP" %}}
Load the source files with `Images::fromFile`, add them to the slide with `addPictureFrame`, render the slide with `getImage`, and save the result with `ImageFormat::Bmp`.

{{% blocks/products/pf/agp/code-block title="PHP code for merging images into BMP" offSpacer="true" %}}
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

    $secondSourceImage = Images::fromFile("image2.jpg");
    try {
        $secondPresentationImage = $presentation->getImages()->addImage($secondSourceImage);
    } finally {
        $secondSourceImage->dispose();
    }

    $slide->getShapes()->addPictureFrame(
        ShapeType::Rectangle, 0, 0, 360, 270, $firstPresentationImage);
    $slide->getShapes()->addPictureFrame(
        ShapeType::Rectangle, 360, 0, 360, 270, $secondPresentationImage);

    $slideImage = $slide->getImage(1.0, 1.0);
    try {
        $slideImage->save("merged-image.bmp", ImageFormat::Bmp);
    } finally {
        $slideImage->dispose();
    }
} finally {
    $presentation->dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge images to BMP in PHP" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install **Aspose.Slides for PHP via Java**. See [**Installation**](https://docs.aspose.com/slides/php-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and access its first slide through a variable.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source images with `Images::fromFile` and place them on the slide with `addPictureFrame`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render the slide with `getImage` and save the result with `ImageFormat::Bmp`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="image-to-bmp" sectionTitle="Merge Images Online" sectionDescription="[Try the free Aspose.Slides Merger](https://products.aspose.app/slides/merger)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge Other Files" subTitle="You can also combine files in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
