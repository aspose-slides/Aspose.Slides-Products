---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversi POT ke PPSX di PHP
weight: 980
url: /id/php-java/conversion/pot-to-ppsx/ 
keywords: "Convert, PowerPoint, POT, PPSX, Presentation, PHP"
description: Contoh kode untuk POT ke PPSX konversi PHP. Gunakan PowerPoint PHP API untuk konversi batch file POT ke file PPSX.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversi POT ke PPSX di PHP" h2="Pustaka PowerPoint PHP yang andal untuk mengonversi POT ke PPSX"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversi POT ke PPSX di PHP" %}}

Perlu mengonversi file POT ke PPSX secara terprogram? Menggunakan [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/id/php-java/) pengembang mana pun dapat mengonversi format POT ke PPSX hanya dengan beberapa baris kode PHP .

Sebagai API pemrosesan presentasi modern, Aspose.Slides untuk PHP membuat PPSX dari POT dengan cepat. Uji kualitas konversi POT ke PPSX langsung di [browser](https://products.aspose.app/slides/conversion) Anda. Pustaka Aspose PowerPoint PPTX memungkinkan Anda mengonversi file POT ke banyak format populer.

Anda dapat menginstal perpustakaan dari [Komposer](https://packagist.org/packages/aspose/slides) menggunakan perintah berikut:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Simpan POT sebagai PPSX di PHP" %}}

Gunakan aplikasi gratis untuk melihat demonstrasi proses konversi POT ke PPSX.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode contoh ini menunjukkan POT ke PPSX Konversi PHP" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pot");
try
{
    $pres->save("output.ppsx", SaveFormat::Ppsx);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Mengonversi POT ke PPSX di PHP" intro="Berikut adalah langkah-langkah untuk mengonversi file POT ke PPSX menggunakan PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file POT dengan instance kelas Presentasi{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode `save` saat menentukan jalur file keluaran & SaveFormat.PPSX sebagai parameter{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}File POT akan disimpan di jalur yang ditentukan{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Persyaratan sistem" intro="Sebelum menjalankan kode sumber contoh konversi PHP, pastikan Anda memiliki prasyarat berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal PHP 7, tambahkan path ke PHP ke variabel `PATH` sistem dan setel `allow_url_include` ke `On` di file `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal JRE 8. Setel variabel lingkungan `JAVA_HOME` sebagai jalur ke lokasi JRE yang diinstal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal Apache Tomcat 8.0 (lihat [lebih lanjut](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert POT to PPSX"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi POT ke banyak format file lainnya. Lihat konversi lain yang didukung di bawah" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-bmp/" name="POT TO BMP" description="Gambar bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-fodp/" name="POT TO FODP" description="Presentasi XML Datar OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-gif/" name="POT TO GIF" description="Format Pertukaran Grafis" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-html/" name="POT TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-jpg/" name="POT TO JPG" description="Gambar JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-odp/" name="POT TO ODP" description="Format Presentasi OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-otp/" name="POT TO OTP" description="Format Standar OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-pdf/" name="POT TO PDF" description="Format Dokumen Portabel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-png/" name="POT TO PNG" description="Grafik Jaringan Portabel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-potm/" name="POT TO POTM" description="File Templat Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-potx/" name="POT TO POTX" description="Presentasi Template Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-pps/" name="POT TO PPS" description="Pertunjukan Slide PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Slide Show yang mendukung makro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-pptm/" name="POT TO PPTM" description="File Presentasi berkemampuan makro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-pptx/" name="POT TO PPTX" description="Buka Format presentasi XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-svg/" name="POT TO SVG" description="Grafik Vektor Skalabel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-swf/" name="POT TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-tiff/" name="POT TO TIFF" description="Format Gambar yang Ditandai" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pot-to-xps/" name="POT TO XPS" description="Spesifikasi Kertas XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
