---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversikan PNG ke PDF dengan Python
url: /id/python-net/conversion/png-to-pdf/
keywords: PNG ke PDF, Konversikan PNG ke PDF, Python API, Python Library, PNG, PDF
description: Konversikan PNG ke PDF dengan Python. Gunakan API pustaka Python untuk mengonversi file PNG ke PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversikan PNG ke PDF dengan Python" h2="Pustaka Python berkecepatan tinggi dan lintas platform yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan PNG ke PDF menggunakan Python" variant="code" %}}

Untuk mengonversi PNG ke PDF, Anda perlu membuat Presentasi dari file PNG dan menyimpannya sebagai PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode python untuk mengubah PNG menjadi PDF" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.png"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    pres.save("index.pdf", slides.export.SaveFormat.PDF)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan PNG ke PDF dengan Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/id/python-net/) adalah library Python yang andal untuk membuat dan memanipulasi file presentasi. Selain itu, ini memberikan cara yang fleksibel untuk mengonversi PNG ke PDF. Dengan menggunakan **Aspose.Slides untuk Python melalui .NET**, pengembang atau aplikasi apa pun dapat mengonversi file PNG ke PDF hanya dengan beberapa baris kode Python.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk Python mengekspor file PNG ke format file PDF dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi PNG ke PDF dan banyak format file lainnya

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara mengonversi PNG ke PDF menggunakan Aspose.Slides untuk Python API" intro="Ini adalah langkah-langkah untuk mengonversi PNG ke PDF dengan Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/id/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Python Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file sumber PNG dengan Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan hasilnya sebagai file PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Konverter Daring Gratis"
  description="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversikan PNG Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi PNG dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah ini" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/png-to-svg/" name="PNG TO SVG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
