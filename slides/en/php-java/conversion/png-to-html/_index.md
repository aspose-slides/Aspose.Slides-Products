---
title: Convert PNG to HTML in PHP
url: /php-java/conversion/png-to-html/
keywords: PNG to HTML, Convert PNG to HTML, PHP API, PHP Library, PNG, HTML
description: Place a PNG image on a presentation slide and export it as HTML in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PNG to HTML in PHP" h2="Place a PNG image on a presentation slide and export the presentation as HTML with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PNG to HTML in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) lets you place a PNG image on a presentation slide at its original dimensions and export the result as HTML.

The PNG is embedded in the presentation, and the slide is exported with `SaveFormat::Html5`. The same workflow can be adapted to other supported image and presentation formats.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PNG to HTML using PHP" %}}
Create a `Presentation`, load the PNG with `Images::fromFile`, add it to the first slide with `addPictureFrame`, and call `save` with `SaveFormat::Html5`.

{{% blocks/products/pf/agp/code-block title="PHP code for converting PNG into HTML" offSpacer="true" %}}

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

    $presentation->save("output.html", SaveFormat::Html5);
} finally {
    $presentation->dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PNG to HTML using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PNG to HTML in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and access its first slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the PNG with `Images::fromFile` and add it to the presentation image collection.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Add the image to the slide with `addPictureFrame`, then save with `SaveFormat::Html5`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PNG To Other Supported Formats" subTitle="You can also convert PNG and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
