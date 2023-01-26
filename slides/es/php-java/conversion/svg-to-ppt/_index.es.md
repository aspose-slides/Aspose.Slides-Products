---
title: Convertir SVG a PPT en PHP
url: /es/php-java/conversion/svg-to-ppt/
keywords: SVG a PPT, Convertir SVG a PPT, API de PHP, Biblioteca PHP, SVG, PPT
description: Convierte SVG a PPT en PHP. Use la API PHP de PowerPoint para convertir archivos SVG a PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir SVG a PPT en PHP" h2="Potente biblioteca PHP de PowerPoint que ayuda a desarrollar aplicaciones con la capacidad de crear, fusionar, inspeccionar o convertir archivos de presentación de Microsoft PowerPoint y OpenOffice sin el uso de ningún software como Microsoft u Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir SVG a PPT en PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/es/php-java/) es una potente biblioteca de PHP para crear y manipular archivos de presentación. Además, proporciona formas flexibles de convertir SVG a PPT. Con **Aspose.Slides para PHP a través de Java**, cualquier desarrollador o aplicación puede convertir archivos SVG a PPT con solo unas pocas líneas de código PHP.

Como una API de procesamiento de documentos moderna, Aspose.Slides para PHP exporta archivos SVG a formatos de archivo PPT rápidamente. La biblioteca de PowerPoint de Aspose le permite convertir SVG a PPTs y muchos otros formatos de archivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta SVG a PPT usando PHP" %}}
Para convertir SVG a PPT, deberá crear la presentación desde el archivo SVG y guardarlo como PPT.

{{% blocks/products/pf/agp/code-block title="Código PHP para convertir SVG en PPT" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.svg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $svgImage = new SvgImage($contents);
    $image = $pres->getImages()->addImage($svgImage);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    $pres->save("output.ppt", SaveFormat::Ppt);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo convertir SVG a PPT usando Aspose.Slides para PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para convertir SVG a PPT en PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para PHP a través de Java**](https://products.aspose.com/slides/es/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue una referencia de biblioteca (importe la biblioteca) a su proyecto PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra los archivos fuente SVG en PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado como archivo PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir SVG a otros formatos admitidos" subTitle="También puede convertir SVG y guardar en otros formatos de archivo. Ver todos los formatos admitidos a continuación" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/conversion/svg-to-pptx/" name="SVG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}