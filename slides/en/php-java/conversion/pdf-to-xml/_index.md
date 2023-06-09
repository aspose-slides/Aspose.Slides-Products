---
title: Convert PDF to XML in PHP
url: /php-java/conversion/pdf-to-xml/
keywords: PDF to XML, Convert PDF to XML, PHP API, PHP Library, PDF, XML
description: Convert PDF to XML in PHP. Use PowerPoint PHP API to convert PDF files to XML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PDF to XML in PHP" h2="Powerful PowerPoint PHP library that helps in developing applications with the ability to create, merge, inspect, or convert Microsoft PowerPoint and OpenOffice presentation files without the use of any software like Microsoft or Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convert PDF to XML in PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/php-java/) is a powerful PHP library for creating and manipulating presentation files. Moreover, it provides flexible ways to convert PDF to XML. Using **Aspose.Slides for PHP via Java**, any developer or application can convert PDF to XML files with just a few lines of PHP code.

As a modern document processing API, Aspose.Slides for PHP exports PDF files to XML file formats quickly. Aspose PowerPoint library allows you to convert PDF to XMLs and many other file formats

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to XML using PHP" %}}
To convert the PDF to XML, you will need to create Presentation from PDF file and save it as XML.

{{% blocks/products/pf/agp/code-block title="PHP code for converting PDF into XML" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $slide = $pres->getSlides()->get_Item($i);
        $javafos = new Java("java.io.FileOutputStream", "slide_". $i .".xml");
        $slide->writeAsSvg($javafos);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="How to convert PDF to XML using Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert PDF to XML in PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your PHP project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source PDF files in PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as XML file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[How to Convert PPT to HTML in Python](https://products.aspose.com/slides/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convert PDF To Other Supported Formats" subTitle="You can also convert PDF and save to other file formats. See all supported formats below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}