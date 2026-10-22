---
lastmod: 2026-07-20
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit HTML in PHP
url: /php-java/editor/html/
keywords: Edit HTML, Edit PowerPoint, HTML, PowerPoint, PHP API, PHP Library
description: Import HTML, edit the generated presentation content, and export it to HTML5 in PHP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edit HTML in PHP" h2="Import HTML into slides, modify the presentation content, and export the result to HTML5 with Aspose.Slides for PHP via Java." related="FODP,ODP,OTP,PDF,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit HTML in PHP" variant="code" %}}

Using [**Aspose.Slides for PHP via Java**](/slides/php-java/), you can import HTML, add a text shape to the generated slide, and export the modified content to HTML5 with a few lines of PHP code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP code for editing HTML" >}}
```php
$presentation = new Presentation();
try {
    $presentation->getSlides()->removeAt(0);

    $htmlContent = file_get_contents("input.html");
    $presentation->getSlides()->addFromHtml($htmlContent);

    $slide = $presentation->getSlides()->get_Item(0);
    $shape = $slide->getShapes()->addAutoShape(
        ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $presentation->save("output.html", SaveFormat::Html5);
} finally {
    $presentation->dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit HTML using Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can import HTML content into presentation slides. You can then modify those slides by adding text, shapes, images, and other presentation elements before exporting the result to HTML5.

The export creates a new HTML5 document from the presentation; it does not modify the source HTML DOM in place. The following example imports an HTML file, adds a rectangle containing text to the first generated slide, and saves the result as HTML5.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to edit HTML in PHP" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for PHP via Java**. See [**Installation**](https://docs.aspose.com/slides/php-java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Configure Aspose.Slides in your PHP project.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Create a `Presentation` and remove its default slide with `removeAt(0)`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Read the HTML content with `file_get_contents` and import it with `addFromHtml`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Access the first generated slide, add a rectangle with `addAutoShape`, and set its text with `setText`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `save` with the output file path and `SaveFormat::Html5`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Edit Other Files" subTitle="You can also edit presentations in other supported formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/php-java/editor/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
