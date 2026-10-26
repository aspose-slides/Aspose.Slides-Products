---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Membuka Kunci File Presentasi PPTX menggunakan .NET
url: /id/net/unlock/pptx/
description: Kode sumber C# untuk menghapus proteksi kata sandi dari presentasi PPTX.
keywords: Hapus Proteksi Tulis PPTX, Dekripsi PPTX, Buka Kunci Presentasi PPTX, Hapus Proteksi PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Membuka Kunci File PPTX menggunakan C#" h2="Buat aplikasi .NET yang menghapus enkripsi dan proteksi tulis dari presentasi dengan API sisi server." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Menghapus Proteksi dari Presentasi PPTX menggunakan C#" variant="code" %}}

Dengan [Aspose.Slides for .NET](/slides/id/net/), Anda dapat menghapus enkripsi atau proteksi tulis dari presentasi PPTX. Untuk menghapus enkripsi, muat presentasi dengan kata sandi yang benar lalu panggil `ProtectionManager.RemoveEncryption`. Untuk menghapus proteksi tulis, panggil `ProtectionManager.RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Menghapus Enkripsi dari Presentasi PPTX menggunakan C#" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.pptx", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Menghapus Proteksi Tulis dari Presentasi PPTX menggunakan C#" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.pptx");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menghapus Proteksi dari Presentasi PPTX menggunakan C#" intro="Ikuti langkah-langkah berikut untuk menghapus proteksi dari presentasi PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPTX dengan `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Untuk file terenkripsi, berikan kata sandi melalui `LoadOptions.Password` sebelum memuatnya.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil `ProtectionManager.RemoveEncryption` atau `ProtectionManager.RemoveWriteProtection`, sesuai proteksi yang diterapkan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi yang sudah dibuka kuncinya dengan `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Dibuat dengan Aspose.Slides" title="Buka Kunci File PPTX Secara Online" description="Aplikasi Aspose.Slides Unlock gratis dibuat dengan [Aspose.Slides for .NET](https://products.aspose.com/slides/id/net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPTX Anda sendiri." button="Buka Aspose.Slides Unlock" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menghapus proteksi sebelum Anda menulis kode.
- Hapus kata sandi atau proteksi tulis dari file PPTX Anda.
- Unduh file yang sudah dibuka kuncinya.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Membuka Kunci" subTitle="Dengan C#, Anda juga dapat menghapus proteksi dari format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
