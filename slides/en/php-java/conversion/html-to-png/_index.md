---
title: Convert HTML to PNG in PHP
url: /php-java/conversion/html-to-png/
keywords: HTML to PNG, Convert HTML to PNG, PHP API, PHP Library, HTML, PNG
description: Convert HTML content to PNG images in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert HTML to PNG in PHP" h2="Import HTML content into presentation slides and render each slide as a PNG image with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert HTML to PNG in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can import HTML content into presentation slides and render those slides as PNG images. The example below exports every generated slide to a separate PNG file.

Aspose.Slides provides a straightforward API for HTML-to-PNG conversion and can also export the imported content to PDF, PowerPoint, and other supported formats.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert HTML to PNG using PHP" %}}
To convert HTML content to PNG, create a `Presentation`, import the HTML with `addFromHtml`, and render each generated slide.

{{% blocks/products/pf/agp/code-block title="PHP code for converting HTML into PNG" offSpacer="true" %}}

```php
$presentation = new Presentation();
try {
    $slides = $presentation->getSlides();
    $slides->removeAt(0);

    $htmlContent = file_get_contents("input.html");
    $slides->addFromHtml($htmlContent);

    $slideCount = java_values($slides->size());
    for ($slideIndex = 0; $slideIndex < $slideCount; $slideIndex++) {
        $slide = $slides->get_Item($slideIndex);
        $slideImage = $slide->getImage(1, 1);

        try {
            $filePath = "slide_" . ($slideIndex + 1) . ".png";
            $slideImage->save($filePath, ImageFormat::Png);
        } finally {
            $slideImage->dispose();
        }
    }
} finally {
    $presentation->dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert HTML to PNG using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert HTML to PNG in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Read the HTML content with `file_get_contents` and pass it to `addFromHtml`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each slide with `getImage` and save it with `ImageFormat::Png`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert HTML To Other Supported Formats" subTitle="You can also convert HTML and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
