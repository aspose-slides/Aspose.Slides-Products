---
title: Convert OTP to FODP in PHP 
weight: 440
url: /php-java/conversion/otp-to-fodp/ 
keywords: "Convert, PowerPoint, OTP, FODP, Presentation, PHP"
description: Sample code for OTP to FODP PHP conversion. Use PowerPoint PHP API for batch conversion OTP files to FODP files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert OTP to FODP in PHP" h2="Powerful PowerPoint PHP library for converting OTP to FODP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Convert OTP to FODP in PHP" %}}

Need to convert OTP files to FODP programmatically? Using [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/php-java/) any developer can convert OTP to FODP format with just a few lines of PHP code.

As a modern presentation processing API, Aspose.Slides for PHP creates FODP from OTP quickly. Test the quality of OTP to FODP conversion right in your [browser](https://products.aspose.app/slides/conversion). Aspose PowerPoint PPTX library allows you to convert OTP files to many popular formats.

You can install the library from [Composer](https://packagist.org/packages/aspose/slides) using the following command:

{{% blocks/products/pf/agp/code-block title="Console/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="How to Convert OTP to FODP in PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert a OTP file to FODP using PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load OTP file with an instance of Presentation class
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Call the `save` method while specifying output file path & SaveFormat.FODP as parameters
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
OTP file will be saved at the specified path
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Before running the PHP conversion sample source code, make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

1. Install PHP 7, add path to PHP to system `PATH` variable and set `allow_url_include` to `On` in `php.ini` file.
1. Install JRE 8. Set the `JAVA_HOME` enviroment variable as a path to the installed JRE location.
1. Install Apache Tomcat 8.0 (see [more](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="This sample code shows OTP to FODP PHP Conversion" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.otp");
try
{
    $pres->save("output.fodp", SaveFormat::Fodp);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Save OTP as FODP in PHP" %}}
Use the free app to see a demonstration of the OTP to FODP conversion process. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert OTP to FODP" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert OTP to many other file formats. See other supported conversions below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-bmp/" name="OTP TO BMP" description="Bitmap Image" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-gif/" name="OTP TO GIF" description="Graphical Interchange Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-html/" name="OTP TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-jpg/" name="OTP TO JPG" description="JPEG Image" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-odp/" name="OTP TO ODP" description="OpenDocument Presentation Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-pdf/" name="OTP TO PDF" description="Portable Document Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-png/" name="OTP TO PNG" description="Portable Network Graphics" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-pot/" name="OTP TO POT" description="Microsoft PowerPoint Template Files" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-potm/" name="OTP TO POTM" description="Microsoft PowerPoint Template File" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-potx/" name="OTP TO POTX" description="Microsoft PowerPoint Template Presentation" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-pps/" name="OTP TO PPS" description="PowerPoint Slide Show" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="Macro-enabled Slide Show" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="PowerPoint Slide Show" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-ppt/" name="OTP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-pptm/" name="OTP TO PPTM" description="Macro-enabled Presentation File" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-pptx/" name="OTP TO PPTX" description="Open XML presentation Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-svg/" name="OTP TO SVG" description="Scalable Vector Graphics" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-swf/" name="OTP TO SWF" description="SWF Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-tiff/" name="OTP TO TIFF" description="Tagged Image Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/otp-to-xps/" name="OTP TO XPS" description="XML Paper Specifications" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}