---
lastmod: 2026-07-20
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert SVG to PPTX in PHP
url: /php-java/conversion/svg-to-pptx/
keywords: SVG to PPTX, Convert SVG to PPTX, PHP API, PHP Library, SVG, PPTX
description: Convert SVG files to PowerPoint PPTX presentations in PHP with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert SVG to PPTX in PHP" h2="Add an SVG image to a slide and save the presentation as a PowerPoint PPTX file with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert SVG to PPTX using PHP" variant="code" %}}

To convert SVG to PPTX, create a `Presentation`, add the SVG image to its first slide, and call `save` with `SaveFormat::Pptx`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP code for converting SVG into PPTX" >}}
```php
$presentation = new Presentation();
try {
    $slide = $presentation->getSlides()->get_Item(0);

    $svgContent = file_get_contents("image.svg");
    $svgImage = new SvgImage($svgContent);
    $presentationImage = $presentation->getImages()->addImage($svgImage);

    $slide->getShapes()->addPictureFrame(
        ShapeType::Rectangle, 10, 10, 100, 100, $presentationImage);

    $presentation->save("output.pptx", SaveFormat::Pptx);
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert SVG to PPTX in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can add an SVG image to a presentation slide and save the result as a PowerPoint PPTX file with a few lines of PHP code.

Load the SVG content into a `SvgImage`, add it to the presentation image collection with `addImage`, place it on a slide with `addPictureFrame`, and save the presentation with `SaveFormat::Pptx`.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to convert SVG to PPTX using Aspose.Slides for PHP API" intro="These are the steps to convert SVG to PPTX in PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure Aspose.Slides in your PHP project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation`, access its first slide, and load the SVG content into a `SvgImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add the SVG image with `addPictureFrame`, then call `save` with `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free Online Converter"
  description="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Convert SVG to Other Supported Formats" subTitle="You can also convert SVG files and save them to other supported formats." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
