---
title: Merge Images to PDF in PHP
url: /php-java/merger/image-to-pdf/
keywords: Image to PDF, Merge Image to PDF, Join Image to PDF, PDF, Image, PHP API, PHP Library
description: Merge multiple images into a single PDF document in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge Images to PDF in PHP" h2="Place multiple images on separate slides and export them as a single PDF document with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Merge Images to PDF using Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you place each source image on a separate presentation slide and export all the slides as a single multi-page PDF document.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge Images to PDF in PHP" %}}
Load each source file with `Images::fromFile`, add a slide with `addEmptySlide`, place the image with `addPictureFrame`, and call `save` with `SaveFormat::Pdf`.

{{% blocks/products/pf/agp/code-block title="PHP code for merging images into PDF" offSpacer="true" %}}
```php
$presentation = new Presentation();
try {
    $presentation->getSlides()->removeAt(0);
    $layoutSlide = $presentation->getLayoutSlides()->get_Item(0);

    $imagePaths = ["image1.png", "image2.jpg"];
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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge images to PDF in PHP" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install **Aspose.Slides for PHP via Java**. See [**Installation**](https://docs.aspose.com/slides/php-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation`, remove its default slide, and access a layout slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load each source image with `Images::fromFile`, add an empty slide with `addEmptySlide`, and place the image with `addPictureFrame`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Save the presentation with `SaveFormat::Pdf`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="image-to-pdf" sectionTitle="Merge Images Online" sectionDescription="[Try the free Aspose.Slides Merger](https://products.aspose.app/slides/merger)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge Other Files" subTitle="You can also combine files in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
