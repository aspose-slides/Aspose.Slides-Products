---
title: Editar PPTX en PHP
url: /es/php-java/editor/pptx/
keywords: Editar PPTX, Editar PowerPoint, PPTX, PowerPoint, API de PHP, Biblioteca de PHP
description: Edite PPTX en PHP. Use la API de la biblioteca PHP para editar archivos PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Editar PPTX en PHP" h2="Biblioteca PHP de alta velocidad y multiplataforma para editar PPTX usando código PHP" >}}

{{% blocks/products/pf/feature-page-section h2="Edite PPTX usando Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/es/php-java/) es una potente biblioteca de PHP para editar presentaciones de forma rápida y sencilla. Brinda a los usuarios una amplia gama de funciones para ayudarlos a crear diapositivas de aspecto profesional en muy poco tiempo. Con Aspose, los usuarios pueden editar texto, agregar imágenes, animaciones y transiciones a su presentación, así como aplicar varias opciones de formato, como el tipo de fuente y la selección de color. Además, la biblioteca ofrece soporte para archivos de PowerPoint (PPT) y formatos de presentación de OpenOffice (ODP), lo que hace que sea más fácil que nunca compartir presentaciones entre diferentes plataformas sin que surjan problemas de compatibilidad. ¡Al aprovechar el poder de la biblioteca de Aspose al crear o editar su próxima presentación, se asegurará de que sus diapositivas se vean geniales cada vez!
Puede editar un archivo PPTX agregándole una nueva línea de texto. 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Editar PPTX en PHP" %}}
Usando [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/es/php-java/), puede agregar una nueva línea de texto al documento PPTX con solo un pocas líneas de código.

{{% blocks/products/pf/agp/code-block title="Código PHP para editar PPTX" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptx");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.pptx", SaveFormat::Pptx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo editar PPTX en PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instale **Aspose.Slides para PHP a través de Java**. Consulte [**Instalación**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue la biblioteca como referencia en su proyecto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea una instancia de la clase Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue la presentación PPTX que desea editar.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agrega una nueva línea de texto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde el archivo modificado.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Editar otros archivos" subTitle="También puedes editar archivos en otros formatos" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/php-java/editor/pptm/" name="PPTM" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}