---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 70
title: Ekstrak Teks dari File PPT menggunakan .NET
url: /id/net/parser/ppt/ 
description: Kode sumber C# untuk mengekstrak teks dari file PPT menggunakan .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Parsing File PPT menggunakan C#" h2="Ekstrak teks dan periksa format teks dalam file PPT dengan API .NET sisi server."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Parsing File PPT dengan C#" %}}

Gunakan [Aspose.Slides for .NET](/slides/id/net/) untuk mengekstrak teks dari presentasi PPT. Instal paket dari [NuGet](https://www.nuget.org/packages/aspose.slides.net) atau jalankan perintah berikut di Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Perintah" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Parsing File PPT – C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Parsing File PPT di C#" intro="Parsing dokumen dasar dengan API [Aspose.Slides for .NET](/slides/id/net/) hanya memerlukan beberapa baris kode." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPT dengan `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ambil bingkai teks dengan `SlideUtil.GetAllTextFrames`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telusuri bingkai teks, paragraf, dan bagian teks.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Baca properti `Text`, `FontHeight`, dan `LatinFont.FontName` sesuai kebutuhan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Persyaratan Sistem" intro="Diperlukan runtime .NET yang didukung dan referensi paket Aspose.Slides for .NET. Anda dapat menggunakan Visual Studio atau lingkungan pengembangan C# lain yang kompatibel." %}}

- Lingkungan yang kompatibel dengan .NET Framework, .NET, Mono, atau Xamarin
- Lingkungan pengembangan C# seperti Visual Studio
- Aspose.Slides for .NET yang diinstal dari NuGet

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Dibuat dengan Aspose.Slides" title="Ekstrak Teks dan Gambar Secara Online" description="Aplikasi Aspose.Slides Parser gratis dibuat dengan [Aspose.Slides for .NET](https://products.aspose.com/slides/id/net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Parser" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides membaca file Anda sebelum menulis kode.
- Unggah file PPT dan dapatkan teks serta gambarnya.
- Unduh semuanya sebagai satu arsip ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

File PPT adalah presentasi Microsoft PowerPoint 97-2003 dalam format file biner. File ini berisi slide dengan teks, daftar berpoin, gambar, multimedia, dan objek OLE tersemat. Versi PowerPoint yang lebih baru menggunakan format PPTX yang berbasis Office Open XML. Aplikasi seperti OpenOffice Impress dan Apple Keynote juga dapat membuat file PPT.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Parsing Lain yang Didukung" subTitle="Dengan C#, Anda juga dapat melakukan parsing format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/parser/odp/" name="ODP" description="Presentasi OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/parser/pptx/" name="PPTX" description="Presentasi PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
