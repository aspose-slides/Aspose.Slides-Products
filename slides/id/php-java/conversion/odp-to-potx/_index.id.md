---
title: Konversi ODP ke POTX di PHP
weight: 320
url: /id/php-java/conversion/odp-to-potx/ 
keywords: "Convert, PowerPoint, ODP, POTX, Presentation, PHP"
description: Contoh kode untuk ODP ke POTX konversi PHP. Gunakan PowerPoint PHP API untuk konversi batch file ODP ke file POTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversi ODP ke POTX di PHP" h2="Pustaka PowerPoint PHP yang andal untuk mengonversi ODP ke POTX" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for PHP via Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/php-java/" installationsDocsLink="https://docs.aspose.com/slides/php-java/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/php-java" learnAsLink="https://docs.aspose.com/slides/php-java/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konversi ODP ke POTX di PHP" %}}

Perlu mengonversi file ODP ke POTX secara terprogram? Menggunakan [*Aspose.Slides for PHP via Java*](https://products.aspose.com/slides/id/php-java/) pengembang mana pun dapat mengonversi format ODP ke POTX hanya dengan beberapa baris kode PHP .

Sebagai API pemrosesan presentasi modern, Aspose.Slides untuk PHP membuat POTX dari ODP dengan cepat. Uji kualitas konversi ODP ke POTX langsung di [browser](https://products.aspose.app/slides/conversion) Anda. Pustaka Aspose PowerPoint PPTX memungkinkan Anda mengonversi file ODP ke banyak format populer.

Anda dapat menginstal perpustakaan dari [Komposer](https://packagist.org/packages/aspose/slides) menggunakan perintah berikut:

{{% blocks/products/pf/agp/code-block title="Konsol/Terminal" offSpacer="true" %}}

```console
> composer require aspose/slides 

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Cara Mengonversi ODP ke POTX di PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Berikut adalah langkah-langkah untuk mengonversi file ODP ke POTX menggunakan PHP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat file ODP dengan instance kelas Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Panggil metode `save` saat menentukan jalur file keluaran & SaveFormat.POTX sebagai parameter
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
File ODP akan disimpan di jalur yang ditentukan
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

{{% blocks/products/pf/agp/code-block title="Kode contoh ini menunjukkan ODP ke POTX Konversi PHP" offSpacer="" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.odp");
try
{
    $pres->save("output.potx", SaveFormat::Potx);
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
 
{{% blocks/products/pf/agp/content h2="Simpan ODP sebagai POTX di PHP" %}}
Gunakan aplikasi gratis untuk melihat demonstrasi proses konversi ODP ke POTX. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/slides-app-widget 
appName="conversion"
extension=""
sectionTitle="Free App to Convert ODP to POTX" 
sectionDescription="[Try our free Video app](https://products.aspose.app/slides/video/)" 
>}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi ODP ke banyak format file lainnya. Lihat konversi lain yang didukung di bawah" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-bmp/" name="ODP TO BMP" description="Gambar bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-fodp/" name="ODP TO FODP" description="Presentasi XML Datar OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-gif/" name="ODP TO GIF" description="Format Pertukaran Grafis" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-html/" name="ODP TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-jpg/" name="ODP TO JPG" description="Gambar JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-otp/" name="ODP TO OTP" description="Format Standar OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-pdf/" name="ODP TO PDF" description="Format Dokumen Portabel" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-png/" name="ODP TO PNG" description="Grafik Jaringan Portabel" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-pot/" name="ODP TO POT" description="File Template Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-potm/" name="ODP TO POTM" description="File Templat Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-pps/" name="ODP TO PPS" description="Pertunjukan Slide PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Slide Show yang mendukung makro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="Pertunjukan Slide PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="File Presentasi berkemampuan makro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Buka Format presentasi XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-svg/" name="ODP TO SVG" description="Grafik Vektor Skalabel" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-swf/" name="ODP TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Format Gambar yang Ditandai" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/php-java/conversion/odp-to-xps/" name="ODP TO XPS" description="Spesifikasi Kertas XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}