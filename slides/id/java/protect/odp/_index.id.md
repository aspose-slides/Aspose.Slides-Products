---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Melindungi File Presentasi ODP menggunakan Java
url: /id/java/protect/odp/
description: Lindungi presentasi ODP di Java. Gunakan Aspose.Slides for Java untuk mengenkripsi file presentasi dan mengatur proteksi tulis.
keywords: Proteksi Tulis ODP, Enkripsi File ODP, Kunci Presentasi ODP, Lindungi ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Mengunci atau Melindungi ODP dengan Kata Sandi menggunakan Java" h2="Buat aplikasi Java yang melindungi file presentasi dengan API sisi server." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Melindungi Presentasi ODP dengan Java" variant="code" %}}

Dengan [Aspose.Slides for Java](/slides/id/java/), Anda dapat melindungi presentasi ODP agar tidak dibuka atau diubah dengan mengatur kata sandi. Gunakan objek `ProtectionManager` dari kelas `Presentation` untuk memanggil metode seperti `encrypt` dan `setWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mengenkripsi Presentasi ODP menggunakan Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Mengatur Proteksi Tulis untuk Presentasi ODP menggunakan Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Melindungi ODP dengan Kata Sandi melalui Java" intro="Ikuti langkah-langkah berikut untuk melindungi presentasi ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file ODP dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode `encrypt` atau metode `setWriteProtection` dari objek `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan file yang dilindungi dengan `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Dibuat dengan Aspose.Slides" title="Lindungi File ODP dengan Kata Sandi Secara Online" description="Aplikasi Aspose.Slides Lock gratis dibuat dengan [Aspose.Slides for Java](https://products.aspose.com/slides/id/java/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file ODP Anda sendiri." button="Buka Aspose.Slides Lock" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides melindungi presentasi sebelum Anda menulis kode.
- Atur kata sandi untuk membuka atau mengedit file ODP Anda.
- Unduh file yang dilindungi.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Proteksi" subTitle="Dengan Java, Anda juga dapat melindungi format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
