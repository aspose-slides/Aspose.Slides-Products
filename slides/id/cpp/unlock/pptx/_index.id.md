---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Membuka Kunci Presentasi PPTX menggunakan C++
url: /id/cpp/unlock/pptx/
description: Buka kunci presentasi PPTX di C++. Gunakan Aspose.Slides for C++ untuk menghapus enkripsi dan proteksi tulis dari file presentasi.
keywords: Hapus Proteksi Tulis PPTX, Dekripsi PPTX, Buka Kunci Presentasi PPTX, Hapus Proteksi PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Membuka Kunci PPTX menggunakan C++" h2="Gunakan Aspose.Slides for C++ untuk menghapus enkripsi dan proteksi tulis dari file presentasi tanpa Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Menghapus Proteksi dari Presentasi PPTX melalui C++" variant="code" %}}

Aspose.Slides for C++ memungkinkan Anda menghapus enkripsi atau proteksi tulis dari presentasi PPTX. Gunakan `LoadOptions` untuk membuka file terenkripsi, lalu gunakan objek `ProtectionManager` dari kelas `Presentation` untuk memanggil `RemoveEncryption` atau `RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Menghapus Proteksi Kata Sandi dari PPTX menggunakan C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.pptx", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Menghapus Proteksi Tulis dari Presentasi PPTX menggunakan C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.pptx");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menghapus Kata Sandi dari PPTX melalui C++" intro="Ikuti langkah-langkah berikut untuk menghapus proteksi dari presentasi PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPTX dengan kelas `Presentation` dan `LoadOptions` jika diperlukan kata sandi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gunakan objek `ProtectionManager` untuk menghapus proteksi.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil `RemoveEncryption` untuk file terenkripsi atau `RemoveWriteProtection` untuk file yang diproteksi tulis.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan file yang sudah dibuka kuncinya dengan `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Dibuat dengan Aspose.Slides" title="Buka Kunci File PPTX Secara Online" description="Aplikasi Aspose.Slides Unlock gratis dibuat dengan [Aspose.Slides for C++](https://products.aspose.com/slides/id/cpp/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPTX Anda sendiri." button="Buka Aspose.Slides Unlock" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menghapus proteksi sebelum Anda menulis kode.
- Hapus kata sandi atau proteksi tulis dari file PPTX Anda.
- Unduh file yang sudah dibuka kuncinya.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Membuka Kunci" subTitle="Dengan C++, Anda juga dapat menghapus proteksi dari format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
