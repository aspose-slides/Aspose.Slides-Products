---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversi POT ke BMP melalui C#
weight: 1670
url: /id/net/conversion/pot-to-bmp/ 
description: Contoh kode untuk konversi POT ke BMP C#. Gunakan kode contoh API untuk file batch POT ke konversi BMP dalam VB.NET, Asp.NET atau aplikasi berbasis .NET apa pun.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversi POT ke BMP melalui C#" h2="Ekspor file PowerPoint® POT ke BMP di .NET Framework, .NET Core, Windows Azure, Mono atau Platform Xamarin"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cara Mengkonversi POT ke BMP Menggunakan C#" %}}

Untuk mengonversi POT ke BMP, kami akan menggunakan
 [Aspose.Slides untuk .NET](https://products.aspose.com/slides/id/net)
 API yang kaya fitur, kuat, dan mudah digunakan untuk manipulasi dokumen dan API konversi untuk platform C#. Membuka
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 manajer paket, cari
 Aspose.Slide
 dan menginstal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Perintah Konsol Manajer Paket" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode contoh ini menunjukkan Konversi POT ke BMP C#" >}}
```cs
using (var presentation = new Presentation("template.pot"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in BMP format
        bitmap.Save(string.Format("Slide_{0}.bmp", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Bmp);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Langkah-langkah untuk Mengkonversi POT ke BMP melalui C#" intro="Pengembang .NET dapat dengan mudah memuat & mengonversi file POT ke BMP hanya dalam beberapa baris kode." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file POT dengan instance kelas Presentasi{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ulangi setiap Slide dalam Presentasi{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buat gambar skala penuh sebagai Bitmap dengan setiap iterasi{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode Bitmap.Save dengan ekstensi file BMP & ImageFormat.Bmp sebagai parameter{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Persyaratan sistem" intro="Sebelum menjalankan kode sumber sampel konversi .NET, pastikan Anda memiliki prasyarat berikut ini." %}}

- Microsoft Windows atau OS yang kompatibel dengan Platform .NET Framework, .NET Core, Windows Azure, Mono atau Xamarin.
- Lingkungan pengembangan seperti Microsoft Visual Studio.
- Aspose.Slides untuk .NET DLL yang dirujuk dalam proyek Anda.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Aplikasi gratis untuk mengonversi POT ke BMP"
  description="[Coba aplikasi gratis kami untuk mengonversi PPT ke BMP](https://products.aspose.app/slides/conversion/ppt-to-bmp)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi POT ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-emf/" name="POT TO EMF" description="Format Metafile yang Ditingkatkan" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-gif/" name="POT TO GIF" description="Format Pertukaran Grafis" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-html/" name="POT TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-jpeg/" name="POT TO JPEG" description="Gambar JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-odp/" name="POT TO ODP" description="Format Presentasi OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-otp/" name="POT TO OTP" description="Format Standar OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-pdf/" name="POT TO PDF" description="Format Dokumen Portabel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-png/" name="POT TO PNG" description="Grafik Jaringan Portabel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-potm/" name="POT TO POTM" description="File Templat Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-potx/" name="POT TO POTX" description="Presentasi Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-pps/" name="POT TO PPS" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Slide Show yang mendukung makro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-ppsx/" name="POT TO PPSX" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-pptm/" name="POT TO PPTM" description="File Presentasi berkemampuan makro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-pptx/" name="POT TO PPTX" description="Buka Format presentasi XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-svg/" name="POT TO SVG" description="Grafik Vektor Skalabel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-swf/" name="POT TO SWF" description="Format SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-tiff/" name="POT TO TIFF" description="Format Gambar yang Ditandai" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pot-to-xps/" name="POT TO XPS" description="Spesifikasi Kertas XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
