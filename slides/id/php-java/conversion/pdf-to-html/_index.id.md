---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversi PDF ke HTML di PHP
weight: 670
url: /id/php-java/conversion/pdf-to-html/ 
keywords: "Convert, PowerPoint, PDF, HTML, Presentation, PHP"
description: Contoh kode untuk PDF ke HTML konversi PHP. Gunakan PowerPoint PHP API untuk konversi batch file PDF ke file HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversi PDF ke HTML di PHP" h2="Pustaka PowerPoint PHP yang andal untuk mengonversi PDF ke HTML"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversi PDF ke HTML di PHP" %}}

Perlu mengonversi file PDF ke HTML secara terprogram? Menggunakan [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/id/php-java/) pengembang mana pun dapat mengonversi format PDF ke HTML hanya dengan beberapa baris kode PHP .

Sebagai API pemrosesan presentasi modern, Aspose.Slides untuk PHP membuat HTML dari PDF dengan cepat. Uji kualitas konversi PDF ke HTML langsung di [browser](https://products.aspose.app/slides/conversion) Anda. Pustaka Aspose PowerPoint PPTX memungkinkan Anda mengonversi file PDF ke banyak format populer.

Anda dapat menginstal perpustakaan dari [Komposer](https://packagist.org/packages/aspose/slides) menggunakan perintah berikut:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Simpan PDF sebagai HTML di PHP" %}}

Gunakan aplikasi gratis untuk melihat demonstrasi proses konversi PDF ke HTML.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode contoh ini menunjukkan PDF ke HTML Konversi PHP" >}}
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
    $pres->save("output.html", SaveFormat::Html5);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Mengonversi PDF ke HTML di PHP" intro="Berikut adalah langkah-langkah untuk mengonversi file PDF ke HTML menggunakan PHP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PDF dengan instance kelas Presentasi{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode `save` saat menentukan jalur file keluaran & SaveFormat.HTML sebagai parameter{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}File PDF akan disimpan di jalur yang ditentukan{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Persyaratan sistem" intro="Sebelum menjalankan kode sumber contoh konversi PHP, pastikan Anda memiliki prasyarat berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal PHP 7, tambahkan path ke PHP ke variabel `PATH` sistem dan setel `allow_url_include` ke `On` di file `php.ini`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal JRE 8. Setel variabel lingkungan `JAVA_HOME` sebagai jalur ke lokasi JRE yang diinstal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal Apache Tomcat 8.0 (lihat [lebih lanjut](https://docs.aspose.com/slides/php-java/installation/)).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PDF to HTML"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi PDF ke banyak format file lainnya. Lihat konversi lain yang didukung di bawah" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-bmp/" name="PDF TO BMP" description="Gambar bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-fodp/" name="PDF TO FODP" description="Presentasi XML Datar OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-gif/" name="PDF TO GIF" description="Format Pertukaran Grafis" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" description="Gambar JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-odp/" name="PDF TO ODP" description="Format Presentasi OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-otp/" name="PDF TO OTP" description="Format Standar OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-png/" name="PDF TO PNG" description="Grafik Jaringan Portabel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-pot/" name="PDF TO POT" description="File Template Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-potm/" name="PDF TO POTM" description="File Templat Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-potx/" name="PDF TO POTX" description="Presentasi Template Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-pps/" name="PDF TO PPS" description="Pertunjukan Slide PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="Slide Show yang mendukung makro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="Pertunjukan Slide PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-ppt/" name="PDF TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="File Presentasi berkemampuan makro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="Buka Format presentasi XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-svg/" name="PDF TO SVG" description="Grafik Vektor Skalabel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-swf/" name="PDF TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="Format Gambar yang Ditandai" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/php-java/conversion/pdf-to-xps/" name="PDF TO XPS" description="Spesifikasi Kertas XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
