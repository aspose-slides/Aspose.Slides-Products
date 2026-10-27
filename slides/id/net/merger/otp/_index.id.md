---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Gabungkan File OTP melalui .NET
weight: 7430
url: /id/net/merger/otp/ 
description: Kode sumber C# untuk menggabungkan dokumen OTP di .NET Framework, .NET Core, Windows Azure, Mono atau Xamarin Platforms.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Gabungkan Format OTP di C#" h2="Penggabungan dokumen OTP asli dan berkinerja tinggi menggunakan Aspose.Slides sisi server untuk .NET API, tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cara Menggabungkan File OTP Menggunakan C#" %}}

Untuk menggabungkan file OTP, kami akan menggunakan
 [Aspose.Slides untuk .NET](https://products.aspose.com/slides/id/net)
 API yang kaya fitur, kuat, dan mudah digunakan manipulasi dokumen dan penggabungan API untuk platform C#. Membuka
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 manajer paket, cari
 **Aspose.Slide**
 dan menginstal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Memerintah" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Gabungkan File OTP - C#" >}}
```cs
var ps1 = new Presentation("presen1.otp");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first OTP presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Langkah-langkah Menggabungkan File OTP di C#" intro="Penggabungan dan penggabungan dokumen dasar dengan [Aspose.Slides for .NET](https://products.aspose.com/slides/id/net) API dapat dilakukan hanya dengan beberapa baris kode." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat semua file OTP dengan path lengkap.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Jadikan satu dokumen sebagai file dasar{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode yang relevan untuk menggabungkan dan menggabungkan file satu per satu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode Save() dan teruskan nama file (path lengkap) dan format (OTP) sebagai parameter.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sekarang Anda dapat membuka dan menggunakan file OTP di Microsoft Office, Adobe PDF, atau program lain yang kompatibel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Persyaratan sistem" intro="API kami didukung di semua platform utama dan Sistem Operasi. Sebelum mengeksekusi kode di bawah ini, pastikan Anda memiliki prasyarat berikut di sistem Anda." %}}

- Microsoft Windows atau OS yang kompatibel dengan .NET Framework, .NET Core, Windows Azure, Mono atau Platform Xamarin
- Lingkungan pengembangan seperti Microsoft Visual Studio
- Aspose.Slides untuk .NET DLL yang dirujuk dalam proyek Anda - Instal dari NuGet menggunakan tombol Unduh di atas

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Menggabungkan File PDF Online"
  description="[Cara Menggabungkan PDF dengan Python](https://products.aspose.com/slides/id/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" %}}

File dengan ekstensi `.OTP` adalah templat presentasi OpenDocument. File ini menyimpan tata letak, gaya, pemformatan, latar belakang, dan konten lain yang dapat digunakan ulang untuk membuat presentasi baru dengan desain yang konsisten. File OTP dapat dibuat dan dibuka oleh aplikasi yang mendukung OpenDocument Format (ODF). Format ini sebanding dengan format templat Microsoft PowerPoint POT dan POTX.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Penggabungan Lainnya yang Didukung" subTitle="Menggunakan C#, One juga dapat menggabungkan banyak format file lainnya termasuk." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/merger/odp/" name="ODP" description="Format Presentasi OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/merger/pot/" name="POT" description="File Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/merger/potm/" name="POTM" description="File Templat Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/merger/potx/" name="POTX" description="Presentasi Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/merger/pps/" name="PPS" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/merger/ppsm/" name="PPSM" description="Slide Show yang mendukung makro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/merger/ppsx/" name="PPSX" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/merger/pptm/" name="PPTM" description="File Presentasi berkemampuan makro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/merger/pptx/" name="PPTX" description="Buka Format presentasi XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
