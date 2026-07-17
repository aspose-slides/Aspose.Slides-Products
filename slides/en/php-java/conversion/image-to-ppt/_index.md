---
title: Convert Image to PPT in PHP
url: /php-java/conversion/image-to-ppt/
keywords: Image to PPT, Convert Image to PPT, PHP API, PHP Library, Image, PPT
description: Convert an image to PowerPoint PPT in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert Image to PPT in PHP" h2="Place an image on a presentation slide and save the result as a PowerPoint PPT file with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert Image to PPT in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you place an image on a presentation slide at its original dimensions and save the result as a PowerPoint 97–2003 PPT file.

Aspose.Slides supports common raster and vector image formats and can save image-based slides as PPT, PPTX, PDF, HTML, and other supported formats.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Image to PPT using PHP" %}}
To convert an image to PPT, create a `Presentation`, add the image with `addPictureFrame`, and call `save` with `SaveFormat::Ppt`.

{{% blocks/products/pf/agp/code-block title="PHP code for converting Image into PPT" offSpacer="true" %}}

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

    $presentation->save("output.ppt", SaveFormat::Ppt);
} finally {
    $presentation->dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert Image to PPT using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert Image to PPT in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source image with `Images::fromFile` and add it to the presentation image collection.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Add the image to the slide with `addPictureFrame`, then save with `SaveFormat::Ppt`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert Image To Other Supported Formats" subTitle="You can also convert Image and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/image-to-html/" name="IMAGE TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
