---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversikan SVG ke PNG di PHP
url: /id/php-java/conversion/svg-to-png/
keywords: SVG ke PNG, Konversikan SVG ke PNG, PHP API, Perpustakaan PHP, SVG, PNG
description: Konversikan SVG ke PNG di PHP. Gunakan PowerPoint PHP API untuk mengonversi file SVG ke PNG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversikan SVG ke PNG di PHP" h2="Pustaka PHP PowerPoint yang kuat yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan SVG ke PNG menggunakan PHP" variant="code" %}}

Untuk mengonversi SVG ke PNG, Anda perlu membuat Presentasi dari file SVG dan menyimpannya sebagai PNG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode PHP untuk mengubah SVG menjadi PNG" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan SVG ke PNG di PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/id/php-java/) adalah library PHP yang andal untuk membuat dan memanipulasi file presentasi. Selain itu, ini memberikan cara yang fleksibel untuk mengonversi SVG ke PNG. Menggunakan **Aspose.Slides untuk PHP melalui Java**, pengembang atau aplikasi apa pun dapat mengonversi file SVG ke PNG hanya dengan beberapa baris kode PHP.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk PHP mengekspor file SVG ke format file PNG dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi SVG ke PNG dan banyak format file lainnya

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara mengonversi SVG ke PNG menggunakan Aspose.Slides untuk PHP API" intro="Ini adalah langkah-langkah untuk mengonversi SVG ke PNG di PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/id/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek PHP Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file sumber SVG di PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan hasilnya sebagai file PNG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Konverter Daring Gratis"
  description="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversikan SVG Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi SVG dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah ini" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/svg-to-ppt/" name="SVG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/svg-to-pptx/" name="SVG TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
