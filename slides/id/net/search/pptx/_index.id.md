---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Cari Teks dalam File Presentasi PPTX menggunakan .NET
url: /id/net/search/pptx/
description: Kode sumber C# untuk mencari teks dalam presentasi PPTX.
keywords: Cari teks di PPTX, temukan teks di PPTX, cari teks presentasi PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Cari Teks dalam File PPTX menggunakan C#" h2="Bangun aplikasi .NET yang menemukan teks dalam presentasi dengan API sisi server." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cari Teks dalam Presentasi PPTX menggunakan C#" variant="code" %}}

Dengan [Aspose.Slides for .NET](/slides/id/net/), Anda dapat mencari teks dalam presentasi PPTX. Ambil bingkai teks dari sebuah slide dengan `SlideUtil.GetAllTextBoxes`, lalu periksa nilai `Text`-nya untuk menemukan frasa yang diperlukan.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cari Teks dalam Presentasi PPTX menggunakan C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Mencari Teks dalam Presentasi PPTX menggunakan C#" intro="Ikuti langkah-langkah berikut untuk mencari teks dalam presentasi PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPTX dengan `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ambil slide yang diperlukan dari `Presentation.Slides` dan tetapkan ke sebuah variabel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ambil bingkai teksnya dengan [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Periksa apakah nilai `Text` setiap bingkai berisi frasa yang diperlukan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Dibuat dengan Aspose.Slides" title="Cari Teks dalam File PPTX Secara Online" description="Aplikasi Aspose.Slides Search gratis dibuat dengan [Aspose.Slides for .NET](https://products.aspose.com/slides/id/net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPTX Anda sendiri." button="Buka Aspose.Slides Search" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menemukan teks sebelum Anda menulis kode.
- Cari teks biasa atau ekspresi reguler di file PPTX Anda.
- Unduh hasil pencarian sebagai file teks.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Pencarian" subTitle="Dengan C#, Anda juga dapat mencari teks dalam format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
