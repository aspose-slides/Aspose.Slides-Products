---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge Images in PHP
url: /php-java/merger/image-to-image/
keywords: Merge image, image to image, Join images, Combine images, PHP API, PHP Library
description: Merge multiple images into a single PNG image in PHP with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Merge Images in PHP" h2="Arrange multiple images on a slide and render them as a single PNG image with Aspose.Slides for PHP via Java." related="JPG,HTML,IMAGE,PDF,PNG,SVG,BMP" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge Images in PHP" variant="code" %}}

Load the source files with `Images::fromFile`, add them to the slide with `addPictureFrame`, render the slide with `getImage`, and save the result with `ImageFormat::Png`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP code for merging images" >}}
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
        $slideImage->save("merged-image.png", ImageFormat::Png);
    } finally {
        $slideImage->dispose();
    }
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge Images using Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you place images in a custom layout on a presentation slide and render the composed slide as a single image. The example below combines two source images side by side and saves the result as PNG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to merge images in PHP" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for PHP via Java**. See [**Installation**](https://docs.aspose.com/slides/php-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure Aspose.Slides in your PHP project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and access its first slide through a variable.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source images with `Images::fromFile` and place them on the slide with `addPictureFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render the slide with `getImage` and save the result with `ImageFormat::Png`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Merge Other Files" subTitle="You can also combine files in other supported formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
