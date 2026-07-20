---
title: Edit HTML in PHP
url: /php-java/editor/html/
keywords: Edit HTML, Edit PowerPoint, HTML, PowerPoint, PHP API, PHP Library
description: Import HTML, edit the generated presentation content, and export it to HTML5 in PHP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit HTML in PHP" h2="Import HTML into slides, modify the presentation content, and export the result to HTML5 with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Edit HTML using Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can import HTML content into presentation slides. You can then modify those slides by adding text, shapes, images, and other presentation elements before exporting the result to HTML5.

The export creates a new HTML5 document from the presentation; it does not modify the source HTML DOM in place. The following example imports an HTML file, adds a rectangle containing text to the first generated slide, and saves the result as HTML5.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Edit HTML in PHP" %}}
Using [**Aspose.Slides for PHP via Java**](/slides/php-java/), you can import HTML, add a text shape to the generated slide, and export the modified content to HTML5 with a few lines of PHP code.

{{% blocks/products/pf/agp/code-block title="PHP code for editing HTML" offSpacer="true" %}}

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
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to edit HTML in PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{% blocks/products/pf/agp/step-autogen %}}
Install **Aspose.Slides for PHP via Java**. See [**Installation**](https://docs.aspose.com/slides/php-java/installation/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{< blocks/products/pf/agp/step-autogen >}}
Configure Aspose.Slides in your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and remove its default slide with `removeAt(0)`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Read the HTML content with `file_get_contents` and import it with `addFromHtml`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Access the first generated slide, add a rectangle with `addAutoShape`, and set its text with `setText`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Call `save` with the output file path and `SaveFormat::Html5`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Edit Other Files" subTitle="You can also edit presentations in other supported formats." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
