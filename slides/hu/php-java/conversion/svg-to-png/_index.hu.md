---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: A SVG konvertálása PNG formátumra PHP-ben
url: /hu/php-java/conversion/svg-to-png/
keywords: SVG to PNG, SVG konvertálása PNG formátumba, PHP API, PHP Library, SVG, PNG
description: A SVG konvertálása PNG formátumra PHP-ben. Használja a PowerPoint PHP API-t a SVG fájlok konvertálásához PNG formátumba
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="A SVG konvertálása PNG formátumra PHP-ben" h2="Hatékony PowerPoint PHP-könyvtár, amely segít olyan alkalmazások fejlesztésében, amelyek képesek Microsoft PowerPoint és OpenOffice prezentációs fájlok létrehozására, egyesítésére, ellenőrzésére vagy konvertálására bármilyen szoftver, például Microsoft vagy Open Office, Adobe PDF használata nélkül." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertálja a(z) SVG fájlt PNG formátumra PHP segítségével" variant="code" %}}

A SVG formátum PNG formátumra konvertálásához létre kell hoznia egy prezentációt a SVG fájlból, és el kell mentenie PNG néven.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PHP kód a(z) SVG PNG formátumba való konvertálásához" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="A SVG konvertálása PNG formátumra PHP-ben" %}}

Az [**Aspose.Slides for PHP Java-n keresztül**](https://products.aspose.com/slides/hu/php-java/) egy hatékony PHP-könyvtár prezentációs fájlok létrehozásához és kezeléséhez. Ezenkívül rugalmas módokat biztosít a SVG PNG formátumra való konvertálására. Az **Aspose.Slides for PHP Java-n keresztül** használatával bármely fejlesztő vagy alkalmazás képes konvertálni a SVG fájlokat PNG fájlokra, mindössze néhány sor PHP kóddal.

Modern dokumentumfeldolgozó API-ként az Aspose.Slides for PHP gyorsan exportál SVG fájlokat PNG fájlformátumokba. Az Aspose PowerPoint könyvtár lehetővé teszi a(z) SVG fájl konvertálását PNG-re és sok más fájlformátumra

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="A SVG konvertálása PNG formátumba az Aspose.Slides for PHP API segítségével" intro="Ezek a lépések a SVG PNG formátumra konvertálásához PHP-ben." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telepítse az [**Aspose.Slides for PHP programot Java-n keresztül**](https://products.aspose.com/slides/hu/php-java/) alkalmazást.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Adjon hozzá egy könyvtári hivatkozást (importálja a könyvtárat) a PHP projekthez.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nyissa meg a forrás SVG fájljait PHP-ben.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Az eredmény mentése PNG fájlként.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ingyenes online konverter"
  description="[Hogyan lehet PPT-t HTML-re konvertálni a Pythonban](https://products.aspose.com/slides/hu/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="A(z) SVG konvertálása más támogatott formátumokká" subTitle="A SVG formátumot konvertálhatja, és más fájlformátumba mentheti. Tekintse meg alább az összes támogatott formátumot" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/svg-to-ppt/" name="SVG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hu/php-java/conversion/svg-to-pptx/" name="SVG TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
