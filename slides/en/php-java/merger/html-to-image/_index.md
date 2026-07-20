---
title: Merge HTML to Image in PHP
url: /php-java/merger/html-to-image/
keywords: Merge HTML to image, HTML to image, Join HTML, Combine HTML, Image, PHP API, PHP Library
description: Merge HTML files in PHP and render the combined presentation content as PNG images.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge HTML to Image in PHP" h2="Combine HTML content and render it as images with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Merge HTML to PNG using Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can import content from multiple HTML files into a `Presentation` and render the resulting slides as PNG images. Each generated slide is saved as a separate image so that all imported content is preserved.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Merge HTML to PNG in PHP" %}}
Using [**Aspose.Slides for PHP via Java**](/slides/php-java/), you can import two HTML files and render every resulting slide as a PNG image with a few lines of PHP code.

{{% blocks/products/pf/agp/code-block title="PHP code for merging HTML to PNG" offSpacer="true" %}}
```php
$presentation = new Presentation();
try {
    $presentation->getSlides()->removeAt(0);

    $firstHtmlContent = file_get_contents("file1.html");
    $presentation->getSlides()->addFromHtml($firstHtmlContent);

    $secondHtmlContent = file_get_contents("file2.html");
    $presentation->getSlides()->addFromHtml($secondHtmlContent);

    $slideCount = java_values($presentation->getSlides()->size());
    for ($slideIndex = 0; $slideIndex < $slideCount; $slideIndex++) {
        $slide = $presentation->getSlides()->get_Item($slideIndex);
        $slideImage = $slide->getImage(1.0, 1.0);

        try {
            $filePath = "merged-slide-" . ($slideIndex + 1) . ".png";
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




{{< blocks/products/pf/feature-page-section  h2="How to merge HTML to image in PHP" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


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
Read the HTML files with `file_get_contents` and import their content with `addFromHtml`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Render each slide with `getImage` and save it with `ImageFormat::Png`.
{{% /blocks/products/pf/agp/step-autogen %}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="html-to-image" sectionTitle="Merge Files Online" sectionDescription="Combine presentations and slides online with Aspose.Slides Merger." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge Other Files" subTitle="You can also combine files in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/html-to-html/" name="HTML TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}}




{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
