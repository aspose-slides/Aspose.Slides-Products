---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversi PPS ke PNG di PHP
weight: 1560
url: /id/php-java/conversion/pps-to-png/ 
keywords: "Convert, PowerPoint, PPS, PNG, Presentation, PHP"
description: Contoh kode untuk PPS ke PNG konversi PHP. Gunakan PowerPoint PHP API untuk konversi batch file PPS ke file PNG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversi PPS ke PNG di PHP" h2="Pustaka PowerPoint PHP yang andal untuk mengonversi PPS ke PNG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversi PPS ke PNG di PHP" %}}

Perlu mengonversi file PPS ke PNG secara terprogram? Menggunakan [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/id/php-java/) pengembang mana pun dapat mengonversi format PPS ke PNG hanya dengan beberapa baris kode PHP .

Sebagai API pemrosesan presentasi modern, Aspose.Slides untuk PHP membuat PNG dari PPS dengan cepat. Uji kualitas konversi PPS ke PNG langsung di [browser](https://products.aspose.app/slides/conversion Anda). Pustaka Aspose PowerPoint PPTX memungkinkan Anda mengonversi file PPS ke banyak format populer.

Anda dapat menginstal perpustakaan dari [Komposer](https://packagist.org/packages/aspose/slides) menggunakan perintah berikut:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Simpan PPS sebagai PNG di PHP" %}}

Gunakan aplikasi gratis untuk melihat demonstrasi proses konversi PPS ke PNG.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode contoh ini menunjukkan PPS ke PNG Konversi PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pps");
try
{
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

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Mengonversi PPS ke PNG di PHP" intro="Berikut adalah langkah-langkah untuk mengonversi file PPS ke PNG menggunakan PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPS dengan instance kelas Presentasi{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode `save` saat menentukan jalur file keluaran & SaveFormat.PNG sebagai parameter{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}File PPS akan disimpan di jalur yang ditentukan{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Persyaratan sistem" intro="Sebelum menjalankan kode sumber contoh konversi PHP, pastikan Anda memiliki prasyarat berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal PHP 7, tambahkan path ke PHP ke variabel `PATH` sistem dan setel `allow_url_include` ke `On` di file `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal JRE 8. Setel variabel lingkungan `JAVA_HOME` sebagai jalur ke lokasi JRE yang diinstal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal Apache Tomcat 8.0 (lihat [lebih lanjut](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Dibuat dengan Aspose.Slides" title="Konversi PPS ke PNG Secara Online" description="Aplikasi Aspose.Slides Conversion gratis dibuat dengan [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/id/php-java/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPS Anda sendiri." button="Buka Aspose.Slides Conversion" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" upload="Letakkan atau unggah file Anda" saveAs="Simpan sebagai" convert="Konversi" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides mengonversi file sebelum Anda menulis kode.
- Unggah file PPS dan simpan sebagai PNG.
- Unduh hasilnya atau konversi lebih banyak file.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi PPS ke banyak format file lainnya. Lihat konversi lain yang didukung di bawah" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-bmp/" name="PPS TO BMP" description="Gambar bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-fodp/" name="PPS TO FODP" description="Presentasi XML Datar OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-gif/" name="PPS TO GIF" description="Format Pertukaran Grafis" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-html/" name="PPS TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-jpg/" name="PPS TO JPG" description="Gambar JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-odp/" name="PPS TO ODP" description="Format Presentasi OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-otp/" name="PPS TO OTP" description="Format Standar OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-pdf/" name="PPS TO PDF" description="Format Dokumen Portabel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-pot/" name="PPS TO POT" description="File Template Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-potm/" name="PPS TO POTM" description="File Templat Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-potx/" name="PPS TO POTX" description="Presentasi Template Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="Slide Show yang mendukung makro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="Pertunjukan Slide PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-pptm/" name="PPS TO PPTM" description="File Presentasi berkemampuan makro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-pptx/" name="PPS TO PPTX" description="Buka Format presentasi XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-svg/" name="PPS TO SVG" description="Grafik Vektor Skalabel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-swf/" name="PPS TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-tiff/" name="PPS TO TIFF" description="Format Gambar yang Ditandai" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pps-to-xps/" name="PPS TO XPS" description="Spesifikasi Kertas XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
