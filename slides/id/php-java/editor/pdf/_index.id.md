---
title: Edit PDF di PHP
url: /id/php-java/editor/pdf/
keywords: Edit PDF, Edit PowerPoint, PDF, PowerPoint, API PHP, Perpustakaan PHP
description: Edit PDF di PHP. Gunakan PHP library API untuk mengedit file PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit PDF di PHP" h2="Pustaka PHP lintas platform dan berkecepatan tinggi untuk mengedit PDF menggunakan kode PHP" >}}

{{% blocks/products/pf/feature-page-section h2="Edit PDF menggunakan Aspose.Slides" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/id/php-java/) adalah library PHP yang andal untuk mengedit presentasi dengan cepat dan mudah. Ini memberi pengguna berbagai fitur untuk membantu mereka membuat slide yang terlihat profesional dalam waktu singkat. Dengan Aspose, pengguna dapat mengedit teks, menambahkan gambar, animasi, dan transisi ke presentasi mereka serta menerapkan berbagai opsi pemformatan seperti jenis font dan pemilihan warna. Selain itu, perpustakaan menawarkan dukungan untuk file PowerPoint (PPT) dan format OpenOffice Presentation (ODP) yang membuatnya lebih mudah dari sebelumnya untuk berbagi presentasi di berbagai platform tanpa timbul masalah kompatibilitas. Dengan memanfaatkan kekuatan perpustakaan Aspose saat membuat atau mengedit presentasi Anda berikutnya, Anda akan yakin bahwa slide Anda selalu tampak hebat!
Anda dapat mengedit file PDF dengan menambahkan baris teks baru ke dalamnya. 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Edit PDF di PHP" %}}
Menggunakan [**Aspose.Slides untuk PHP via Java**](https://products.aspose.com/slides/id/php-java/), Anda dapat menambahkan baris teks baru ke dokumen PDF hanya dengan beberapa baris kode.

{{% blocks/products/pf/agp/code-block title="Kode PHP untuk mengedit PDF" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");

    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("document.pdf", SaveFormat::Pdf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara mengedit PDF di PHP" >}}

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
Muat presentasi PDF yang ingin Anda edit.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan baris teks baru.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan file yang diubah.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Mengedit file lain" subTitle="Anda juga dapat mengedit file dalam format lain" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}