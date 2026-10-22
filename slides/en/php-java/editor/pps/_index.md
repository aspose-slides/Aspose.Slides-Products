---
lastmod: 2026-07-20
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit PPS in PHP
url: /php-java/editor/pps/
keywords: Edit PPS, Edit PowerPoint, PPS, PowerPoint, PHP API, PHP Library
description: Edit PPS presentations in PHP with Aspose.Slides for PHP via Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edit PPS in PHP" h2="Load, modify, and save PPS presentations with Aspose.Slides for PHP via Java." related="FODP,HTML,ODP,OTP,PDF,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PPS in PHP" variant="code" %}}

Using [**Aspose.Slides for PHP via Java**](/slides/php-java/), you can add a text shape to a PPS presentation with a few lines of PHP code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP code for editing PPS" >}}
```php
$presentation = new Presentation("input.pps");
try {
    $slide = $presentation->getSlides()->get_Item(0);
    $shape = $slide->getShapes()->addAutoShape(
        ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $presentation->save("output.pps", SaveFormat::Pps);
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PPS using Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can load, modify, and save PPS presentations. You can edit slide text, add shapes and images, update formatting, and work with other presentation elements through the API.

The following example loads a PPS presentation, adds a rectangle containing text to its first slide, and saves the modified presentation as a new PPS file.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to edit PPS in PHP" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for PHP via Java**. See [**Installation**](https://docs.aspose.com/slides/php-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure Aspose.Slides in your PHP project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPS file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access the first slide with `get_Item(0)`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Add a rectangle with `addAutoShape` and set its text with `setText`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with the output file path and `SaveFormat::Pps`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Edit Other Files" subTitle="You can also edit presentations in other supported formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
