---
title: Convert PDF to JPG in PHP
url: /php-java/conversion/pdf-to-jpg/
keywords: PDF to JPG, Convert PDF to JPG, PHP API, PHP Library, PDF, JPG
description: Convert PDF pages to JPG images in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PDF to JPG in PHP" h2="Import PDF pages and render them as JPG images with Aspose.Slides for PHP via Java" >}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to JPG in PHP" %}}

Use [**Aspose.Slides for PHP via Java**](/slides/php-java/) to import the pages of a PDF document as slides and render each slide as a JPG image.

Call `addFromPdf` to import the PDF pages, then call `getImage` for each slide and save the result with `ImageFormat::Jpeg`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to JPG using PHP" %}}
Create a `Presentation`, remove its default slide, import the PDF pages, and save a JPG image for each imported slide.

{{% blocks/products/pf/agp/code-block title="PHP code for converting PDF into JPG" offSpacer="true" %}}

```php
$presentation = new Presentation();
try {
    $presentation->getSlides()->removeAt(0);
    $presentation->getSlides()->addFromPdf("document.pdf");

    $slideCount = java_values($presentation->getSlides()->size());
    for ($slideIndex = 0; $slideIndex < $slideCount; $slideIndex++) {
        $slide = $presentation->getSlides()->get_Item($slideIndex);
        $slideImage = $slide->getImage(2.0, 2.0);

        try {
            $filePath = "slide_" . ($slideIndex + 1) . ".jpg";
            $slideImage->save($filePath, ImageFormat::Jpeg);
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

{{< blocks/products/pf/feature-page-section  h2="How to convert PDF to JPG using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PDF to JPG in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for PHP via Java**](/slides/php-java/) with Composer.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and remove its default slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the PDF pages with `addFromPdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Access each slide through a variable, call `getImage`, and save the rendered image with `ImageFormat::Jpeg`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online PDF Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PDF To Other Supported Formats" subTitle="You can also convert PDF and save to other file formats. See all supported formats below:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/pdf-to-xml/" name="PDF TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
