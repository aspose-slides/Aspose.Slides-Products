---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir PDF a PPSX en PHP
weight: 770
url: /es/php-java/conversion/pdf-to-ppsx/ 
keywords: "Convert, PowerPoint, PDF, PPSX, Presentation, PHP"
description: Código de muestra para la conversión PHP de PDF a PPSX. Utilice la API PHP de PowerPoint para la conversión por lotes de archivos PDF a archivos PPSX.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir PDF a PPSX en PHP" h2="Potente biblioteca PHP de PowerPoint para convertir PDF a PPSX"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir PDF a PPSX en PHP" %}}

¿Necesita convertir archivos PDF a PPSX mediante programación? Usando [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/es/php-java/) cualquier desarrollador puede convertir PDF a PPSX con solo unas pocas líneas de código PHP .

Como una API moderna de procesamiento de presentaciones, Aspose.Slides para PHP crea PPSX desde PDF rápidamente. Pruebe la calidad de la conversión de PDF a PPSX directamente en su [navegador](https://products.aspose.app/slides/conversion). La biblioteca Aspose PowerPoint PPTX le permite convertir archivos PDF a muchos formatos populares.

Puede instalar la biblioteca desde [Composer](https://packagist.org/packages/aspose/slides) usando el siguiente comando:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Consola/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Guardar PDF como PPSX en PHP" %}}

Utilice la aplicación gratuita para ver una demostración del proceso de conversión de PDF a PPSX.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Este código de muestra muestra PDF a PPSX Conversión de PHP" >}}
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
    $pres->save("output.ppsx", SaveFormat::Ppsx);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo convertir PDF a PPSX en PHP" intro="Estos son los pasos para convertir un archivo PDF a PPSX usando PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PDF con una instancia de la clase Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método `save` mientras especifica la ruta del archivo de salida y SaveFormat.PPSX como parámetros{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}El archivo PDF se guardará en la ruta especificada{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Requisitos del sistema" intro="Antes de ejecutar el código fuente de ejemplo de conversión de PHP, asegúrese de cumplir con los siguientes requisitos previos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale PHP 7, agregue la ruta de PHP a la variable `PATH` del sistema y establezca `allow_url_include` en `On` en el archivo `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale JRE 8. Establezca la variable de entorno `JAVA_HOME` como ruta a la ubicación de JRE instalada.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale Apache Tomcat 8.0 (ver [más](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Creado con Aspose.Slides" title="Convertir PDF a PPSX en línea" description="La aplicación gratuita Aspose.Slides Conversion está creada con [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/es/php-java/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PDF." button="Abrir Aspose.Slides Conversion" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" upload="Arrastre o suba su archivo" saveAs="Guardar como" convert="Convertir" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides convierte archivos antes de escribir código.
- Suba archivos PDF y guárdelos como PPSX.
- Descargue el resultado o convierta más archivos.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otras conversiones admitidas" subTitle="También puede convertir PDF a muchos otros formatos de archivo. Vea otras conversiones admitidas a continuación" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-bmp/" name="PDF TO BMP" description="Imagen de mapa de bits" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-fodp/" name="PDF TO FODP" description="Presentación XML plana de OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-gif/" name="PDF TO GIF" description="Formato de intercambio gráfico" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-html/" name="PDF TO HTML" description="Lenguaje de marcado de hipertexto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" description="Imagen JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-odp/" name="PDF TO ODP" description="Formato de presentación de OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-otp/" name="PDF TO OTP" description="Formato estándar de OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-png/" name="PDF TO PNG" description="Gráficos de red portátiles" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-pot/" name="PDF TO POT" description="Archivos de plantilla de Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-potm/" name="PDF TO POTM" description="Archivo de plantilla de Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-potx/" name="PDF TO POTX" description="Presentación de plantilla de Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-pps/" name="PDF TO PPS" description="Presentación de diapositivas de PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="Presentación de diapositivas habilitada para macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-ppt/" name="PDF TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="Archivo de presentación habilitado para macros" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="Formato de presentación XML abierto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-svg/" name="PDF TO SVG" description="gráficas vectoriales escalables" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-swf/" name="PDF TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="Formato de imagen etiquetada" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-xps/" name="PDF TO XPS" description="Especificaciones de papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
