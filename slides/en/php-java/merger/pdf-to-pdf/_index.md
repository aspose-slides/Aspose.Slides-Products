---
title: Merge PDF Files in PHP
url: /php-java/merger/pdf-to-pdf/
keywords: Merge PDF, PDF to PDF, Join PDF, Combine PDF, PHP API, PHP Library
description: Merge multiple PDF files into one PDF in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PDF Files in PHP" h2="Combine multiple PDF documents with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Merge PDF to PDF using Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can import pages from multiple PDF documents into a single `Presentation` and export the combined slides as one PDF file.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge PDF to PDF in PHP" %}}
Create a `Presentation`, remove its default slide, import each PDF with `addFromPdf`, and save the combined content with `SaveFormat::Pdf`.

{{% blocks/products/pf/agp/code-block title="PHP code for merging PDF to PDF" offSpacer="true" %}}
```php
$presentation = new Presentation();
try {
    $presentation->getSlides()->removeAt(0);

    $presentation->getSlides()->addFromPdf("document1.pdf");
    $presentation->getSlides()->addFromPdf("document2.pdf");

    $presentation->save("merged.pdf", SaveFormat::Pdf);
} finally {
    $presentation->dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to merge PDF files in PHP" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge multiple PDF files into one PDF in PHP." >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install **Aspose.Slides for PHP via Java**. See [**Installation**](https://docs.aspose.com/slides/php-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` instance and remove its default slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import each PDF file with `addFromPdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with the output file path and `SaveFormat::Pdf`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="pdf-to-pdf" sectionTitle="Merge PDF Files Online" sectionDescription="Combine PDF documents online with Aspose.Slides Merger." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge Other Files" subTitle="You can also combine files in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/png-to-png/" name="PNG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
