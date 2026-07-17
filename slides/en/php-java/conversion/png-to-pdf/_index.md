---
title: Convert PNG to PDF in PHP
url: /php-java/conversion/png-to-pdf/
keywords: PNG to PDF, Convert PNG to PDF, PHP API, PHP Library, PNG, PDF
description: Place a PNG image on a presentation slide and export it as PDF in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PNG to PDF in PHP" h2="Place a PNG image on a presentation slide and export the result as PDF with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PNG to PDF in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you place a PNG image on a presentation slide at its original dimensions and export the result as a PDF document.

The PNG remains embedded as an image on the slide, while `SaveFormat::Pdf` exports the complete presentation to PDF.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PNG to PDF using PHP" %}}
Create a `Presentation`, load the PNG with `Images::fromFile`, match the slide size to the image with `setSize`, add the image with `addPictureFrame`, and call `save` with `SaveFormat::Pdf`.

{{% blocks/products/pf/agp/code-block title="PHP code for converting PNG into PDF" offSpacer="true" %}}

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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PNG to PDF using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PNG to PDF in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation`, access its first slide, and load the PNG with `Images::fromFile`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Set the slide dimensions with `setSize`, then place the image on the slide with `addPictureFrame`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with the output file path and `SaveFormat::Pdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PNG To Other Supported Formats" subTitle="You can also convert PNG and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-html/" name="PNG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
