---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Hapus Anotasi PPTX menggunakan .NET
url: /id/net/annotation/pptx/ 
description: Hapus komentar dan penulis komentar dari presentasi PPTX di C#.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Hapus Komentar & Penulis Komentar dari PPTX di C#" h2="Bangun aplikasi .NET yang mengelola komentar dan penulis dalam file presentasi menggunakan API sisi server." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hapus Komentar dari PPTX melalui C#" variant="code" %}}

Gunakan [Aspose.Slides for .NET](/slides/id/net/) untuk menghapus komentar dan penulis komentar dari file presentasi PPTX. Contoh di bawah ini mengosongkan koleksi `Comments` milik setiap penulis, lalu mengosongkan koleksi `CommentAuthors` presentasi.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Hapus Anotasi dari PPTX – C#" >}}
```cs
using var presentation = new Presentation("example.pptx");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menghapus Komentar dari PPTX melalui C#" intro="Ikuti langkah-langkah ini untuk menghapus komentar dan penulis komentar dari presentasi PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal Aspose.Slides for .NET. Lihat [Instalasi](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPTX dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterasi koleksi `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kosongkan koleksi `Comments` untuk setiap penulis komentar.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kosongkan koleksi `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi yang diperbarui dengan `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Dibuat dengan Aspose.Slides" title="Hapus Komentar PPTX Secara Online" description="Aplikasi Aspose.Slides Annotation gratis dibuat dengan [Aspose.Slides for .NET](https://products.aspose.com/slides/id/net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPTX Anda sendiri." button="Buka Aspose.Slides Annotation" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menghapus komentar sebelum Anda menulis kode.
- Hapus semua komentar dari file PPTX Anda.
- Unduh file yang sudah dibersihkan.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Anotasi" subTitle="Dengan C#, Anda juga dapat menghapus anotasi dari format lain." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
