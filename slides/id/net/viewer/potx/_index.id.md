---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Lihat POTX di C#
keywords: Lihat POTX, Buka POTX, Penampil POTX, POTX, PowerPoint, API C#, Pustaka .NET
weight: 5740
url: /id/net/viewer/potx/ 
description: Lihat file POTX di C#. Gunakan Aspose.Slides for .NET untuk membuka file presentasi dan menyimpannya sebagai HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lihat POTX di C#" h2="API C# untuk membuka file POTX dan menyimpannya sebagai HTML responsif."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Lihat POTX dengan Aspose.Slides" %}}

Untuk melihat file POTX, gunakan API [Aspose.Slides for .NET](https://products.aspose.com/slides/id/net/), API C# yang kaya fitur, andal, dan mudah digunakan. Buka manajer paket [NuGet](https://www.nuget.org/packages/aspose.slides.net), cari **Aspose.Slides**, lalu instal. Anda juga dapat menjalankan perintah berikut di Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Perintah Package Manager Console" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Dengan [**Aspose.Slides for .NET**](/slides/id/net/), Anda dapat memuat file POTX dan menyimpannya sebagai HTML responsif hanya dengan beberapa baris kode.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode C# untuk melihat POTX" >}}
```cs
using var presentation = new Presentation("presentation.potx");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara melihat POTX di C#" intro="Aspose.Slides memungkinkan pengembang melihat file POTX hanya dengan beberapa baris kode." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal **Aspose.Slides for .NET**. Lihat [**Instalasi**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan pustaka sebagai referensi dalam proyek Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file `POTX` dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buat objek `ResponsiveHtmlController` untuk output HTML responsif.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buat objek `HtmlOptions` dan atur properti `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan file POTX sebagai HTML dengan `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Persyaratan sistem" intro="Aspose.Slides for .NET mendukung semua sistem operasi utama. Pastikan Anda memenuhi prasyarat berikut." %}}

- Microsoft Windows atau OS yang kompatibel dengan .NET Framework, .NET Core, Windows Azure, Mono, atau Xamarin
- Lingkungan pengembangan seperti Microsoft Visual Studio
- Referensi ke Aspose.Slides for .NET di proyek Anda

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Dibuat dengan Aspose.Slides" title="Lihat File POTX Secara Online" description="Aplikasi Aspose.Slides Viewer gratis dibuat dengan [Aspose.Slides for .NET](https://products.aspose.com/slides/id/net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file POTX Anda sendiri." button="Buka Aspose.Slides Viewer" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides merender file Anda sebelum menulis kode.
- Unggah file POTX Anda dan lihat slide-nya secara instan.
- Berfungsi di desktop dan perangkat seluler, tanpa PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTX" readMoreLink="https://docs.fileformat.com/presentation/potx/" %}}

File dengan ekstensi .POTX adalah templat presentasi Microsoft PowerPoint berformat Open XML. Berbeda dengan format biner POT, POTX didasarkan pada standar Office Open XML. File POTX menyimpan tata letak slide, tema, gaya, latar belakang, skema warna, font, dan pemformatan lain yang dapat digunakan ulang untuk membuat presentasi baru.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Lihat file lainnya" subTitle="Anda juga dapat membuka dan melihat presentasi dalam format lain." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/viewer/odp/" name="ODP" description="Presentasi OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/viewer/otp/" name="OTP" description="Templat Presentasi OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/viewer/pot/" name="POT" description="Templat PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/viewer/potm/" name="POTM" description="Templat PowerPoint dengan Makro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/viewer/pps/" name="PPS" description="Tayangan Slide PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/viewer/ppsm/" name="PPSM" description="Tayangan Slide PowerPoint dengan Makro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/viewer/ppsx/" name="PPSX" description="Tayangan Slide PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/viewer/ppt/" name="PPT" description="Presentasi PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/viewer/pptm/" name="PPTM" description="Presentasi PowerPoint dengan Makro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/viewer/pptx/" name="PPTX" description="Presentasi PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
