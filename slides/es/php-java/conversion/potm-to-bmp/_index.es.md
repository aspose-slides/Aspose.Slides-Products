---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir POTM a BMP en PHP
weight: 1060
url: /es/php-java/conversion/potm-to-bmp/ 
keywords: "Convert, PowerPoint, POTM, BMP, Presentation, PHP"
description: Código de muestra para la conversión PHP de POTM a BMP. Utilice la API PHP de PowerPoint para la conversión por lotes de archivos POTM a archivos BMP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir POTM a BMP en PHP" h2="Potente biblioteca PHP de PowerPoint para convertir POTM a BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir POTM a BMP en PHP" %}}

¿Necesita convertir archivos POTM a BMP mediante programación? Usando [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/es/php-java/) cualquier desarrollador puede convertir POTM a BMP con solo unas pocas líneas de código PHP .

Como una API moderna de procesamiento de presentaciones, Aspose.Slides para PHP crea BMP desde POTM rápidamente. Pruebe la calidad de la conversión de POTM a BMP directamente en su [navegador](https://products.aspose.app/slides/conversion). La biblioteca Aspose PowerPoint PPTX le permite convertir archivos POTM a muchos formatos populares.

Puede instalar la biblioteca desde [Composer](https://packagist.org/packages/aspose/slides) usando el siguiente comando:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Consola/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Guardar POTM como BMP en PHP" %}}

Utilice la aplicación gratuita para ver una demostración del proceso de conversión de POTM a BMP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Este código de muestra muestra POTM a BMP Conversión de PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.potm");
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo convertir POTM a BMP en PHP" intro="Estos son los pasos para convertir un archivo POTM a BMP usando PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo POTM con una instancia de la clase Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método `save` mientras especifica la ruta del archivo de salida y SaveFormat.BMP como parámetros{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}El archivo POTM se guardará en la ruta especificada{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Requisitos del sistema" intro="Antes de ejecutar el código fuente de ejemplo de conversión de PHP, asegúrese de cumplir con los siguientes requisitos previos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale PHP 7, agregue la ruta de PHP a la variable `PATH` del sistema y establezca `allow_url_include` en `On` en el archivo `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale JRE 8. Establezca la variable de entorno `JAVA_HOME` como ruta a la ubicación de JRE instalada.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale Apache Tomcat 8.0 (ver [más](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Creado con Aspose.Slides" title="Convertir POTM a BMP en línea" description="La aplicación gratuita Aspose.Slides Conversion está creada con [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/es/php-java/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos POTM." button="Abrir Aspose.Slides Conversion" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" upload="Arrastre o suba su archivo" saveAs="Guardar como" convert="Convertir" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides convierte archivos antes de escribir código.
- Suba archivos POTM y guárdelos como BMP.
- Descargue el resultado o convierta más archivos.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otras conversiones admitidas" subTitle="También puede convertir POTM a muchos otros formatos de archivo. Vea otras conversiones admitidas a continuación" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-fodp/" name="POTM TO FODP" description="Presentación XML plana de OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-gif/" name="POTM TO GIF" description="Formato de intercambio gráfico" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-html/" name="POTM TO HTML" description="Lenguaje de marcado de hipertexto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-jpg/" name="POTM TO JPG" description="Imagen JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-odp/" name="POTM TO ODP" description="Formato de presentación de OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-otp/" name="POTM TO OTP" description="Formato estándar de OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-pdf/" name="POTM TO PDF" description="Formato de Documento Portable" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-png/" name="POTM TO PNG" description="Gráficos de red portátiles" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-pot/" name="POTM TO POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-potx/" name="POTM TO POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-pps/" name="POTM TO PPS" description="Presentación de diapositivas de PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="Presentación de diapositivas de PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Archivo de presentación habilitado para macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Formato de presentación XML abierto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-svg/" name="POTM TO SVG" description="gráficas vectoriales escalables" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-swf/" name="POTM TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Formato de imagen etiquetada" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/potm-to-xps/" name="POTM TO XPS" description="Especificaciones de papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
