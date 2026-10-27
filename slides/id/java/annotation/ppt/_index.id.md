---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3630
title: Hapus Anotasi PPT menggunakan Java
url: /id/java/annotation/ppt/ 
description: Hapus komentar dan penulis komentar dari presentasi PPT di Java dengan Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Hapus Komentar dan Penulis Komentar dari PPT di Java" h2="Gunakan Aspose.Slides for Java untuk menghapus komentar dan penulis komentar dari file presentasi." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hapus Komentar dari PPT melalui Java" variant="code" %}}

Aspose.Slides for Java memungkinkan Anda menghapus komentar dan penulis komentar dari presentasi PPT. Muat file dengan kelas `Presentation`, iterasi objek `ICommentAuthor` dari `getCommentAuthors`, hapus komentarnya, lalu simpan presentasi yang diperbarui.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Hapus Anotasi dari PPT – Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menghapus Komentar dari PPT melalui Java" intro="Ikuti langkah-langkah ini untuk menghapus komentar dan penulis komentar dari presentasi PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal Aspose.Slides for Java. Lihat [Instalasi](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPT dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterasi objek `ICommentAuthor` dari `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hapus komentar setiap penulis dengan `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kosongkan koleksi penulis komentar dan simpan file PPT yang diperbarui.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Dibuat dengan Aspose.Slides" title="Hapus Komentar PPT Secara Online" description="Aplikasi Aspose.Slides Annotation gratis dibuat dengan [Aspose.Slides for Java](https://products.aspose.com/slides/id/java/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Annotation" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menghapus komentar sebelum Anda menulis kode.
- Hapus semua komentar dari file PPT Anda.
- Unduh file yang sudah dibersihkan.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Anotasi" subTitle="Dengan Java, Anda juga dapat menghapus anotasi dari format lain." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
