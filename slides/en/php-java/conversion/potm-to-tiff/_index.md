---
title: Convert POTM to TIFF in PHP 
weight: 1250
url: /php-java/conversion/potm-to-tiff/ 
keywords: "Convert, PowerPoint, POTM, TIFF, Presentation, PHP"
description: Sample code for POTM to TIFF PHP conversion. Use PowerPoint PHP API for batch conversion POTM files to TIFF files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert POTM to TIFF in PHP" h2="Powerful PowerPoint PHP library for converting POTM to TIFF" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Convert POTM to TIFF in PHP" %}}

Need to convert POTM files to TIFF programmatically? Using [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/php-java/) any developer can convert POTM to TIFF format with just a few lines of PHP code.

As a modern presentation processing API, Aspose.Slides for PHP creates TIFF from POTM quickly. Test the quality of POTM to TIFF conversion right in your [browser](https://products.aspose.app/slides/conversion). Aspose PowerPoint PPTX library allows you to convert POTM files to many popular formats.

You can install the library from [Composer](https://packagist.org/packages/aspose/slides) using the following command:

{{% blocks/products/pf/agp/code-block title="Console/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="How to Convert POTM to TIFF in PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert a POTM file to TIFF using PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load POTM file with an instance of Presentation class
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Call the `save` method while specifying output file path & SaveFormat.TIFF as parameters
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
POTM file will be saved at the specified path
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

{{% blocks/products/pf/agp/code-block title="This sample code shows POTM to TIFF PHP Conversion" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potm");
try
{
    $pres->save("output.tiff", SaveFormat::Tiff);
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
 
{{% blocks/products/pf/agp/content h2="Save POTM as TIFF in PHP" %}}
Use the free app to see a demonstration of the POTM to TIFF conversion process. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert POTM to TIFF" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert POTM to many other file formats. See other supported conversions below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-bmp/" name="POTM TO BMP" description="Bitmap Image" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-fodp/" name="POTM TO FODP" description="OpenDocument Flat XML Presentation" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-gif/" name="POTM TO GIF" description="Graphical Interchange Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-html/" name="POTM TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-jpg/" name="POTM TO JPG" description="JPEG Image" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-odp/" name="POTM TO ODP" description="OpenDocument Presentation Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-otp/" name="POTM TO OTP" description="OpenDocument Standard Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-pdf/" name="POTM TO PDF" description="Portable Document Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-png/" name="POTM TO PNG" description="Portable Network Graphics" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-pot/" name="POTM TO POT" description="Microsoft PowerPoint Template Files" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-potx/" name="POTM TO POTX" description="Microsoft PowerPoint Template Presentation" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-pps/" name="POTM TO PPS" description="PowerPoint Slide Show" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Macro-enabled Slide Show" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="PowerPoint Slide Show" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Macro-enabled Presentation File" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Open XML presentation Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-svg/" name="POTM TO SVG" description="Scalable Vector Graphics" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-swf/" name="POTM TO SWF" description="SWF Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/potm-to-xps/" name="POTM TO XPS" description="XML Paper Specifications" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}