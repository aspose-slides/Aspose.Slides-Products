---
title: Konversikan Image ke PPT di PHP
url: /id/php-java/conversion/image-to-ppt/
keywords: Image ke PPT, Konversikan Image ke PPT, PHP API, Perpustakaan PHP, Image, PPT
description: Konversikan Image ke PPT di PHP. Gunakan PowerPoint PHP API untuk mengonversi file Image ke PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversikan Image ke PPT di PHP" h2="Pustaka PHP PowerPoint yang kuat yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan Image ke PPT di PHP" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/id/php-java/) adalah library PHP yang andal untuk membuat dan memanipulasi file presentasi. Selain itu, ini memberikan cara yang fleksibel untuk mengonversi Image ke PPT. Menggunakan **Aspose.Slides untuk PHP melalui Java**, pengembang atau aplikasi apa pun dapat mengonversi file Image ke PPT hanya dengan beberapa baris kode PHP.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk PHP mengekspor file Image ke format file PPT dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi Image ke PPT dan banyak format file lainnya

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversikan Image ke PPT menggunakan PHP" %}}
Untuk mengonversi Image ke PPT, Anda perlu membuat Presentasi dari file Image dan menyimpannya sebagai PPT.

{{% blocks/products/pf/agp/code-block title="Kode PHP untuk mengubah Image menjadi PPT" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Cara mengonversi Image ke PPT menggunakan Aspose.Slides untuk PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk mengonversi Image ke PPT di PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal [**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/id/php-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek PHP Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buka file sumber Image di PHP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasilnya sebagai file PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Konverter Daring Gratis" sectionDescription="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversikan Image Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi Image dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah ini" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/image-to-html/" name="IMAGE TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}