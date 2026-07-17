---
title: Convert HTML to TIFF in PHP
url: /php-java/conversion/html-to-tiff/
keywords: HTML to TIFF, Convert HTML to TIFF, PHP API, PHP Library, HTML, TIFF
description: Convert HTML content to multipage TIFF in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert HTML to TIFF in PHP" h2="Import HTML content into presentation slides and export the result as a multipage TIFF image with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert HTML to TIFF in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can import HTML content into presentation slides and export the resulting presentation as a multipage TIFF image with a few lines of PHP code.

Aspose.Slides provides a straightforward API for HTML-to-TIFF conversion and can also export the imported content to PowerPoint, PDF, and other supported formats.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert HTML to TIFF using PHP" %}}
To convert HTML content to TIFF, create a `Presentation`, import the HTML with `addFromHtml`, and call `save` with `SaveFormat::Tiff`.

{{% blocks/products/pf/agp/code-block title="PHP code for converting HTML into TIFF" offSpacer="true" %}}

```php
$presentation = new Presentation();
try {
    $slides = $presentation->getSlides();
    $slides->removeAt(0);

    $htmlContent = file_get_contents("input.html");
    $slides->addFromHtml($htmlContent);

    $presentation->save("output.tiff", SaveFormat::Tiff);
} finally {
    $presentation->dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert HTML to TIFF using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert HTML to TIFF in PHP." >}}

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
Call `save` with the output file path and `SaveFormat::Tiff`.
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
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
