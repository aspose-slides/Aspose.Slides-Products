---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversi PPSM ke BMP di PHP
weight: 1690
url: /id/php-java/conversion/ppsm-to-bmp/ 
keywords: "Convert, PowerPoint, PPSM, BMP, Presentation, PHP"
description: Contoh kode untuk PPSM ke BMP konversi PHP. Gunakan PowerPoint PHP API untuk konversi batch file PPSM ke file BMP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversi PPSM ke BMP di PHP" h2="Pustaka PowerPoint PHP yang andal untuk mengonversi PPSM ke BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversi PPSM ke BMP di PHP" %}}

Perlu mengonversi file PPSM ke BMP secara terprogram? Menggunakan [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/id/php-java/) pengembang mana pun dapat mengonversi format PPSM ke BMP hanya dengan beberapa baris kode PHP .

Sebagai API pemrosesan presentasi modern, Aspose.Slides untuk PHP membuat BMP dari PPSM dengan cepat. Uji kualitas konversi PPSM ke BMP langsung di [browser](https://products.aspose.app/slides/conversion) Anda. Pustaka Aspose PowerPoint PPTX memungkinkan Anda mengonversi file PPSM ke banyak format populer.

Anda dapat menginstal perpustakaan dari [Komposer](https://packagist.org/packages/aspose/slides) menggunakan perintah berikut:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Simpan PPSM sebagai BMP di PHP" %}}

Gunakan aplikasi gratis untuk melihat demonstrasi proses konversi PPSM ke BMP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode contoh ini menunjukkan PPSM ke BMP Konversi PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppsm");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".bmp");
        $imageio->write($bmp, "BMP", $javafile);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Mengonversi PPSM ke BMP di PHP" intro="Berikut adalah langkah-langkah untuk mengonversi file PPSM ke BMP menggunakan PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPSM dengan instance kelas Presentasi{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode `save` saat menentukan jalur file keluaran & SaveFormat.BMP sebagai parameter{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}File PPSM akan disimpan di jalur yang ditentukan{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Persyaratan sistem" intro="Sebelum menjalankan kode sumber contoh konversi PHP, pastikan Anda memiliki prasyarat berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal PHP 7, tambahkan path ke PHP ke variabel `PATH` sistem dan setel `allow_url_include` ke `On` di file `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal JRE 8. Setel variabel lingkungan `JAVA_HOME` sebagai jalur ke lokasi JRE yang diinstal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal Apache Tomcat 8.0 (lihat [lebih lanjut](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPSM to BMP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi PPSM ke banyak format file lainnya. Lihat konversi lain yang didukung di bawah" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-fodp/" name="PPSM TO FODP" description="Presentasi XML Datar OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Format Pertukaran Grafis" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-jpg/" name="PPSM TO JPG" description="Gambar JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="Format Presentasi OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="Format Standar OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Format Dokumen Portabel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-png/" name="PPSM TO PNG" description="Grafik Jaringan Portabel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-pot/" name="PPSM TO POT" description="File Template Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="File Templat Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Presentasi Template Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="Pertunjukan Slide PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="Pertunjukan Slide PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="File Presentasi berkemampuan makro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Buka Format presentasi XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Grafik Vektor Skalabel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Format Gambar yang Ditandai" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="Spesifikasi Kertas XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
