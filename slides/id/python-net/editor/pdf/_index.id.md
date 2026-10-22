---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Edit PDF dengan Python
url: /id/python-net/editor/pdf/
keywords: Edit PDF, PDF, API Python, Perpustakaan Python
description: Edit PDF dengan Python. Gunakan API perpustakaan Python untuk mengedit dokumen PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edit PDF dengan Python" h2="Pustaka Python berkecepatan tinggi dan lintas platform untuk mengedit PDF menggunakan kode Python" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PDF dengan Python" variant="code" %}}

Menggunakan [**Aspose.Slides untuk Python via .NET**](https://products.aspose.com/slides/id/python-net/), Anda dapat menambahkan baris teks baru ke dokumen PDF hanya dengan beberapa baris kode.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode python untuk mengedit PDF" >}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    pres.slides.add_from_pdf("document.pdf")

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("document.pdf", slides.export.SaveFormat.PDF)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Edit PDF menggunakan Aspose.Slides" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/id/python-net/) adalah pustaka Python andal yang digunakan untuk memanipulasi dan mengedit presentasi, dokumen PDF, dan file lainnya . Anda dapat mengedit dokumen PDF dengan menambahkan baris teks baru ke dalamnya.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara mengedit PDF dengan Python" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal **Aspose.Slides untuk Python melalui .NET**. Lihat [**Penginstalan**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan perpustakaan sebagai referensi dalam proyek Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buat sebuah instance dari kelas Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat dokumen PDF yang ingin Anda edit.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan baris teks baru.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan file PDF yang diubah.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Mengedit file lain" subTitle="Anda juga dapat mengedit file dalam format lain" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
