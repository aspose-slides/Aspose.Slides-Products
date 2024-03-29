---
title: Konversi PPTX ke BMP melalui Java
weight: 2950
url: /id/java/conversion/pptx-to-bmp/ 
description: Contoh kode konversi Java untuk format PPTX ke file BMP. Gunakan kode contoh ini untuk mengekspor presentasi PowerPoint & OpenOffice ke BMP dalam Aplikasi berbasis Java Web atau Desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konversi PPTX ke BMP melalui Java" h2="Konversi PPTX ke BMP Java untuk mengonversi satu atau beberapa halaman ke BMP menggunakan perpustakaan Java di tempat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi PPTX ke BMP Menggunakan Java" %}}

 Untuk merender PPTX ke BMP, kami akan menggunakan
 [Aspose.Slides untuk Java](https://products.aspose.com/slides/id/java/)
 API yang merupakan API konversi yang kaya fitur, kuat, dan mudah digunakan untuk platform Java. Anda dapat mengunduh versi terbarunya langsung dari
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 dan instal dalam proyek berbasis Maven Anda dengan menambahkan konfigurasi berikut ke pom.xml.

{{% blocks/products/pf/agp/code-block title="Gudang" offSpacer="true" %}}

```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ketergantungan" offSpacer="true" %}}

```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>version of aspose-slides API</version>
    <classifier>jdk17</classifier>
</dependency>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengkonversi PPTX ke BMP melalui Java" %}}

{{% blocks/products/pf/agp/text %}}

 Pengembang Java dapat dengan mudah mengonversi file PPTX ke BMP hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Muat file PPTX dengan instance kelas Presentasi
1. Ulangi setiap Slide dalam Presentasi
1. Buat gambar skala penuh sebagai Bitmap dengan setiap iterasi
1. Panggil metode Bitmap.save dengan ekstensi file BMP & ImageFormat

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan kode contoh konversi Java, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
- Dapatkan Aspose.Slides versi terbaru untuk Java langsung dari Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kode Sumber Konversi PPTX ke BMP Java" offSpacer="" %}}

```cs
// load PPTX with Aspose.Slides
Presentation presentation = new Presentation("template.pptx");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type BMP for every slide
  File outputfile = new File(sld.getSlideNumber() + ".bmp");
  
  // save the slide image to disk
  ImageIO.write(bi, "bmp", outputfile);
}   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="pptx-to-bmp"
        sectionTitle="Aplikasi gratis untuk mengonversi PPTX ke BMP" 
        sectionDescription="[Coba aplikasi gratis kami untuk mengonversi PPT ke BMP](https://products.aspose.app/slides/conversion/ppt-to-bmp)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi PPTX ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Format Pertukaran Grafis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="Gambar JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-odp/" name="PPTX TO ODP" description="Format Presentasi OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-otp/" name="PPTX TO OTP" description="Format Standar OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Format Dokumen Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-png/" name="PPTX TO PNG" description="Grafik Jaringan Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-pot/" name="PPTX TO POT" description="File Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-potm/" name="PPTX TO POTM" description="File Templat Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Presentasi Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-pps/" name="PPTX TO PPS" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Slide Show yang mendukung makro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="File Presentasi berkemampuan makro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-svg/" name="PPTX TO SVG" description="Grafik Vektor Skalabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-swf/" name="PPTX TO SWF" description="Format SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Format Gambar yang Ditandai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/pptx-to-xps/" name="PPTX TO XPS" description="Spesifikasi Kertas XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}