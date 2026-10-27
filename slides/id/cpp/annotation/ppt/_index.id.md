---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Hapus Anotasi PPT menggunakan C++
url: /id/cpp/annotation/ppt/ 
description: Kode sumber C++ untuk menghapus anotasi dari presentasi PPT.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Hapus Komentar dan Penulis Komentar dari PPT di C++" h2="Bangun aplikasi C++ yang mengelola komentar dan penulis dalam file presentasi menggunakan API sisi server." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hapus Komentar dari PPT melalui C++" variant="code" %}}

Gunakan [Aspose.Slides for C++](/slides/id/cpp/) untuk menghapus komentar dan penulis komentar dari presentasi PPT. Contoh di bawah ini menghapus komentar setiap penulis dari `get_CommentAuthors`, lalu mengosongkan koleksi penulis komentar.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Hapus Anotasi dari PPT – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.ppt");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menghapus Komentar dari PPT melalui C++" intro="Ikuti langkah-langkah ini untuk menghapus komentar dan penulis komentar dari presentasi PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal Aspose.Slides for C++. Lihat [Instalasi](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPT dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterasi penulis komentar dari `get_CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hapus komentar setiap penulis dengan `get_Comments()->Clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kosongkan koleksi penulis komentar.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi yang diperbarui dengan `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Dibuat dengan Aspose.Slides" title="Hapus Komentar PPT Secara Online" description="Aplikasi Aspose.Slides Annotation gratis dibuat dengan [Aspose.Slides for C++](https://products.aspose.com/slides/id/cpp/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Annotation" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menghapus komentar sebelum Anda menulis kode.
- Hapus semua komentar dari file PPT Anda.
- Unduh file yang sudah dibersihkan.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Anotasi" subTitle="Dengan C++, Anda juga dapat menghapus anotasi dari format lain." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
