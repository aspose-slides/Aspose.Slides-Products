---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir ODP a BMP en PHP
weight: 220
url: /es/php-java/conversion/odp-to-bmp/ 
keywords: "Convert, PowerPoint, ODP, BMP, Presentation, PHP"
description: Código de muestra para la conversión PHP de ODP a BMP. Utilice la API PHP de PowerPoint para la conversión por lotes de archivos ODP a archivos BMP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir ODP a BMP en PHP" h2="Potente biblioteca PHP de PowerPoint para convertir ODP a BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir ODP a BMP en PHP" %}}

¿Necesita convertir archivos ODP a BMP mediante programación? Usando [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/es/php-java/) cualquier desarrollador puede convertir ODP a BMP con solo unas pocas líneas de código PHP .

Como una API moderna de procesamiento de presentaciones, Aspose.Slides para PHP crea BMP desde ODP rápidamente. Pruebe la calidad de la conversión de ODP a BMP directamente en su [navegador](https://products.aspose.app/slides/conversion). La biblioteca Aspose PowerPoint PPTX le permite convertir archivos ODP a muchos formatos populares.

Puede instalar la biblioteca desde [Composer](https://packagist.org/packages/aspose/slides) usando el siguiente comando:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Consola/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Guardar ODP como BMP en PHP" %}}

Utilice la aplicación gratuita para ver una demostración del proceso de conversión de ODP a BMP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Este código de muestra muestra ODP a BMP Conversión de PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.odp");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".bmp");
        $imageio->write($bmp, "BMP", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo convertir ODP a BMP en PHP" intro="Estos son los pasos para convertir un archivo ODP a BMP usando PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo ODP con una instancia de la clase Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método `save` mientras especifica la ruta del archivo de salida y SaveFormat.BMP como parámetros{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}El archivo ODP se guardará en la ruta especificada{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Requisitos del sistema" intro="Antes de ejecutar el código fuente de ejemplo de conversión de PHP, asegúrese de cumplir con los siguientes requisitos previos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale PHP 7, agregue la ruta de PHP a la variable `PATH` del sistema y establezca `allow_url_include` en `On` en el archivo `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale JRE 8. Establezca la variable de entorno `JAVA_HOME` como ruta a la ubicación de JRE instalada.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale Apache Tomcat 8.0 (ver [más](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert ODP to BMP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otras conversiones admitidas" subTitle="También puede convertir ODP a muchos otros formatos de archivo. Vea otras conversiones admitidas a continuación" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-fodp/" name="ODP TO FODP" description="Presentación XML plana de OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-gif/" name="ODP TO GIF" description="Formato de intercambio gráfico" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-html/" name="ODP TO HTML" description="Lenguaje de marcado de hipertexto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-jpg/" name="ODP TO JPG" description="Imagen JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-otp/" name="ODP TO OTP" description="Formato estándar de OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-pdf/" name="ODP TO PDF" description="Formato de Documento Portable" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-png/" name="ODP TO PNG" description="Gráficos de red portátiles" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-pot/" name="ODP TO POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-potm/" name="ODP TO POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-potx/" name="ODP TO POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-pps/" name="ODP TO PPS" description="Presentación de diapositivas de PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="Presentación de diapositivas de PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Archivo de presentación habilitado para macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Formato de presentación XML abierto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-svg/" name="ODP TO SVG" description="gráficas vectoriales escalables" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-swf/" name="ODP TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Formato de imagen etiquetada" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/odp-to-xps/" name="ODP TO XPS" description="Especificaciones de papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
