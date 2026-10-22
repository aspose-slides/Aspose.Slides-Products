---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit file PPSM melalui .NET
url: /id/net/editor/ppsm/ 
description: Kode sumber C# untuk mengedit dokumen PPSM di .NET Framework, .NET Core, Windows Azure, Mono atau Platform Xamarin.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Mengedit Format PPSM di C#" h2="Pengeditan dokumen PPSM asli dan berkinerja tinggi menggunakan Aspose.Slides sisi server untuk .NET API, tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cara Mengedit File PPSM Menggunakan C#" %}}

Untuk mengedit file PPSM, kami akan menggunakan <a href="https://products.aspose.com/slides/id/net">Aspose.Slides for .NET</a> API yang kaya fitur, kuat dan API yang mudah digunakan untuk platform C# untuk editor apa pun. Buka <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a> pengelola paket, cari <b>Aspose.Slides</b> dan instal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Memerintah" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Edit File PPSM - C#" >}}
```cs
using var presentation = new Presentation("document.ppsm");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.ppsm", SaveFormat.Ppsm);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Langkah-langkah Mengedit File PPSM di C#" intro="Pengeditan dokumen dasar dengan [Aspose.Slides untuk .NET](https://products.aspose.com/slides/id/net) API dapat dilakukan hanya dengan beberapa baris kode." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPSM dengan objek `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Akses slide dan bentuk target melalui variabel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Perbarui teks melalui `TextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi yang telah diedit dengan `SaveFormat.Ppsm`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Persyaratan sistem" intro="API kami didukung di semua platform utama dan Sistem Operasi. Sebelum mengeksekusi kode di bawah ini, pastikan Anda memiliki prasyarat berikut di sistem Anda." %}}

- Microsoft Windows atau OS yang kompatibel dengan .NET Framework, .NET Core, Windows Azure, Mono atau Platform Xamarin
- Lingkungan pengembangan seperti Microsoft Visual Studio
- Aspose.Slides untuk .NET DLL yang dirujuk dalam proyek Anda - Instal dari NuGet menggunakan tombol Unduh di atas

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSM" readMoreLink="https://docs.fileformat.com/presentation/ppsm/" %}}

Files with PPSM extension represent Macro-enabled Slide Show file format created with Microsoft PowerPoint 2007 or higher. Another similar file format is PPTM which differs in opening with Microsoft PowerPoint in editable format instead of running as Slide Show. When run as slide show, the PPSM file shows the presentation slides with contents intact in the slide show and is in read-only mode by default. PPSM files can still be edited in Microsoft PowerPoint by opening it in PowerPoint.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
