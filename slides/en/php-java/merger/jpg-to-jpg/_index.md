---
lastmod: 2026-07-20
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge JPG Images in PHP
url: /php-java/merger/jpg-to-jpg/
keywords: Merge JPG, JPG to JPG, Join JPG, Combine JPG, PHP API, PHP Library
description: Merge multiple JPG images into a single JPEG file in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge JPG Images in PHP" h2="Arrange multiple JPG images on a slide and render them as a single JPEG file with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Merge JPG Images using Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you arrange multiple JPG images on a presentation slide and render the composed slide as a single JPEG file. The example below places two JPG images side by side.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge JPG Images in PHP" %}}
Load the JPG files with `Images::fromFile`, add them to the slide with `addPictureFrame`, render the slide with `getImage`, and save the result with `ImageFormat::Jpeg`.

{{% blocks/products/pf/agp/code-block title="PHP code for merging JPG images" offSpacer="true" %}}
```php
$presentation = new Presentation();
try {
    $slide = $presentation->getSlides()->get_Item(0);

    $firstSourceImage = Images::fromFile("image1.jpg");
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
        $slideImage->save("merged-image.jpg", ImageFormat::Jpeg);
    } finally {
        $slideImage->dispose();
    }
} finally {
    $presentation->dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge JPG images in PHP" >}}


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
Load the JPG files with `Images::fromFile` and place them on the slide with `addPictureFrame`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render the slide with `getImage` and save the result with `ImageFormat::Jpeg`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="jpg-to-jpg" sectionTitle="Merge JPG Images Online" sectionDescription="[Try the free Aspose.Slides Merger](https://products.aspose.app/slides/merger)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge Other Files" subTitle="You can also combine files in other supported formats." >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
