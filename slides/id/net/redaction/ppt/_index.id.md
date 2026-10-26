---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sensor File Presentasi PPT menggunakan .NET
url: /id/net/redaction/ppt/
description: Kode sumber C# untuk mencari dan mengganti teks dalam presentasi PPT.
keywords: Sensor PPT, cari dan ganti teks di PPT, perbarui presentasi PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sensor File PPT menggunakan C#" h2="Bangun aplikasi .NET yang mencari dan mengganti teks dalam presentasi dengan API sisi server." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sensor Presentasi PPT menggunakan C#" variant="code" %}}

Dengan [Aspose.Slides for .NET](/slides/id/net/), Anda dapat mencari dan mengganti teks dalam presentasi PPT. Gunakan `Presentation.ReplaceText` dengan `TextSearchOptions` untuk mengontrol pencarian, lalu simpan presentasi yang telah diubah.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Sensor Presentasi PPT menggunakan C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menyensor Presentasi PPT menggunakan C#" intro="Ikuti langkah-langkah berikut untuk mengganti teks dalam presentasi PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPT dengan `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gunakan [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) dengan `TextSearchOptions` untuk mengganti teks yang diperlukan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi yang telah diubah dengan `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Dibuat dengan Aspose.Slides" title="Sensor File PPT Secara Online" description="Aplikasi Aspose.Slides Redaction gratis dibuat dengan [Aspose.Slides for .NET](https://products.aspose.com/slides/id/net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Redaction" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides mencari dan mengganti teks sebelum Anda menulis kode.
- Cari dan ganti teks di file PPT Anda, termasuk dengan ekspresi reguler.
- Unduh file yang telah disensor.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Penyensoran" subTitle="Dengan C#, Anda juga dapat menyensor format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
