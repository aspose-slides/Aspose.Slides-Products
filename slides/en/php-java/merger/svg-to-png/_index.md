---
lastmod: 2026-07-20
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge SVG Files into PNG in PHP
url: /php-java/merger/svg-to-png/
keywords: Merge SVG to PNG, SVG to PNG, Join SVG to PNG, Combine SVG to PNG, PHP API, PHP Library
description: Merge multiple SVG images into a single PNG image in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge SVG Files into PNG in PHP" h2="Arrange multiple SVG images on a slide and render them as a single PNG image with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Merge SVG to PNG using Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you place multiple SVG images in a custom layout on a presentation slide and render the composed slide as a single PNG image.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge SVG to PNG in PHP" %}}
Load each SVG file into an `SvgImage`, add the images to a slide with `addPictureFrame`, render the slide with `getImage`, and save the result with `ImageFormat::Png`.

{{% blocks/products/pf/agp/code-block title="PHP code for merging SVG to PNG" offSpacer="true" %}}
```php
$presentation = new Presentation();
try {
    $slide = $presentation->getSlides()->get_Item(0);

    $firstSvgContent = file_get_contents("image1.svg");
    $firstSvgImage = new SvgImage($firstSvgContent);
    $firstPresentationImage = $presentation->getImages()->addImage($firstSvgImage);

    $secondSvgContent = file_get_contents("image2.svg");
    $secondSvgImage = new SvgImage($secondSvgContent);
    $secondPresentationImage = $presentation->getImages()->addImage($secondSvgImage);

    $firstImageWidth = java_values($firstPresentationImage->getWidth());
    $firstImageHeight = java_values($firstPresentationImage->getHeight());
    $secondImageWidth = java_values($secondPresentationImage->getWidth());
    $secondImageHeight = java_values($secondPresentationImage->getHeight());

    $slideWidth = $firstImageWidth + $secondImageWidth;
    $slideHeight = max($firstImageHeight, $secondImageHeight);

    $presentation->getSlideSize()->setSize(
        $slideWidth, $slideHeight, SlideSizeScaleType::DoNotScale);

    $slide->getShapes()->addPictureFrame(
        ShapeType::Rectangle, 0, 0, $firstImageWidth, $firstImageHeight, $firstPresentationImage);

    $slide->getShapes()->addPictureFrame(
        ShapeType::Rectangle, $firstImageWidth, 0, $secondImageWidth, $secondImageHeight, $secondPresentationImage);

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




{{< blocks/products/pf/feature-page-section  h2="How to merge SVG to PNG in PHP" >}}


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
Load each SVG file into an `SvgImage` and place it on the slide with `addPictureFrame`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render the slide with `getImage` and save the result with `ImageFormat::Png`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="svg-to-png" sectionTitle="Merge SVG Files Online" sectionDescription="Combine SVG images online with Aspose.Slides Merger." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge Other Files" subTitle="You can also combine files in other supported formats." >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
