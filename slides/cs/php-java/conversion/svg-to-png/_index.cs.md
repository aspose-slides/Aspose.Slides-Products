---
title: Převeďte SVG do PNG v PHP
url: /cs/php-java/conversion/svg-to-png/
keywords: SVG do PNG, Převést SVG do PNG, PHP API, PHP Library, SVG, PNG
description: Převeďte SVG do PNG v PHP. Použijte PowerPoint PHP API k převodu souborů SVG do PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Převeďte SVG do PNG v PHP" h2="Výkonná knihovna PowerPoint PHP, která pomáhá při vývoji aplikací se schopností vytvářet, slučovat, kontrolovat nebo převádět prezentační soubory Microsoft PowerPoint a OpenOffice bez použití jakéhokoli softwaru, jako je Microsoft nebo Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte SVG do PNG v PHP" %}}

[**Aspose.Slides pro PHP přes Javu**](https://products.aspose.com/slides/cs/php-java/) je výkonná PHP knihovna pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby převodu SVG do PNG. Pomocí **Aspose.Slides for PHP přes Java** může každý vývojář nebo aplikace převést soubory SVG do PNG pomocí několika řádků kódu PHP.

Aspose.Slides pro PHP jako moderní API pro zpracování dokumentů rychle exportuje soubory SVG do formátů souborů PNG. Knihovna Aspose PowerPoint vám umožňuje převést SVG do PNGs a mnoho dalších formátů souborů

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte SVG do PNG pomocí PHP" %}}
Chcete-li převést SVG do PNG, budete muset vytvořit prezentaci ze souboru SVG a uložit ji jako PNG.

{{% blocks/products/pf/agp/code-block title="PHP kód pro převod SVG do PNG" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Jak převést SVG do PNG pomocí Aspose.Slides for PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky pro převod SVG do PNG v PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides for PHP přes Java**](https://products.aspose.com/slides/cs/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory SVG v PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložit výsledek jako soubor PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Převést SVG do jiných podporovaných formátů" subTitle="Můžete také převést SVG a uložit do jiných formátů souborů. Všechny podporované formáty naleznete níže" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/svg-to-ppt/" name="SVG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/php-java/conversion/svg-to-pptx/" name="SVG TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}