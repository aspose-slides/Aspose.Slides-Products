---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge SVG Files into PNG in PHP
url: /php-java/merger/svg-to-png/
keywords: Merge SVG to PNG, SVG to PNG, Join SVG to PNG, Combine SVG to PNG, PHP API, PHP Library
description: Merge multiple SVG images into a single PNG image in PHP with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Merge SVG Files into PNG in PHP" h2="Arrange multiple SVG images on a slide and render them as a single PNG image with Aspose.Slides for PHP via Java." related="JPG,PNG,HTML,IMAGE,PDF,BMP" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge SVG to PNG in PHP" variant="code" %}}

Load each SVG file into an `SvgImage`, add the images to a slide with `addPictureFrame`, render the slide with `getImage`, and save the result with `ImageFormat::Png`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP code for merging SVG to PNG" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge SVG to PNG using Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you place multiple SVG images in a custom layout on a presentation slide and render the composed slide as a single PNG image.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to merge SVG to PNG in PHP" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for PHP via Java**. See [**Installation**](https://docs.aspose.com/slides/php-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure Aspose.Slides in your PHP project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and access its first slide through a variable.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load each SVG file into an `SvgImage` and place it on the slide with `addPictureFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render the slide with `getImage` and save the result with `ImageFormat::Png`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Merge Other Files" subTitle="You can also combine files in other supported formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
