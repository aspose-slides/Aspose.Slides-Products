---
title: Konversi Presentasi Microsoft PowerPoint ke PDF di PHP
url: /id/php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API untuk Mengonversi PPT ke PDF. Konversikan Presentasi ke JPG, PNG, dan format lain di PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> Presentasi PowerPoint ke Konversi PDF di PHP" h2="Kode Sumber PHP untuk kasus konversi yang berbeda untuk mengkonversi PPT ke PDF, PNG, HTML, JPEG, PPTX dan format lainnya." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides for PHP via Java](https://products.aspose.com/slides/id/php-java/) adalah library kelas lokal yang kuat yang digunakan untuk memproses dan bekerja dengan presentasi. Sangat mudah bagi para pengembang untuk mengonversi PowerPoint ke PDF dengan kecepatan dan akurasi. Dapatkan hasil dalam waktu singkat untuk mengotomatisasi proses bisnis. Kami membahas di sini beberapa kasus untuk membaca atau memuat input apa pun [format PowerPoint yang didukung](https://docs.aspose.com/slides/php-java/supported-file-formats/) dan menulis atau menyimpan ke format output apa pun yang didukung . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi PowerPoint ke PDF di PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/id/php-java/) memungkinkan Anda mengonversi file dalam format PowerPoint PPT, PPTX, dan OpenOffice ODP ke PDF. Untuk mengonversi presentasi ke PDF, cukup berikan nama file dan simpan format ke metode `Presentation.save`. Kelas `Presentation` mengekspos metode `save` yang dapat dipanggil untuk mengonversi seluruh presentasi PPT, PPTX, atau ODP menjadi dokumen PDF.

{{% blocks/products/pf/feature-page-code h3="Konversi PHP PowerPoint ke PDF" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    $pres->save("output.pdf", SaveFormat::Pdf); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf potm-to-pdf potx-to-pdf ppsm-to-pdf odp-to-pdf" >}}

{{% blocks/products/pf/feature-page-section  h2="Konversi PDF ke PPT di PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/id/php-java/) memungkinkan Anda mengimpor presentasi dari PDF. Pada dasarnya, Anda dapat mengonversi PDF ke presentasi PowerPoint. Untuk mengonversi PDF ke Powerpoint, lakukan langkah-langkah berikut:
- Membuat instance objek dari kelas `Presentation`.
- Panggil metode `addFromPdf` dan teruskan file PDF.
- Gunakan metode `save` untuk menyimpan file dalam format PowerPoint.

{{% blocks/products/pf/feature-page-code h3="Konversi PHP PDF ke Powerpoint" %}}

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
    $pres->save("output.pptx", SaveFormat::Pptx); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-ppt pdf-to-pptx pdf-to-odp pdf-to-png pdf-to-jpg pdf-to-html" >}}


{{% blocks/products/pf/feature-page-section  h2="Konversi PPT ke PDF dengan opsi khusus di PHP" %}}

Untuk mengonversi slide PowerPoint ke PDF secara akurat, Pemrogram dapat memuat dokumen menggunakan kelas `Presentation` dan menggunakan kelas `PdfOptions` untuk semua opsi khusus dan khusus seperti tingkat kompresi teks, kualitas Jpeg, perilaku metafile, mengonversi slide tersembunyi serta memilih slide tertentu dan banyak lagi. Bahkan ada opsi untuk melindungi file PDF yang dikonversi dengan kata sandi.
{{% blocks/products/pf/feature-page-code h3="Konversi PHP PowerPoint ke PDF dengan pengaturan khusus" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\PdfOptions;
use aspose\slides\PdfTextCompression;
use aspose\slides\PdfCompliance;
 
$pres = new Presentation("input.pptx");
try
{
    $pdfOptions = new PdfOptions();
    $pdfOptions->setJpegQuality(90);
    $pdfOptions->setSaveMetafilesAsPng(true);
    $pdfOptions->setTextCompression(PdfTextCompression::Flate);
    $pdfOptions->setCompliance(PdfCompliance::Pdf15);
    $pres->save("output.pdf", SaveFormat::Pdf, $pdfOptions);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Konversi Microsoft PowerPoint ke HTML di PHP" %}}
Kapan pun ada kebutuhan untuk menyematkan presentasi di dalam halaman web, maka ada kebutuhan untuk mengonversi slide ke HTML. 
{{% blocks/products/pf/feature-page-code h3="Kode PHP untuk Konversi PowerPoint ke HTML" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\Html5Options;
 
$pres = new Presentation("input.pptx");
try
{
    $html5Options = new Html5Options();
    $html5Options->setAnimateShapes(false);
    $html5Options->setAnimateTransitions(false);
    $pres->save("output.html", SaveFormat::Html5, $html5Options);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Konversi PowerPoint ke JPG" %}}
Mengonversi Microsoft<sup>®</sup> format PowerPoint ke gambar JPEG, PNG, TIFF dll adalah kasus penggunaan umum lainnya yang sebagian besar digunakan untuk membuat thumbnail slide. 
{{% blocks/products/pf/feature-page-code h3="Kode Konverter PHP PPT ke JPG" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
 
$pres = new Presentation("input.pptx");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(1, 1);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPEG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>  
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-jpg pptx-to-jpg ppt-to-png pptx-to-png ppt-to-gif pptx-to-gif" >}}