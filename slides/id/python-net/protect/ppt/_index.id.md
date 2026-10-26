---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Melindungi File Presentasi PPT dengan Python
url: /id/python-net/protect/ppt/
description: Enkripsi presentasi PPT atau atur proteksi tulis dengan Python.
keywords: proteksi tulis PPT, enkripsi PPT dengan Python, kunci presentasi PPT, lindungi PPT dengan Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Melindungi Presentasi PPT dengan Python" h2="Buat aplikasi Python yang mengenkripsi presentasi atau mengatur proteksi tulis dengan Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Melindungi Presentasi PPT dengan Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/id/python-net/) menyediakan dua mekanisme proteksi yang berbeda. Panggil `ProtectionManager.encrypt` untuk mengenkripsi presentasi PPT sehingga diperlukan kata sandi untuk membukanya. Sebagai alternatif, panggil `ProtectionManager.set_write_protection` untuk mencegah perubahan tanpa mengenkripsi file. Pengguna tetap dapat membuka presentasi yang diproteksi tulis dan menyimpan perubahan ke file lain.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Mengenkripsi Presentasi PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Mengatur Proteksi Tulis pada Presentasi PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Melindungi PPT dengan Python" intro="Ikuti langkah-langkah berikut untuk melindungi file PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file PPT dengan `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gunakan `ProtectionManager.encrypt` untuk mewajibkan kata sandi saat membuka, atau `ProtectionManager.set_write_protection` untuk mencegah perubahan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi yang dilindungi sebagai PPT dengan `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Dibuat dengan Aspose.Slides" title="Lindungi File PPT dengan Kata Sandi Secara Online" description="Aplikasi Aspose.Slides Lock gratis dibuat dengan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/id/python-net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Lock" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides melindungi presentasi sebelum Anda menulis kode.
- Atur kata sandi untuk membuka atau mengedit file PPT Anda.
- Unduh file yang dilindungi.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Proteksi" subTitle="Gunakan Python untuk melindungi format presentasi lain yang didukung." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
