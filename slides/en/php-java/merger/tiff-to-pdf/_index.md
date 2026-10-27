---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge TIFF Images to PDF in PHP
url: /php-java/merger/tiff-to-pdf/
keywords: TIFF to PDF, Merge TIFF to PDF, Join TIFF to PDF, PDF, TIFF, PHP API, PHP Library
description: Merge multiple TIFF images into a single PDF document in PHP with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Merge TIFF Images to PDF in PHP" h2="Place multiple TIFF images on separate slides and export them as a single PDF document with Aspose.Slides for PHP via Java." related="JPG,PNG,HTML,IMAGE,PDF,SVG,BMP" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge TIFF to PDF in PHP" variant="code" %}}

Load each TIFF file with `Images::fromFile`, add a slide with `addEmptySlide`, place the image with `addPictureFrame`, and call `save` with `SaveFormat::Pdf`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP code for merging TIFF images into PDF" >}}
```php
$presentation = new Presentation();
try {
    $presentation->getSlides()->removeAt(0);
    $layoutSlide = $presentation->getLayoutSlides()->get_Item(0);

    $imagePaths = ["image1.tiff", "image2.tiff"];
    foreach ($imagePaths as $imagePath) {
        $slide = $presentation->getSlides()->addEmptySlide($layoutSlide);

        $sourceImage = Images::fromFile($imagePath);
        try {
            $presentationImage = $presentation->getImages()->addImage($sourceImage);
        } finally {
            $sourceImage->dispose();
        }

        $slide->getShapes()->addPictureFrame(
            ShapeType::Rectangle, 0, 0, 720, 540, $presentationImage);
    }

    $presentation->save("merged-images.pdf", SaveFormat::Pdf);
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge TIFF to PDF using Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you place each TIFF image on a separate presentation slide and export all the slides as a single multi-page PDF document.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to merge TIFF images to PDF in PHP" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for PHP via Java**. See [**Installation**](https://docs.aspose.com/slides/php-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure Aspose.Slides in your PHP project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation`, remove its default slide, and access a layout slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load each TIFF file with `Images::fromFile`, add an empty slide with `addEmptySlide`, and place the image with `addPictureFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the presentation with `SaveFormat::Pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Merge Other Files" subTitle="You can also combine files in other supported formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
