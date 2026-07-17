---
title: Convert PDF to XML in PHP
url: /php-java/conversion/pdf-to-xml/
keywords: PDF to XML, Convert PDF to XML, PHP API, PHP Library, PDF, XML
description: Import PDF pages and write each page as XML-based SVG markup in PHP with Aspose.Slides for PHP via Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PDF to XML in PHP" h2="Import PDF pages and write each page as XML-based SVG markup with Aspose.Slides for PHP via Java." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to XML in PHP" %}}

[**Aspose.Slides for PHP via Java**](/slides/php-java/) can import PDF pages as presentation slides and serialize each slide as SVG, an XML-based vector graphics format.

The example writes the SVG markup to files with the `.xml` extension. It preserves the visual representation of each PDF page; it does not extract the document's logical structure into a generic XML schema.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to XML using PHP" %}}
Create a `Presentation`, import the PDF pages with `addFromPdf`, and call `writeAsSvg` for each imported slide. Because SVG is XML, the resulting markup can be stored in an `.xml` file.

{{% blocks/products/pf/agp/code-block title="PHP code for writing PDF pages as XML-based SVG" offSpacer="true" %}}

```php
$presentation = new Presentation();
try {
    $presentation->getSlides()->removeAt(0);
    $presentation->getSlides()->addFromPdf("document.pdf");

    $slideCount = java_values($presentation->getSlides()->size());
    for ($slideIndex = 0; $slideIndex < $slideCount; $slideIndex++) {
        $slide = $presentation->getSlides()->get_Item($slideIndex);
        $filePath = "slide_" . ($slideIndex + 1) . ".xml";
        $outputStream = new Java("java.io.FileOutputStream", $filePath);
        try {
            $slide->writeAsSvg($outputStream);
        } finally {
            $outputStream->close();
        }
    }
} finally {
    $presentation->dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PDF to XML using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PDF to XML in PHP." >}}

{{% blocks/products/pf/agp/step-autogen %}}
Install [**Aspose.Slides for PHP via Java**](/slides/php-java/).
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Create a `Presentation` and remove its default slide.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
Import the PDF pages with `addFromPdf`.
{{% /blocks/products/pf/agp/step-autogen %}}

{{% blocks/products/pf/agp/step-autogen %}}
For each slide, create an output stream and call `writeAsSvg` to write the XML-based SVG markup.
{{% /blocks/products/pf/agp/step-autogen %}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[Try our free Conversion app](https://products.aspose.app/slides/conversion)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PDF To Other Supported Formats" subTitle="You can also convert PDF and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/slides/php-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
