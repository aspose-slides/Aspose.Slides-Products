---
title: Convertir PDF a JPG en PHP
url: /es/php-java/conversion/pdf-to-jpg/
keywords: PDF a JPG, Convertir PDF a JPG, API de PHP, Biblioteca PHP, PDF, JPG
description: Convierte PDF a JPG en PHP. Use la API PHP de PowerPoint para convertir archivos PDF a JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir PDF a JPG en PHP" h2="Potente biblioteca PHP de PowerPoint que ayuda a desarrollar aplicaciones con la capacidad de crear, fusionar, inspeccionar o convertir archivos de presentación de Microsoft PowerPoint y OpenOffice sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir PDF a JPG en PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/es/php-java/) es una potente biblioteca de PHP para crear y manipular archivos de presentación. Además, proporciona formas flexibles de convertir PDF a JPG. Con **Aspose.Slides para PHP a través de Java**, cualquier desarrollador o aplicación puede convertir archivos PDF a JPG con solo unas pocas líneas de código PHP.

Como una API de procesamiento de documentos moderna, Aspose.Slides para PHP exporta archivos PDF a formatos de archivo JPG rápidamente. La biblioteca de PowerPoint de Aspose le permite convertir PDF a JPGs y muchos otros formatos de archivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta PDF a JPG usando PHP" %}}
Para convertir PDF a JPG, deberá crear la presentación desde el archivo PDF y guardarlo como JPG.

{{% blocks/products/pf/agp/code-block title="Código PHP para convertir PDF en JPG" offSpacer="true" %}}

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
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPG", $javafile);
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

{{< blocks/products/pf/feature-page-section  h2="Cómo convertir PDF a JPG usando Aspose.Slides para PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para convertir PDF a JPG en PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para PHP a través de Java**](https://products.aspose.com/slides/es/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra los archivos fuente PDF en PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado como archivo JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertidor en línea gratuito" sectionDescription="[Cómo convertir PPT a HTML en Python](https://products.aspose.com/slides/es/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir PDF a otros formatos admitidos" subTitle="También puede convertir PDF y guardar en otros formatos de archivo. Ver todos los formatos admitidos a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/pdf-to-xml/" name="PDF TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}