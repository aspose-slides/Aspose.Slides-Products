---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit file POTX melalui .NET
url: /id/net/editor/potx/ 
description: Kode sumber C# untuk mengedit dokumen POTX di .NET Framework, .NET Core, Windows Azure, Mono atau Xamarin Platforms.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Mengedit Format POTX di C#" h2="Pengeditan dokumen POTX asli dan berkinerja tinggi menggunakan Aspose.Slides sisi server untuk .NET API, tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Adobe PDF."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTM,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cara Mengedit File POTX Menggunakan C#" %}}

Untuk mengedit file POTX, kami akan menggunakan <a href="https://products.aspose.com/slides/id/net">Aspose.Slides for .NET</a> API yang kaya fitur dan kuat dan API yang mudah digunakan untuk platform C# untuk editor apa pun. Buka <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a> pengelola paket, cari <b>Aspose.Slides</b> dan instal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Memerintah" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Edit File POTX - C#" >}}
```cs
using var presentation = new Presentation("document.potx");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.potx", SaveFormat.Potx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Langkah-langkah Mengedit File POTX di C#" intro="Pengeditan dokumen dasar dengan [Aspose.Slides untuk .NET](https://products.aspose.com/slides/id/net) API dapat dilakukan hanya dengan beberapa baris kode." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file POTX dengan objek `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Akses slide dan bentuk target melalui variabel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Perbarui teks melalui `TextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi yang telah diedit dengan `SaveFormat.Potx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Persyaratan sistem" intro="API kami didukung di semua platform utama dan Sistem Operasi. Sebelum mengeksekusi kode di bawah ini, pastikan Anda memiliki prasyarat berikut di sistem Anda." %}}

- Microsoft Windows atau OS yang kompatibel dengan .NET Framework, .NET Core, Windows Azure, Mono atau Platform Xamarin
- Lingkungan pengembangan seperti Microsoft Visual Studio
- Aspose.Slides untuk .NET DLL yang dirujuk dalam proyek Anda - Instal dari NuGet menggunakan tombol Unduh di atas

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Dibuat dengan Aspose.Slides" title="Edit File PPTX Secara Online" description="Aplikasi Aspose.Slides Editor gratis dibuat dengan [Aspose.Slides for .NET](https://products.aspose.com/slides/id/net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPTX Anda sendiri." button="Buka Aspose.Slides Editor" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menangani file Anda sebelum menulis kode.
- Unggah file PPTX Anda dan edit secara instan.
- Simpan dan unduh file yang telah diedit.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTX" readMoreLink="https://docs.fileformat.com/presentation/potx/" %}}

Files with .POTX extension represent Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above. This format was created to replace the POT file format that is based on the binary file format and is supported with PowerPoint 97-2003. The files generated can be used to create presentations that have same layout and other settings required to be applied to new files. These settings can include styles, backgrounds, colour palette, fonts and defaults. Such files are generated in order to create ready-to-use template files for official use.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
