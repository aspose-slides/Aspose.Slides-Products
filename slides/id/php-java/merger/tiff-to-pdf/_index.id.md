---
title: Menggabungkan TIFF ke PDF dalam PHP
url: /id/php-java/merger/tiff-to-pdf/
keywords: TIFF ke PDF, Gabungkan TIFF ke PDF, Gabung TIFF ke PDF, PDF, TIFF, API PHP, Perpustakaan PHP
description: Menggabungkan TIFF ke PDF dalam PHP. Gunakan PHP library API untuk menggabungkan TIFF dan PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Menggabungkan TIFF ke PDF dalam PHP" h2="Pustaka PHP berkecepatan tinggi dan lintas platform untuk menggabungkan file TIFF ke PDF menggunakan kode PHP" >}}

{{% blocks/products/pf/feature-page-section h2="Menggabungkan TIFF ke PDF menggunakan Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/id/php-java/) adalah library PHP yang kuat yang digunakan untuk membuat, mengonversi, menggabungkan, dan memanipulasi presentasi, PDF, gambar, dan file lainnya. Saat Anda menggabungkan TIFF ke PDF, Anda menggabungkan gambar secara efektif untuk mendapatkan satu file PDF.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Menggabungkan TIFF ke PDF dalam PHP" %}}
Menggunakan [**Aspose.Slides untuk PHP via Java**](https://products.aspose.com/slides/id/php-java/), Anda dapat menggabungkan TIFF ke PDF dengan cepat hanya dengan beberapa baris kode

{{% blocks/products/pf/agp/code-block title="Kode PHP untuk menggabungkan TIFF ke PDF" offSpacer="true" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename1 = 'image1.tif';
    $f1 = fopen($filename1, 'r');
    if ($f1) {
        $contents1 = fread($f1, filesize($filename1));
        fclose($f1);
    }

    $filename2 = 'image2.tif';
    $f2 = fopen($filename2, 'r');
    if ($f2) {
        $contents2 = fread($f2, filesize($filename2));
        fclose($f2);
    }
    
    $image1 = $pres->getImages()->addImage($contents1);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 0, 0, 360, 540, $image1);
    
    $image2 = $pres->getImages()->addImage($contents2);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 360, 0, 360, 540, $image2);

    $pres->save("merged-pdf.pdf", SaveFormat::Pdf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cara menggabungkan TIFF ke PDF di PHP" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instal **Aspose.Slides untuk PHP melalui Java**. Lihat [**Instalasi**](https://docs.aspose.com/slides/php-java/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan perpustakaan sebagai referensi dalam proyek Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buat sebuah instance dari kelas Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat file TIFF yang ingin Anda gabungkan sebagai bingkai foto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan PDF yang dihasilkan.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Menggabungkan File PDF Online" sectionDescription="[Cara Menggabungkan PDF dengan Python](https://products.aspose.com/slides/id/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Menggabungkan file lain" subTitle="Anda juga dapat menggabungkan file dalam format lain untuk mendapatkan satu file" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}