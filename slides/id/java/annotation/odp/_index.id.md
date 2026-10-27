---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1790
title: Hapus Anotasi ODP menggunakan Java
url: /id/java/annotation/odp/ 
description: Hapus komentar dan penulis komentar dari presentasi ODP di Java dengan Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Hapus Komentar dan Penulis Komentar dari ODP di Java" h2="Gunakan Aspose.Slides for Java untuk menghapus komentar dan penulis komentar dari file presentasi." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Hapus Komentar dari ODP melalui Java" variant="code" %}}

Aspose.Slides for Java memungkinkan Anda menghapus komentar dan penulis komentar dari presentasi ODP. Muat file dengan kelas `Presentation`, iterasi objek `ICommentAuthor` dari `getCommentAuthors`, hapus komentarnya, lalu simpan presentasi yang diperbarui.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Hapus Anotasi dari ODP – Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menghapus Komentar dari ODP melalui Java" intro="Ikuti langkah-langkah ini untuk menghapus komentar dan penulis komentar dari presentasi ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal Aspose.Slides for Java. Lihat [Instalasi](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file ODP dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterasi objek `ICommentAuthor` dari `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hapus komentar setiap penulis dengan `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kosongkan koleksi penulis komentar dan simpan file ODP yang diperbarui.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Dibuat dengan Aspose.Slides" title="Hapus Komentar ODP Secara Online" description="Aplikasi Aspose.Slides Annotation gratis dibuat dengan [Aspose.Slides for Java](https://products.aspose.com/slides/id/java/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file ODP Anda sendiri." button="Buka Aspose.Slides Annotation" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menghapus komentar sebelum Anda menulis kode.
- Hapus semua komentar dari file ODP Anda.
- Unduh file yang sudah dibersihkan.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Anotasi" subTitle="Dengan Java, Anda juga dapat menghapus anotasi dari format lain." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
