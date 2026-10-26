---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Melindungi Presentasi PPTX menggunakan C++
url: /id/cpp/protect/pptx/
description: Lindungi presentasi PPTX di C++. Gunakan Aspose.Slides for C++ untuk mengenkripsi file dan mengatur proteksi tulis.
keywords: Proteksi Tulis PPTX, Enkripsi PPTX, Kunci Presentasi PPTX, Lindungi PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Mengunci atau Melindungi PPTX dengan Kata Sandi menggunakan C++" h2="Gunakan Aspose.Slides for C++ untuk mengenkripsi presentasi dan mengatur proteksi tulis tanpa Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Melindungi Presentasi PPTX dengan C++" variant="code" %}}

Aspose.Slides for C++ memungkinkan Anda melindungi presentasi PPTX agar tidak dibuka atau diubah. Gunakan objek `ProtectionManager` dari kelas `Presentation` untuk mengenkripsi file dengan `Encrypt` atau membatasi pengeditan dengan `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mengenkripsi Presentasi PPTX menggunakan C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Mengatur Proteksi Tulis untuk Presentasi PPTX menggunakan C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Melindungi PPTX dengan Kata Sandi melalui C++" intro="Ikuti langkah-langkah berikut untuk melindungi presentasi PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPTX dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lindungi presentasi dengan objek `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gunakan `Encrypt` untuk proteksi kata sandi atau `SetWriteProtection` untuk proteksi tulis.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan file yang dilindungi dengan `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Dibuat dengan Aspose.Slides" title="Lindungi File PPTX dengan Kata Sandi Secara Online" description="Aplikasi Aspose.Slides Lock gratis dibuat dengan [Aspose.Slides for C++](https://products.aspose.com/slides/id/cpp/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPTX Anda sendiri." button="Buka Aspose.Slides Lock" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides melindungi presentasi sebelum Anda menulis kode.
- Atur kata sandi untuk membuka atau mengedit file PPTX Anda.
- Unduh file yang dilindungi.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Proteksi" subTitle="Dengan C++, Anda juga dapat melindungi format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
