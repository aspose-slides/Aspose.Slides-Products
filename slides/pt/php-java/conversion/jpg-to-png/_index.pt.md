---
title: Converter JPG para PNG em PHP
url: /pt/php-java/conversion/jpg-to-png/
keywords: JPG para PNG, Converter JPG para PNG, API PHP, Biblioteca PHP, JPG, PNG
description: Converter JPG para PNG em PHP. Use a API PHP do PowerPoint para converter arquivos JPG em PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter JPG para PNG em PHP" h2="Poderosa biblioteca PowerPoint PHP que ajuda no desenvolvimento de aplicativos com a capacidade de criar, mesclar, inspecionar ou converter arquivos de apresentação do Microsoft PowerPoint e OpenOffice sem o uso de qualquer software como Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Converter JPG para PNG em PHP" %}}

[**Aspose.Slides para PHP via Java**](https://products.aspose.com/slides/pt/php-java/) é uma poderosa biblioteca PHP para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter JPG em PNG. Usando **Aspose.Slides para PHP via Java**, qualquer desenvolvedor ou aplicativo pode converter arquivos JPG em PNG com apenas algumas linhas de código PHP.

Como uma API moderna de processamento de documentos, o Aspose.Slides for PHP exporta arquivos JPG para formatos de arquivo PNG rapidamente. A biblioteca Aspose PowerPoint permite converter JPG para PNGs e muitos outros formatos de arquivo

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converter JPG para PNG usando PHP" %}}
Para converter o JPG para PNG, você precisará criar a apresentação do arquivo JPG e salvá-lo como PNG.

{{% blocks/products/pf/agp/code-block title="Código PHP para converter JPG em PNG" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename = 'image.jpg';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $image = $pres->getImages()->addImage($contents);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 10, 10, 100, 100, $image);

    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".png");
        $imageio->write($bmp, "PNG", $javafile);
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

{{< blocks/products/pf/feature-page-section  h2="Como converter JPG para PNG usando Aspose.Slides para PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para converter JPG para PNG em PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instale [**Aspose.Slides para PHP via Java**](https://products.aspose.com/slides/pt/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Abra os arquivos de origem JPG em PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o resultado como arquivo PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Converter JPG para outros formatos suportados" subTitle="Você também pode converter JPG e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/jpg-to-html/" name="JPG TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/php-java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}