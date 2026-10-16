---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter PNG para SVG em PHP
url: /pt/php-java/conversion/png-to-svg/
keywords: PNG para SVG, Converter PNG para SVG, API PHP, Biblioteca PHP, PNG, SVG
description: Converter PNG para SVG em PHP. Use a API PHP do PowerPoint para converter arquivos PNG em SVG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converter PNG para SVG em PHP" h2="Poderosa biblioteca PowerPoint PHP que ajuda no desenvolvimento de aplicativos com a capacidade de criar, mesclar, inspecionar ou converter arquivos de apresentação do Microsoft PowerPoint e OpenOffice sem o uso de qualquer software como Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter PNG para SVG usando PHP" variant="code" %}}

Para converter o PNG para SVG, você precisará criar a apresentação do arquivo PNG e salvá-lo como SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código PHP para converter PNG em SVG" >}}
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

    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $slide = $pres->getSlides()->get_Item($i);
        $javafos = new Java("java.io.FileOutputStream", "slide_". $i .".svg");
        $slide->writeAsSvg($javafos);
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter PNG para SVG em PHP" %}}

[**Aspose.Slides para PHP via Java**](https://products.aspose.com/slides/pt/php-java/) é uma poderosa biblioteca PHP para criar e manipular arquivos de apresentação. Além disso, oferece maneiras flexíveis de converter PNG em SVG. Usando **Aspose.Slides para PHP via Java**, qualquer desenvolvedor ou aplicativo pode converter arquivos PNG em SVG com apenas algumas linhas de código PHP.

Como uma API moderna de processamento de documentos, o Aspose.Slides for PHP exporta arquivos PNG para formatos de arquivo SVG rapidamente. A biblioteca Aspose PowerPoint permite converter PNG para SVGs e muitos outros formatos de arquivo

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como converter PNG para SVG usando Aspose.Slides para PHP API" intro="Estas são as etapas para converter PNG para SVG em PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale [**Aspose.Slides para PHP via Java**](https://products.aspose.com/slides/pt/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adicione uma referência de biblioteca (importe a biblioteca) ao seu projeto PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra os arquivos de origem PNG em PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve o resultado como arquivo SVG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Conversor Online Gratuito"
  description="[Como converter PPT para HTML em Python](https://products.aspose.com/slides/pt/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Converter PNG para outros formatos suportados" subTitle="Você também pode converter PNG e salvar em outros formatos de arquivo. Veja todos os formatos suportados abaixo" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/png-to-html/" name="PNG TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/php-java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
