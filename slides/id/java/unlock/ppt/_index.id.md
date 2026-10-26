---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Membuka Kunci File Presentasi PPT menggunakan Java
url: /id/java/unlock/ppt/
description: Hapus kata sandi dan proteksi tulis dari presentasi PPT di Java menggunakan Aspose.Slides for Java.
keywords: Hapus Proteksi Tulis PPT, Dekripsi PPT, Buka Kunci Presentasi PPT, Hapus Proteksi PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Membuka Kunci PPT menggunakan Java" h2="Buat aplikasi Java yang menghapus kata sandi dan proteksi tulis dari file presentasi dengan API sisi server." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Menghapus Proteksi dari Presentasi PPT melalui Java" variant="code" %}}

Dengan [Aspose.Slides for Java](/slides/id/java/), Anda dapat menghapus enkripsi atau proteksi tulis dari presentasi PPT. Gunakan `LoadOptions.setPassword` untuk membuka presentasi terenkripsi, dan metode `removeEncryption` serta `removeWriteProtection` dari `ProtectionManager` untuk menghapus pengaturan proteksi.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Menghapus Proteksi Kata Sandi dari PPT menggunakan Java" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.ppt", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Menghapus Proteksi Tulis dari Presentasi PPT menggunakan Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menghapus Kata Sandi dari PPT melalui Java" intro="Ikuti langkah-langkah berikut untuk menghapus proteksi dari presentasi PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPT dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gunakan `LoadOptions.setPassword` jika presentasi terenkripsi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil `removeEncryption` atau `removeWriteProtection` dari objek `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi yang sudah dibuka kuncinya dengan `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Dibuat dengan Aspose.Slides" title="Buka Kunci File PPT Secara Online" description="Aplikasi Aspose.Slides Unlock gratis dibuat dengan [Aspose.Slides for Java](https://products.aspose.com/slides/id/java/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Unlock" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menghapus proteksi sebelum Anda menulis kode.
- Hapus kata sandi atau proteksi tulis dari file PPT Anda.
- Unduh file yang sudah dibuka kuncinya.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Membuka Kunci" subTitle="Dengan Java, Anda juga dapat menghapus proteksi dari format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
