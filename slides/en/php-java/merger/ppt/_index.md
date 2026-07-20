---
title: Merge PPT Files in PHP
url: /php-java/merger/ppt/
keywords: Merge PPT, Join PPT, Combine PPT, PowerPoint, Presentation, PHP, Aspose
description: Merge multiple PPT presentations in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Merge PPT Files in PHP" h2="Combine PPT presentations with Aspose.Slides for PHP via Java without requiring Microsoft PowerPoint." >}}

{{% blocks/products/pf/feature-page-section h2="Merge PPT in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can combine multiple PPT presentations into one file. The API clones slides from each source presentation into a destination presentation while retaining their content and formatting.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Merge PPT files using PHP" %}}
To merge PPT presentations, load both files, clone each source slide into the destination presentation, and save the result in PPT format.

{{% blocks/products/pf/agp/code-block title="PHP code for merging multiple PPT files" offSpacer="true" %}}


```php
$destinationPresentation = new Presentation("document1.ppt");
$sourcePresentation = new Presentation("document2.ppt");
try {
    $slideCount = java_values($sourcePresentation->getSlides()->size());

    for ($slideIndex = 0; $slideIndex < $slideCount; $slideIndex++) {
        $slide = $sourcePresentation->getSlides()->get_Item($slideIndex);
        $destinationPresentation->getSlides()->addClone($slide);
    }

    $destinationPresentation->save("merged.ppt", SaveFormat::Ppt);
} finally {
    $sourcePresentation->dispose();
    $destinationPresentation->dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to merge PPT files in PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Follow these steps to merge two PPT files and save the result as PPT in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install **Aspose.Slides for PHP via Java**. See [**Installation**](https://docs.aspose.com/slides/php-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Load the source and destination PPT files with the `Presentation` class, then clone each source slide with `addClone`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with the output file path and `SaveFormat::Ppt`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="ppt" sectionTitle="Merge PPT Files Online" sectionDescription="Combine PPT presentations online with Aspose.Slides Merger." >}}

{{< blocks/products/pf/agp/other-supported-section title="Merge PPT with Other Supported Formats" subTitle="You can also combine PPT with presentations in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/merger/fodp/" name="FODP" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
