---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Melindungi File Presentasi ODP menggunakan .NET
url: /id/net/protect/odp/
description: Kode sumber C# untuk melindungi presentasi ODP dengan kata sandi.
keywords: Proteksi Tulis ODP, Enkripsi ODP, Kunci Presentasi ODP, Lindungi ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Mengunci atau Melindungi File ODP dengan Kata Sandi menggunakan C#" h2="Buat aplikasi .NET yang mengenkripsi presentasi dan membatasi perubahan dengan API sisi server." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Melindungi Presentasi ODP menggunakan C#" variant="code" %}}

Dengan [Aspose.Slides for .NET](/slides/id/net/), Anda dapat mengenkripsi presentasi ODP atau membatasi perubahannya dengan kata sandi. Membuka presentasi yang dienkripsi dengan `ProtectionManager.Encrypt` memerlukan kata sandi. Gunakan `ProtectionManager.SetWriteProtection` agar presentasi tetap dapat dibuka tetapi perubahannya dibatasi.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mengenkripsi Presentasi ODP menggunakan C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Mengatur Proteksi Tulis untuk Presentasi ODP menggunakan C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Melindungi Presentasi ODP dengan Kata Sandi menggunakan C#" intro="Ikuti langkah-langkah berikut untuk melindungi presentasi ODP dengan kata sandi." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file ODP dengan `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enkripsi presentasi dengan `ProtectionManager.Encrypt` atau batasi perubahan dengan `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan file yang dilindungi dengan `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Dibuat dengan Aspose.Slides" title="Lindungi File ODP dengan Kata Sandi Secara Online" description="Aplikasi Aspose.Slides Lock gratis dibuat dengan [Aspose.Slides for .NET](https://products.aspose.com/slides/id/net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file ODP Anda sendiri." button="Buka Aspose.Slides Lock" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides melindungi presentasi sebelum Anda menulis kode.
- Atur kata sandi untuk membuka atau mengedit file ODP Anda.
- Unduh file yang dilindungi.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Proteksi" subTitle="Dengan C#, Anda juga dapat melindungi format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
