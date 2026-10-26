---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Cari Teks dalam Presentasi PPTX dengan Python
url: /id/python-net/search/pptx/
description: Cari teks dalam presentasi PPTX dengan Python dan Aspose.Slides.
keywords: cari teks di PPTX, temukan kata di PPTX, cari presentasi PPTX dengan Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Cari Teks dalam Presentasi PPTX dengan Python" h2="Bangun aplikasi Python yang menemukan teks dalam presentasi PowerPoint dengan Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cari Teks dalam Sebuah Presentasi PPTX dengan Python" variant="code" %}}

Dengan [Aspose.Slides for Python via .NET](/slides/id/python-net/), Anda dapat menggunakan [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) untuk menemukan bingkai teks di setiap slide yang berisi string tertentu.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cari Teks dalam Presentasi PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Mencari Teks dalam PPTX dengan Python" intro="Ikuti langkah-langkah berikut untuk mencari teks dalam presentasi PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file PPTX dengan `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telusuri slide dan panggil [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) untuk masing-masing slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Baca properti `text` dari setiap bingkai teks yang cocok.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Dibuat dengan Aspose.Slides" title="Cari Teks dalam File PPTX Secara Online" description="Aplikasi Aspose.Slides Search gratis dibuat dengan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/id/python-net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPTX Anda sendiri." button="Buka Aspose.Slides Search" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menemukan teks sebelum Anda menulis kode.
- Cari teks biasa atau ekspresi reguler di file PPTX Anda.
- Unduh hasil pencarian sebagai file teks.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Pencarian" subTitle="Gunakan Python untuk mencari teks dalam format presentasi lain yang didukung." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
