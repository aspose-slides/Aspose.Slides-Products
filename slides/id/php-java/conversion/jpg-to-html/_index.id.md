---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversikan JPG ke HTML di PHP
url: /id/php-java/conversion/jpg-to-html/
keywords: JPG ke HTML, Konversikan JPG ke HTML, PHP API, Perpustakaan PHP, JPG, HTML
description: Konversikan JPG ke HTML di PHP. Gunakan PowerPoint PHP API untuk mengonversi file JPG ke HTML
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversikan JPG ke HTML di PHP" h2="Pustaka PHP PowerPoint yang kuat yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan JPG ke HTML menggunakan PHP" variant="code" %}}

Untuk mengonversi JPG ke HTML, Anda perlu membuat Presentasi dari file JPG dan menyimpannya sebagai HTML.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode PHP untuk mengubah JPG menjadi HTML" >}}
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

    $pres->save("output.pptx", SaveFormat::Pptx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan JPG ke HTML di PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/id/php-java/) adalah library PHP yang andal untuk membuat dan memanipulasi file presentasi. Selain itu, ini memberikan cara yang fleksibel untuk mengonversi JPG ke HTML. Menggunakan **Aspose.Slides untuk PHP melalui Java**, pengembang atau aplikasi apa pun dapat mengonversi file JPG ke HTML hanya dengan beberapa baris kode PHP.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk PHP mengekspor file JPG ke format file HTML dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi JPG ke HTML dan banyak format file lainnya

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara mengonversi JPG ke HTML menggunakan Aspose.Slides untuk PHP API" intro="Ini adalah langkah-langkah untuk mengonversi JPG ke HTML di PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/id/php-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek PHP Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file sumber JPG di PHP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan hasilnya sebagai file HTML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Konverter Daring Gratis"
  description="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversikan JPG Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi JPG dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah ini" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
