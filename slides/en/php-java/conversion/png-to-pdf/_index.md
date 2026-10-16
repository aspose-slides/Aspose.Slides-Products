---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert PNG to PDF in PHP
url: /php-java/conversion/png-to-pdf/
keywords: PNG to PDF, Convert PNG to PDF, PHP API, PHP Library, PNG, PDF
description: Place a PNG image on a presentation slide and export it as PDF in PHP with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert PNG to PDF in PHP" h2="Place a PNG image on a presentation slide and export the result as PDF with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to PDF using PHP" variant="code" %}}

Create a `Presentation`, load the PNG with `Images::fromFile`, match the slide size to the image with `setSize`, add the image with `addPictureFrame`, and call `save` with `SaveFormat::Pdf`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP code for converting PNG into PDF" >}}
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

    $presentation->getSlideSize()->setSize(
        $imageWidth, $imageHeight, SlideSizeScaleType::DoNotScale);

    $slide->getShapes()->addPictureFrame(
        ShapeType::Rectangle, 0, 0, $imageWidth, $imageHeight, $embeddedImage);

    $presentation->save("output.pdf", SaveFormat::Pdf);
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert PNG to PDF in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you place a PNG image on a presentation slide at its original dimensions and export the result as a PDF document.

The PNG remains embedded as an image on the slide, while `SaveFormat::Pdf` exports the complete presentation to PDF.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert PNG to PDF using Aspose.Slides for PHP API" intro="These are the steps to convert PNG to PDF in PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation`, access its first slide, and load the PNG with `Images::fromFile`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Set the slide dimensions with `setSize`, then place the image on the slide with `addPictureFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with the output file path and `SaveFormat::Pdf`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert PNG To Other Supported Formats" subTitle="You can also convert PNG and save to other file formats. See all supported formats below:" >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
