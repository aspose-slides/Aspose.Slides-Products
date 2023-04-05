---
title: Gabungkan HTML ke Gambar di PHP
url: /id/php-java/merger/html-to-image/
keywords: Gabungkan HTML ke gambar, HTML ke gambar, Gabung HTML, Gabungkan HTML, Gambar, API PHP, Perpustakaan PHP
description: Menggabungkan HTML ke gambar dalam PHP. Gunakan PHP library API untuk menggabungkan HTML ke gambar
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Menggabungkan gambar dalam PHP" h2="Pustaka PHP berkecepatan tinggi dan lintas platform untuk menggabungkan HTML ke gambar menggunakan kode PHP" >}}

{{% blocks/products/pf/feature-page-section h2="Menggabungkan HTML ke gambar menggunakan Aspose.Slides" %}}

[**Aspose.Slides untuk PHP melalui Java**](https://products.aspose.com/slides/id/php-java/) adalah library PHP yang kuat yang digunakan untuk menggabungkan dan memanipulasi presentasi, dokumen HTML, dan file lainnya. Saat Anda menggabungkan HTML ke gambar, Anda secara efektif menggabungkan konten dalam dokumen HTML untuk mendapatkan satu gambar. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Menggabungkan HTML ke gambar dalam PHP" %}}
Menggunakan [**Aspose.Slides untuk PHP via Java**](https://products.aspose.com/slides/id/php-java/), Anda dapat menggabungkan file gambar dengan cepat hanya dengan beberapa baris kode

{{% blocks/products/pf/agp/code-block title="Kode PHP untuk menggabungkan HTML ke gambar" offSpacer="true" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $filename1 = 'file1.html';
    $f1 = fopen($filename1, 'r');
    if ($f1) {
        $contents1 = fread($f1, filesize($filename1));
        fclose($f1);
    }
    
    $pres->getSlides()->addFromHtml($contents1);
    
    $filename2 = 'file2.html';
    $f2 = fopen($filename2, 'r');
    if ($f2) {
        $contents2 = fread($f2, filesize($filename2));
        fclose($f2);
    }
    
    $pres->getSlides()->addFromHtml($contents2);

    $img = $pres->getSlides()->get_Item(0)->getThumbnail(2, 2);
    $imageio = new Java("javax.imageio.ImageIO");
    $javafile = new Java("java.io.File", "merged-image.png");
    $imageio->write($img, "PNG", $javafile);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cara menggabungkan HTML ke gambar di PHP" >}}


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
Muat dokumen HTML yang ingin Anda gabungkan.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan gambar yang dihasilkan.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Menggabungkan File PDF Online" sectionDescription="[Cara Menggabungkan PDF dengan Python](https://products.aspose.com/slides/id/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Menggabungkan file lain" subTitle="Anda juga dapat menggabungkan file dalam format lain untuk mendapatkan satu file" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
    
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}