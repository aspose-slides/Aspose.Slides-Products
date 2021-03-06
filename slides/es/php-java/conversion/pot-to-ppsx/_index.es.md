---
title: Convertir POT a PPSX en PHP
weight: 980
url: /es/php-java/conversion/pot-to-ppsx/ 
keywords: "Convert, PowerPoint, POT, PPSX, Presentation, PHP"
description: Código de muestra para la conversión PHP de POT a PPSX. Utilice la API PHP de PowerPoint para la conversión por lotes de archivos POT a archivos PPSX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir POT a PPSX en PHP" h2="Potente biblioteca PHP de PowerPoint para convertir POT a PPSX" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Convertir POT a PPSX en PHP" %}}

¿Necesita convertir archivos POT a PPSX mediante programación? Usando [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/es/php-java/) cualquier desarrollador puede convertir POT a PPSX con solo unas pocas líneas de código PHP .

Como una API moderna de procesamiento de presentaciones, Aspose.Slides para PHP crea PPSX desde POT rápidamente. Pruebe la calidad de la conversión de POT a PPSX directamente en su [navegador](https://products.aspose.app/slides/conversion). La biblioteca Aspose PowerPoint PPTX le permite convertir archivos POT a muchos formatos populares.

Puede instalar la biblioteca desde [Composer](https://packagist.org/packages/aspose/slides) usando el siguiente comando:

{{% blocks/products/pf/agp/code-block title="Consola/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Cómo convertir POT a PPSX en PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para convertir un archivo POT a PPSX usando PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue el archivo POT con una instancia de la clase Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Llame al método `save` mientras especifica la ruta del archivo de salida y SaveFormat.PPSX como parámetros
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
El archivo POT se guardará en la ruta especificada
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

{{% blocks/products/pf/agp/code-block title="Este código de muestra muestra POT a PPSX Conversión de PHP" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pot");
try
{
    $pres->save("output.ppsx", SaveFormat::Ppsx);
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
 
{{% blocks/products/pf/agp/content h2="Guardar POT como PPSX en PHP" %}}
Utilice la aplicación gratuita para ver una demostración del proceso de conversión de POT a PPSX. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert POT to PPSX" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir POT a muchos otros formatos de archivo. Vea otras conversiones admitidas a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-bmp/" name="POT TO BMP" description="Imagen de mapa de bits" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-fodp/" name="POT TO FODP" description="Presentación XML plana de OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-gif/" name="POT TO GIF" description="Formato de intercambio gráfico" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-html/" name="POT TO HTML" description="Lenguaje de marcado de hipertexto" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-jpg/" name="POT TO JPG" description="Imagen JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-odp/" name="POT TO ODP" description="Formato de presentación de OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-otp/" name="POT TO OTP" description="Formato estándar de OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-pdf/" name="POT TO PDF" description="Formato de Documento Portable" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-png/" name="POT TO PNG" description="Gráficos de red portátiles" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-potm/" name="POT TO POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-potx/" name="POT TO POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-pps/" name="POT TO PPS" description="Presentación de diapositivas de PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-pptm/" name="POT TO PPTM" description="Archivo de presentación habilitado para macros" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-pptx/" name="POT TO PPTX" description="Formato de presentación XML abierto" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-svg/" name="POT TO SVG" description="gráficas vectoriales escalables" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-swf/" name="POT TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-tiff/" name="POT TO TIFF" description="Formato de imagen etiquetada" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pot-to-xps/" name="POT TO XPS" description="Especificaciones de papel XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}