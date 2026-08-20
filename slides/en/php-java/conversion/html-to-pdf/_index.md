---
lastmod: 2026-07-31
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert HTML to PDF in PHP
url: /php-java/conversion/html-to-pdf/
keywords: HTML to PDF, Convert HTML to PDF, PHP API, PHP Library, HTML, PDF
description: Convert HTML content to PDF in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert HTML to PDF in PHP" h2="Import HTML content into presentation slides and export the result to PDF with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert HTML to PDF in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can import HTML content into presentation slides and export the resulting presentation as a PDF document with a few lines of PHP code.

Aspose.Slides provides a straightforward API for HTML-to-PDF conversion and can also export the imported content to PowerPoint, images, and other supported formats.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert HTML to PDF using PHP" %}}
To convert HTML content to PDF, create a `Presentation`, import the HTML with `addFromHtml`, and call `save` with `SaveFormat::Pdf`.

{{% blocks/products/pf/agp/code-block title="PHP code for converting HTML into PDF" offSpacer="true" %}}

```php
$presentation = new Presentation();
try {
    $slides = $presentation->getSlides();
    $slides->removeAt(0);

    $htmlContent = file_get_contents("input.html");
    $slides->addFromHtml($htmlContent);

    $presentation->save("output.pdf", SaveFormat::Pdf);
} finally {
    $presentation->dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert HTML to PDF using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert HTML to PDF in PHP." >}}

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
Call `save` with the output file path and `SaveFormat::Pdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert HTML To Other Supported Formats" subTitle="You can also convert HTML and save to other file formats. See all supported formats below:" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
