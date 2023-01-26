---
title: Converter SVG para PPT em PHP
url: /pt/php-java/conversion/svg-to-ppt/
keywords: SVG para PPT, Converter SVG para PPT, API PHP, Biblioteca PHP, SVG, PPT
description: Converter SVG para PPT em PHP. Use a API PHP do PowerPoint para converter arquivos SVG em PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter SVG para PPT em PHP" h2="Poderosa biblioteca PowerPoint PHP que ajuda no desenvolvimento de aplicativos com a capacidade de criar, mesclar, inspecionar ou converter arquivos de apresentação do Microsoft PowerPoint e OpenOffice sem o uso de qualquer software como Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converter SVG para PPT em PHP" %}}

[**Aspose.Slides para PHP via Java**](https://products.aspose.com/slides/pt/php-java/) é uma poderosa biblioteca PHP para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter SVG em PPT. Usando **Aspose.Slides para PHP via Java**, qualquer desenvolvedor ou aplicativo pode converter arquivos SVG em PPT com apenas algumas linhas de código PHP.

Como uma API moderna de processamento de documentos, o Aspose.Slides for PHP exporta arquivos SVG para formatos de arquivo PPT rapidamente. A biblioteca Aspose PowerPoint permite converter SVG para PPTs e muitos outros formatos de arquivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converter SVG para PPT usando PHP" %}}
Para converter o SVG para PPT, você precisará criar a apresentação do arquivo SVG e salvá-lo como PPT.

{{% blocks/products/pf/agp/code-block title="Código PHP para converter SVG em PPT" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Como converter SVG para PPT usando Aspose.Slides para PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para converter SVG para PPT em PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para PHP via Java**](https://products.aspose.com/slides/pt/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos de origem SVG em PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado como arquivo PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converter SVG para outros formatos suportados" subTitle="Você também pode converter SVG e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/svg-to-png/" name="SVG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/svg-to-pptx/" name="SVG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}