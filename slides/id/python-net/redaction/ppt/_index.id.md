---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sensor Teks dalam Presentasi PPT dengan Python
url: /id/python-net/redaction/ppt/
description: Cari dan ganti teks sensitif dalam presentasi PPT dengan Python.
keywords: sensor PPT, cari dan ganti teks di PPT, perbarui presentasi PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sensor Teks dalam Presentasi PPT dengan Python" h2="Bangun aplikasi Python yang mencari dan mengganti teks sensitif dalam presentasi dengan Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sensor Teks dalam Sebuah Presentasi PPT dengan Python" variant="code" %}}

Dengan [Aspose.Slides for Python via .NET](/slides/id/python-net/), Anda dapat mengganti teks sensitif di seluruh presentasi PPT. Gunakan `Presentation.replace_text` dengan `TextSearchOptions` untuk mengontrol pencarian, lalu simpan presentasi yang telah diubah.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Sensor Teks dalam Presentasi PPT – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.ppt") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menyensor Teks dalam Presentasi PPT dengan Python" intro="Ikuti langkah-langkah berikut untuk mengganti teks sensitif dalam presentasi PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file PPT dengan `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gunakan [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) dengan `TextSearchOptions` untuk mengganti teks yang diperlukan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi yang telah diubah dengan `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Dibuat dengan Aspose.Slides" title="Sensor File PPT Secara Online" description="Aplikasi Aspose.Slides Redaction gratis dibuat dengan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/id/python-net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Redaction" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides mencari dan mengganti teks sebelum Anda menulis kode.
- Cari dan ganti teks di file PPT Anda, termasuk dengan ekspresi reguler.
- Unduh file yang telah disensor.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Penyensoran" subTitle="Gunakan Python untuk menyensor teks dalam format presentasi lain yang didukung." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
