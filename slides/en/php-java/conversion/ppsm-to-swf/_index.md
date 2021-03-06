---
title: Convert PPSM to SWF in PHP 
weight: 1870
url: /php-java/conversion/ppsm-to-swf/ 
keywords: "Convert, PowerPoint, PPSM, SWF, Presentation, PHP"
description: Sample code for PPSM to SWF PHP conversion. Use PowerPoint PHP API for batch conversion PPSM files to SWF files.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert PPSM to SWF in PHP" h2="Powerful PowerPoint PHP library for converting PPSM to SWF" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Convert PPSM to SWF in PHP" %}}

Need to convert PPSM files to SWF programmatically? Using [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/php-java/) any developer can convert PPSM to SWF format with just a few lines of PHP code.

As a modern presentation processing API, Aspose.Slides for PHP creates SWF from PPSM quickly. Test the quality of PPSM to SWF conversion right in your [browser](https://products.aspose.app/slides/conversion). Aspose PowerPoint PPTX library allows you to convert PPSM files to many popular formats.

You can install the library from [Composer](https://packagist.org/packages/aspose/slides) using the following command:

{{% blocks/products/pf/agp/code-block title="Console/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="How to Convert PPSM to SWF in PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="These are the steps to convert a PPSM file to SWF using PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load PPSM file with an instance of Presentation class
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Call the `save` method while specifying output file path & SaveFormat.SWF as parameters
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPSM file will be saved at the specified path
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

{{% blocks/products/pf/agp/code-block title="This sample code shows PPSM to SWF PHP Conversion" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsm");
try
{
    $pres->save("output.swf", SaveFormat::Swf);
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
 
{{% blocks/products/pf/agp/content h2="Save PPSM as SWF in PHP" %}}
Use the free app to see a demonstration of the PPSM to SWF conversion process. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPSM to SWF" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PPSM to many other file formats. See other supported conversions below" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Bitmap Image" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-fodp/" name="PPSM TO FODP" description="OpenDocument Flat XML Presentation" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Graphical Interchange Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-jpg/" name="PPSM TO JPG" description="JPEG Image" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="OpenDocument Presentation Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="OpenDocument Standard Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Portable Document Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-png/" name="PPSM TO PNG" description="Portable Network Graphics" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Microsoft PowerPoint Template Files" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Microsoft PowerPoint Template File" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Microsoft PowerPoint Template Presentation" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="PowerPoint Slide Show" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="PowerPoint Slide Show" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Macro-enabled Presentation File" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Open XML presentation Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Scalable Vector Graphics" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Tagged Image Format" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/php-java/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="XML Paper Specifications" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}