---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversi PPSX ke ODP melalui Java
weight: 5760
url: /id/java/conversion/ppsx-to-odp/ 
description: Contoh kode konversi Java untuk format PPSX ke file ODP. Gunakan kode contoh ini untuk mengekspor presentasi PowerPoint & OpenOffice ke ODP dalam Aplikasi berbasis Java Web atau Desktop.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversi PPSX ke ODP melalui Java" h2="Konversi PPSX ke ODP Java untuk mengonversi satu atau beberapa halaman ke ODP menggunakan pustaka Java di tempat."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cara Mengonversi PPSX ke ODP Menggunakan Java" %}}

Untuk merender PPSX ke ODP, kami akan menggunakan
 [Aspose.Slides untuk Java](https://products.aspose.com/slides/id/java/)
 API yang merupakan API konversi yang kaya fitur, kuat, dan mudah digunakan untuk platform Java. Anda dapat mengunduh versi terbarunya langsung dari
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 dan instal dalam proyek berbasis Maven Anda dengan menambahkan konfigurasi berikut ke pom.xml.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Gudang" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ketergantungan" >}}
```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode Sumber Konversi PPSX ke ODP Java" >}}
```cs
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("template.ppsx");
// save the presentation as ODP
presentation.save("output.odp", SaveFormat.Odp);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Langkah-langkah untuk Mengkonversi PPSX ke ODP melalui Java" intro="Pengembang Java dapat dengan mudah mengonversi file PPSX ke ODP hanya dalam beberapa baris kode." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPSX dengan instance kelas Presentasi{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode Presentation.save saat menentukan jalur file output & SaveFormat{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}File ODP akan disimpan di jalur yang ditentukan{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Persyaratan sistem" intro="Sebelum menjalankan kode contoh konversi Java, pastikan Anda memiliki prasyarat berikut." %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.
- Dapatkan Aspose.Slides versi terbaru untuk Java langsung dari Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplikasi gratis untuk mengonversi PPSX ke ODP"
  description="[Coba aplikasi Editor gratis kami](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi PPSX ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Gambar bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Format Pertukaran Grafis" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="Gambar JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="Format Standar OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Format Dokumen Portabel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-png/" name="PPSX TO PNG" description="Grafik Jaringan Portabel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="File Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="File Templat Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Presentasi Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Slide Show yang mendukung makro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="File Presentasi berkemampuan makro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Buka Format presentasi XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="Grafik Vektor Skalabel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="Format SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Format Gambar yang Ditandai" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="Spesifikasi Kertas XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
