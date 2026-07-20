---
title: Merge PPS Files in PHP
url: /php-java/merger/pps/
keywords: Merge PPS, Join PPS, Combine PPS, PowerPoint, Presentation, PHP, Aspose
description: Merge multiple PPS presentations in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PPS Files in PHP" h2="Combine PPS presentations with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Merge PPS in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can combine multiple PPS presentations into one file. The API clones slides from each source presentation into a destination presentation while retaining their content and formatting.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge PPS files using PHP" %}}
To merge PPS presentations, load both files, clone each source slide into the destination presentation with `addClone`, and save the result in PPS format.

{{% blocks/products/pf/agp/code-block title="PHP code for merging multiple PPS files" offSpacer="true" %}}


```php
$destinationPresentation = new Presentation("document1.pps");
$sourcePresentation = new Presentation("document2.pps");
try {
    $slideCount = java_values($sourcePresentation->getSlides()->size());

    for ($slideIndex = 0; $slideIndex < $slideCount; $slideIndex++) {
        $slide = $sourcePresentation->getSlides()->get_Item($slideIndex);
        $destinationPresentation->getSlides()->addClone($slide);
    }

    $destinationPresentation->save("merged.pps", SaveFormat::Pps);
} finally {
    $sourcePresentation->dispose();
    $destinationPresentation->dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge PPS files in PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two PPS files and save the result as PPS in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install **Aspose.Slides for PHP via Java**. See [**Installation**](https://docs.aspose.com/slides/php-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source and destination PPS files with the `Presentation` class, then clone each source slide with `addClone`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with the output file path and `SaveFormat::Pps`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="pps" sectionTitle="Merge PPS Files Online" sectionDescription="Combine PPS presentations online with Aspose.Slides Merger." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge PPS with Other Supported Formats" subTitle="You can also combine PPS with presentations in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/fodp/" name="FODP" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
