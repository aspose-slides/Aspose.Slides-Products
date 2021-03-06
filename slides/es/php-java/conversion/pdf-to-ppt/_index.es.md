---
title: Convertir PDF a PPT en PHP
weight: 780
url: /es/php-java/conversion/pdf-to-ppt/ 
keywords: "Convert, PowerPoint, PDF, PPT, Presentation, PHP"
description: Código de muestra para la conversión PHP de PDF a PPT. Utilice la API PHP de PowerPoint para la conversión por lotes de archivos PDF a archivos PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir PDF a PPT en PHP" h2="Potente biblioteca PHP de PowerPoint para convertir PDF a PPT" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Convertir PDF a PPT en PHP" %}}

¿Necesita convertir archivos PDF a PPT mediante programación? Usando [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/es/php-java/) cualquier desarrollador puede convertir PDF a PPT con solo unas pocas líneas de código PHP .

Como una API moderna de procesamiento de presentaciones, Aspose.Slides para PHP crea PPT desde PDF rápidamente. Pruebe la calidad de la conversión de PDF a PPT directamente en su [navegador](https://products.aspose.app/slides/conversion). La biblioteca Aspose PowerPoint PPTX le permite convertir archivos PDF a muchos formatos populares.

Puede instalar la biblioteca desde [Composer](https://packagist.org/packages/aspose/slides) usando el siguiente comando:

{{% blocks/products/pf/agp/code-block title="Consola/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Cómo convertir PDF a PPT en PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para convertir un archivo PDF a PPT usando PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue el archivo PDF con una instancia de la clase Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Llame al método `save` mientras especifica la ruta del archivo de salida y SaveFormat.PPT como parámetros
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
El archivo PDF se guardará en la ruta especificada
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código fuente de ejemplo de conversión de PHP, asegúrese de cumplir con los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

1. Instale PHP 7, agregue la ruta de PHP a la variable `PATH` del sistema y establezca `allow_url_include` en `On` en el archivo `php.ini`.
1. Instale JRE 8. Establezca la variable de entorno `JAVA_HOME` como ruta a la ubicación de JRE instalada.
1. Instale Apache Tomcat 8.0 (ver [más](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de muestra muestra PDF a PPT Conversión de PHP" offSpacer="" %}}

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
    $pres->save("output.ppt", SaveFormat::Ppt);
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
 
{{% blocks/products/pf/agp/content h2="Guardar PDF como PPT en PHP" %}}
Utilice la aplicación gratuita para ver una demostración del proceso de conversión de PDF a PPT. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PDF to PPT" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir PDF a muchos otros formatos de archivo. Vea otras conversiones admitidas a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-bmp/" name="PDF TO BMP" description="Imagen de mapa de bits" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-fodp/" name="PDF TO FODP" description="Presentación XML plana de OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-gif/" name="PDF TO GIF" description="Formato de intercambio gráfico" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-html/" name="PDF TO HTML" description="Lenguaje de marcado de hipertexto" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" description="Imagen JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-odp/" name="PDF TO ODP" description="Formato de presentación de OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-otp/" name="PDF TO OTP" description="Formato estándar de OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-png/" name="PDF TO PNG" description="Gráficos de red portátiles" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-pot/" name="PDF TO POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-potm/" name="PDF TO POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-potx/" name="PDF TO POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-pps/" name="PDF TO PPS" description="Presentación de diapositivas de PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="Presentación de diapositivas de PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="Archivo de presentación habilitado para macros" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="Formato de presentación XML abierto" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-svg/" name="PDF TO SVG" description="gráficas vectoriales escalables" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-swf/" name="PDF TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="Formato de imagen etiquetada" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-xps/" name="PDF TO XPS" description="Especificaciones de papel XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}