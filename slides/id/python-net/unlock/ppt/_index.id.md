---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Membuka Kunci Presentasi PPT dengan Python
url: /id/python-net/unlock/ppt/
description: Hapus enkripsi dan proteksi tulis dari presentasi PPT dengan Python.
keywords: buka kunci PPT, hapus kata sandi dari PPT, hapus enkripsi PPT, hapus proteksi tulis dari PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Membuka Kunci Presentasi PPT dengan Python" h2="Buat aplikasi Python yang menghapus kata sandi pembuka dan pengaturan proteksi tulis dari presentasi PPT dengan Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Menghapus Enkripsi dan Proteksi Tulis dari PPT dengan Python" variant="code" %}}

Dengan [Aspose.Slides for Python via .NET](/slides/id/python-net/), Anda dapat menghapus enkripsi yang mewajibkan kata sandi untuk membuka presentasi PPT, atau menonaktifkan pengaturan proteksi tulisnya. Untuk membuka file terenkripsi, berikan kata sandi saat ini melalui `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Menghapus Enkripsi dari Presentasi PPT – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.ppt", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Menghapus Proteksi Tulis dari Presentasi PPT – Python" >}}
```py
with slides.Presentation("write-protected-presentation.ppt") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menghapus Proteksi dari PPT dengan Python" intro="Ikuti langkah-langkah berikut untuk menghapus proteksi dari presentasi PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Untuk file PPT terenkripsi, atur kata sandi saat ini di `LoadOptions`, lalu buka file dengan `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil `ProtectionManager.remove_encryption` untuk menghapus kata sandi pembuka, atau `ProtectionManager.remove_write_protection` untuk menonaktifkan proteksi tulis.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi hasil dengan `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Dibuat dengan Aspose.Slides" title="Buka Kunci File PPT Secara Online" description="Aplikasi Aspose.Slides Unlock gratis dibuat dengan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/id/python-net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Unlock" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menghapus proteksi sebelum Anda menulis kode.
- Hapus kata sandi atau proteksi tulis dari file PPT Anda.
- Unduh file yang sudah dibuka kuncinya.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Membuka Kunci" subTitle="Gunakan Python untuk menghapus proteksi dari format presentasi lain yang didukung." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
