---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversikan JPG ke Image dengan Python
url: /id/python-net/conversion/jpg-to-image/
keywords: JPG ke Image, Konversikan JPG ke Image, Python API, Python Library, JPG, Image
description: Konversikan JPG ke Image dengan Python. Gunakan API pustaka Python untuk mengonversi file JPG ke Image
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversikan JPG ke Image dengan Python" h2="Pustaka Python berkecepatan tinggi dan lintas platform yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan JPG ke Image menggunakan Python" variant="code" %}}

Untuk mengonversi JPG ke Image, Anda perlu membuat Presentasi dari file JPG dan menyimpannya sebagai Image.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode python untuk mengubah JPG menjadi Image" >}}
```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan JPG ke Image dengan Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/id/python-net/) adalah library Python yang andal untuk membuat dan memanipulasi file presentasi. Selain itu, ini memberikan cara yang fleksibel untuk mengonversi JPG ke Image. Dengan menggunakan **Aspose.Slides untuk Python melalui .NET**, pengembang atau aplikasi apa pun dapat mengonversi file JPG ke Image hanya dengan beberapa baris kode Python.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk Python mengekspor file JPG ke format file Image dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi JPG ke Image dan banyak format file lainnya

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara mengonversi JPG ke Image menggunakan Aspose.Slides untuk Python API" intro="Ini adalah langkah-langkah untuk mengonversi JPG ke Image dengan Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/id/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Python Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file sumber JPG dengan Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan hasilnya sebagai file Image.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Dibuat dengan Aspose.Slides" title="Konversi JPG ke Gambar Secara Online" description="Aplikasi Aspose.Slides Conversion gratis dibuat dengan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/id/python-net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file JPG Anda sendiri." button="Buka Aspose.Slides Conversion" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" upload="Letakkan atau unggah file Anda" saveAs="Simpan sebagai" convert="Konversi" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides mengonversi file sebelum Anda menulis kode.
- Unggah file JPG dan simpan sebagai Gambar.
- Unduh hasilnya atau konversi lebih banyak file.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversikan JPG Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi JPG dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah ini" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
