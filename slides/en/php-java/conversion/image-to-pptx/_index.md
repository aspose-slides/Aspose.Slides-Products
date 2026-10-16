---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert Image to PPTX in PHP
url: /php-java/conversion/image-to-pptx/
keywords: Image to PPTX, Convert Image to PPTX, PHP API, PHP Library, Image, PPTX
description: Convert an image to PowerPoint PPTX in PHP with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert Image to PPTX in PHP" h2="Place an image on a presentation slide and save the result as a PowerPoint PPTX file with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert Image to PPTX using PHP" variant="code" %}}

To convert an image to PPTX, create a `Presentation`, add the image with `addPictureFrame`, and call `save` with `SaveFormat::Pptx`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP code for converting Image into PPTX" >}}
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

    $presentation->save("output.pptx", SaveFormat::Pptx);
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert Image to PPTX in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you place an image on a presentation slide at its original dimensions and save the result as a PowerPoint Open XML file.

Aspose.Slides supports common raster and vector image formats and can save image-based slides as PPTX, PPT, PDF, HTML, and other supported formats.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert Image to PPTX using Aspose.Slides for PHP API" intro="These are the steps to convert Image to PPTX in PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure Aspose.Slides in your PHP project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source image with `Images::fromFile` and add it to the presentation image collection.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the image to the slide with `addPictureFrame`, then save with `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert Image To Other Supported Formats" subTitle="You can also convert Image and save to other file formats. See all supported formats below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
