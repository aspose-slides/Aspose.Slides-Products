---
title: Konversi PPT ke PPSX di PHP
weight: 2250
url: /id/php-java/conversion/ppt-to-ppsx/ 
keywords: "Convert, PowerPoint, PPT, PPSX, Presentation, PHP"
description: Contoh kode untuk PPT ke PPSX konversi PHP. Gunakan PowerPoint PHP API untuk konversi batch file PPT ke file PPSX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversi PPT ke PPSX di PHP" h2="Pustaka PowerPoint PHP yang andal untuk mengonversi PPT ke PPSX" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konversi PPT ke PPSX di PHP" %}}

Perlu mengonversi file PPT ke PPSX secara terprogram? Menggunakan [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/id/php-java/) pengembang mana pun dapat mengonversi format PPT ke PPSX hanya dengan beberapa baris kode PHP .

Sebagai API pemrosesan presentasi modern, Aspose.Slides untuk PHP membuat PPSX dari PPT dengan cepat. Uji kualitas konversi PPT ke PPSX langsung di [browser](https://products.aspose.app/slides/conversion) Anda. Pustaka Aspose PowerPoint PPTX memungkinkan Anda mengonversi file PPT ke banyak format populer.

Anda dapat menginstal perpustakaan dari [Komposer](https://packagist.org/packages/aspose/slides) menggunakan perintah berikut:

{{% blocks/products/pf/agp/code-block title="Konsol/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Cara Mengonversi PPT ke PPSX di PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Berikut adalah langkah-langkah untuk mengonversi file PPT ke PPSX menggunakan PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat file PPT dengan instance kelas Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Panggil metode `save` saat menentukan jalur file keluaran & SaveFormat.PPSX sebagai parameter
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
File PPT akan disimpan di jalur yang ditentukan
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan kode sumber contoh konversi PHP, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

1. Instal PHP 7, tambahkan path ke PHP ke variabel `PATH` sistem dan setel `allow_url_include` ke `On` di file `php.ini`.
1. Instal JRE 8. Setel variabel lingkungan `JAVA_HOME` sebagai jalur ke lokasi JRE yang diinstal.
1. Instal Apache Tomcat 8.0 (lihat [lebih lanjut](https://docs.aspose.com/slides/php-java/installation/)). 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kode contoh ini menunjukkan PPT ke PPSX Konversi PHP" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
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
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Simpan PPT sebagai PPSX di PHP" %}}
Gunakan aplikasi gratis untuk melihat demonstrasi proses konversi PPT ke PPSX. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert PPT to PPSX" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi PPT ke banyak format file lainnya. Lihat konversi lain yang didukung di bawah" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Gambar bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-fodp/" name="PPT TO FODP" description="Presentasi XML Datar OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-gif/" name="PPT TO GIF" description="Format Pertukaran Grafis" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-html/" name="PPT TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-jpg/" name="PPT TO JPG" description="Gambar JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-odp/" name="PPT TO ODP" description="Format Presentasi OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-otp/" name="PPT TO OTP" description="Format Standar OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-pdf/" name="PPT TO PDF" description="Format Dokumen Portabel" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-png/" name="PPT TO PNG" description="Grafik Jaringan Portabel" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-pot/" name="PPT TO POT" description="File Template Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-potm/" name="PPT TO POTM" description="File Templat Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-potx/" name="PPT TO POTX" description="Presentasi Template Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-pps/" name="PPT TO PPS" description="Pertunjukan Slide PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Slide Show yang mendukung makro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="File Presentasi berkemampuan makro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Buka Format presentasi XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-svg/" name="PPT TO SVG" description="Grafik Vektor Skalabel" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-swf/" name="PPT TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Format Gambar yang Ditandai" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/ppt-to-xps/" name="PPT TO XPS" description="Spesifikasi Kertas XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}