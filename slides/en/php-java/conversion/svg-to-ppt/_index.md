---
lastmod: 2026-07-20
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert SVG to PPT in PHP
url: /php-java/conversion/svg-to-ppt/
keywords: SVG to PPT, Convert SVG to PPT, PHP API, PHP Library, SVG, PPT
description: Convert SVG files to PowerPoint PPT presentations in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert SVG to PPT in PHP" h2="Add an SVG image to a slide and save the presentation as a PowerPoint PPT file with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert SVG to PPT in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can add an SVG image to a presentation slide and save the result as a PowerPoint PPT file with a few lines of PHP code.

Load the SVG content into a `SvgImage`, add it to the presentation image collection with `addImage`, place it on a slide with `addPictureFrame`, and save the presentation with `SaveFormat::Ppt`.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert SVG to PPT using PHP" %}}
To convert SVG to PPT, create a `Presentation`, add the SVG image to its first slide, and call `save` with `SaveFormat::Ppt`.

{{% blocks/products/pf/agp/code-block title="PHP code for converting SVG into PPT" offSpacer="true" %}}

```php
$presentation = new Presentation();
try {
    $slide = $presentation->getSlides()->get_Item(0);

    $svgContent = file_get_contents("image.svg");
    $svgImage = new SvgImage($svgContent);
    $presentationImage = $presentation->getImages()->addImage($svgImage);

    $slide->getShapes()->addPictureFrame(
        ShapeType::Rectangle, 10, 10, 100, 100, $presentationImage);

    $presentation->save("output.ppt", SaveFormat::Ppt);
} finally {
    $presentation->dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert SVG to PPT using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert SVG to PPT in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation`, access its first slide, and load the SVG content into a `SvgImage`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Add the SVG image with `addPictureFrame`, then call `save` with `SaveFormat::Ppt`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert SVG to Other Supported Formats" subTitle="You can also convert SVG files and save them to other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/svg-to-pptx/" name="SVG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
