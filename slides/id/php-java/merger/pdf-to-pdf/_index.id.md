---
title: Menggabungkan File PDF di PHP
url: /id/php-java/merger/pdf-to-pdf/
keywords: Gabungkan PDF, PDF ke PDF, Gabung PDF, Gabungkan PDF, API PHP, Perpustakaan PHP
description: Menggabungkan PDF ke PDF dalam PHP. Gunakan PHP library API untuk menggabungkan file PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Menggabungkan PDF dalam PHP" h2="Pustaka PHP berkecepatan tinggi dan lintas platform untuk menggabungkan file PDF menggunakan kode PHP" >}}

{{% blocks/products/pf/feature-page-section h2="Gabungkan PDF ke PDF menggunakan Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/id/php-java/) adalah library PHP yang kuat yang digunakan untuk membuat, mengonversi, menggabungkan, dan memanipulasi presentasi, PDF, dan dokumen lainnya. Saat Anda menggabungkan PDF ke PDF, Anda secara efektif menggabungkan halaman dari 2 dokumen untuk mendapatkan satu file PDF. Aspose.Slides memungkinkan Anda menggabungkan PDF dengan berbagai cara. Anda dapat menggabungkan PDF dengan semua bentuk, gaya, teks, pemformatan, dll.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Menggabungkan PDF ke PDF dalam PHP" %}}
Menggunakan [**Aspose.Slides untuk PHP via Java**](https://products.aspose.com/slides/id/php-java/), Anda dapat menggabungkan file PDF dengan cepat hanya dengan beberapa baris kode

{{% blocks/products/pf/agp/code-block title="Kode PHP untuk menggabungkan PDF ke PDF" offSpacer="true" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $pres->getSlides()->addFromPdf("document1.pdf");
    $pres->getSlides()->addFromPdf("document2.pdf");

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




{{< blocks/products/pf/feature-page-section  h2="Cara menggabungkan PDF di PHP" >}}


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
Muat file PDF yang ingin Anda gabungkan.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan PDF yang dihasilkan.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Menggabungkan file lain" subTitle="Anda juga dapat menggabungkan file dalam format lain untuk mendapatkan satu file" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}