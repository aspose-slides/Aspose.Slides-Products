---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1480
title: Ekstrak Teks dari File PPTX menggunakan .NET
url: /id/net/parser/pptx/ 
description: Kode sumber C# untuk mengekstrak teks dari file PPTX menggunakan .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Parsing File PPTX menggunakan C#" h2="Ekstrak teks dan periksa format teks dalam file PPTX dengan API .NET sisi server."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Parsing File PPTX dengan C#" %}}

Gunakan [Aspose.Slides for .NET](/slides/id/net/) untuk mengekstrak teks dari presentasi PPTX. Instal paket dari [NuGet](https://www.nuget.org/packages/aspose.slides.net) atau jalankan perintah berikut di Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Perintah" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Parsing File PPTX – C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Parsing File PPTX di C#" intro="Parsing dokumen dasar dengan API [Aspose.Slides for .NET](/slides/id/net/) hanya memerlukan beberapa baris kode." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPTX dengan `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Dibuat dengan Aspose.Slides" title="Ekstrak Teks dan Gambar Secara Online" description="Aplikasi Aspose.Slides Parser gratis dibuat dengan [Aspose.Slides for .NET](https://products.aspose.com/slides/id/net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPTX Anda sendiri." button="Buka Aspose.Slides Parser" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides membaca file Anda sebelum menulis kode.
- Unggah file PPTX dan dapatkan teks serta gambarnya.
- Unduh semuanya sebagai satu arsip ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

PPTX files are presentations created with Microsoft PowerPoint. Unlike the binary PPT format, PPTX uses the Office Open XML format. A presentation contains slides with text, images, formatting, animations, and other media that are shown as a slideshow.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Parsing Lain yang Didukung" subTitle="Dengan C#, Anda juga dapat melakukan parsing format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/parser/odp/" name="ODP" description="Presentasi OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/parser/ppt/" name="PPT" description="Presentasi PowerPoint 97-2003" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
