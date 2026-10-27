---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert SVG to PPT in PHP
url: /php-java/conversion/svg-to-ppt/
keywords: SVG to PPT, Convert SVG to PPT, PHP API, PHP Library, SVG, PPT
description: Convert SVG files to PowerPoint PPT presentations in PHP with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert SVG to PPT in PHP" h2="Add an SVG image to a slide and save the presentation as a PowerPoint PPT file with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert SVG to PPT using PHP" variant="code" %}}

To convert SVG to PPT, create a `Presentation`, add the SVG image to its first slide, and call `save` with `SaveFormat::Ppt`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP code for converting SVG into PPT" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert SVG to PPT in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can add an SVG image to a presentation slide and save the result as a PowerPoint PPT file with a few lines of PHP code.

Load the SVG content into a `SvgImage`, add it to the presentation image collection with `addImage`, place it on a slide with `addPictureFrame`, and save the presentation with `SaveFormat::Ppt`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert SVG to PPT using Aspose.Slides for PHP API" intro="These are the steps to convert SVG to PPT in PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure Aspose.Slides in your PHP project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation`, access its first slide, and load the SVG content into a `SvgImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the SVG image with `addPictureFrame`, then call `save` with `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert SVG to Other Supported Formats" subTitle="You can also convert SVG files and save them to other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
