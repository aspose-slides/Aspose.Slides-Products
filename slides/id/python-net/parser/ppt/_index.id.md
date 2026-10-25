---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ekstrak Teks dari File PPT dengan Python
url: /id/python-net/parser/ppt/
description: Ekstrak teks dan detail format teks dari presentasi PPT dengan Python.
keywords: parsing PPT dengan Python, parser PPT Python, ekstrak data dari PPT di Python, ekstrak teks dari PPT dengan Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ekstrak Teks dari Presentasi PPT dengan Python" h2="Bangun aplikasi Python yang mengekstrak teks dan detail format teks dari presentasi PowerPoint dengan Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ekstrak Teks dari Presentasi PPT dengan Python – Contoh" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/id/python-net/) menyediakan metode statis [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) pada `SlideUtil`. Metode ini mengembalikan objek `TextFrame` dari seluruh presentasi dan dapat menyertakan teks dari slide master. Contoh berikut mengekstrak teks dan detail font terkait dari presentasi PPT.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Ekstrak Teks dari Presentasi PPT – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.ppt") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Mengekstrak Teks dari PPT dengan Python" intro="Ikuti langkah-langkah berikut untuk mengekstrak teks dari file PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file PPT dengan `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil `SlideUtil.get_all_text_frames` dan tentukan apakah slide master disertakan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telusuri objek `TextFrame` yang dikembalikan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telusuri koleksi `paragraphs` pada setiap bingkai teks.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telusuri koleksi `portions` pada setiap paragraf.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Baca `text` dan properti format dari bagian teks saat ini.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Dibuat dengan Aspose.Slides" title="Ekstrak Teks dan Gambar Secara Online" description="Aplikasi Aspose.Slides Parser gratis dibuat dengan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/id/python-net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Parser" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides membaca file Anda sebelum menulis kode.
- Unggah file PPT dan dapatkan teks serta gambarnya.
- Unduh semuanya sebagai satu arsip ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Parsing Lain yang Didukung" subTitle="Dengan Python, Anda juga dapat mengekstrak teks dari format presentasi lain yang didukung." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
