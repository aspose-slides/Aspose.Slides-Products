---
title: Converter PNG para PPT em PHP
url: /pt/php-java/conversion/png-to-ppt/
keywords: PNG para PPT, Converter PNG para PPT, API PHP, Biblioteca PHP, PNG, PPT
description: Converter PNG para PPT em PHP. Use a API PHP do PowerPoint para converter arquivos PNG em PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter PNG para PPT em PHP" h2="Poderosa biblioteca PowerPoint PHP que ajuda no desenvolvimento de aplicativos com a capacidade de criar, mesclar, inspecionar ou converter arquivos de apresentação do Microsoft PowerPoint e OpenOffice sem o uso de qualquer software como Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converter PNG para PPT em PHP" %}}

[**Aspose.Slides para PHP via Java**](https://products.aspose.com/slides/pt/php-java/) é uma poderosa biblioteca PHP para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter PNG em PPT. Usando **Aspose.Slides para PHP via Java**, qualquer desenvolvedor ou aplicativo pode converter arquivos PNG em PPT com apenas algumas linhas de código PHP.

Como uma API moderna de processamento de documentos, o Aspose.Slides for PHP exporta arquivos PNG para formatos de arquivo PPT rapidamente. A biblioteca Aspose PowerPoint permite converter PNG para PPTs e muitos outros formatos de arquivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converter PNG para PPT usando PHP" %}}
Para converter o PNG para PPT, você precisará criar a apresentação do arquivo PNG e salvá-lo como PPT.

{{% blocks/products/pf/agp/code-block title="Código PHP para converter PNG em PPT" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.png';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
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

{{< blocks/products/pf/feature-page-section  h2="Como converter PNG para PPT usando Aspose.Slides para PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para converter PNG para PPT em PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para PHP via Java**](https://products.aspose.com/slides/pt/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos de origem PNG em PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado como arquivo PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Conversor Online Gratuito" sectionDescription="[Como converter PPT para HTML em Python](https://products.aspose.com/slides/pt/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Converter PNG para outros formatos suportados" subTitle="Você também pode converter PNG e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/png-to-html/" name="PNG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}