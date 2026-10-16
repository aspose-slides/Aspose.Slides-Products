---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversikan HTML ke XML dengan Python
url: /id/python-net/conversion/html-to-xml/
keywords: HTML ke XML, Konversikan HTML ke XML, Python API, Python Library, HTML, XML
description: Konversikan HTML ke XML dengan Python. Gunakan API pustaka Python untuk mengonversi file HTML ke XML
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversikan HTML ke XML dengan Python" h2="Pustaka Python berkecepatan tinggi dan lintas platform yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan HTML ke XML menggunakan Python" variant="code" %}}

Untuk mengonversi HTML ke XML, Anda perlu membuat Presentasi dari file HTML dan menyimpannya sebagai XML.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode python untuk mengubah HTML menjadi XML" >}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("file.html", "rt", encoding="utf-8") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)
    for index, slide in enumerate(pres.slides):

        with open("slide-{index}.xml".format(index = index), "wb") as file:
            slide.write_as_svg(file)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan HTML ke XML dengan Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/id/python-net/) adalah library Python yang andal untuk membuat dan memanipulasi file presentasi. Selain itu, ini memberikan cara yang fleksibel untuk mengonversi HTML ke XML. Dengan menggunakan **Aspose.Slides untuk Python melalui .NET**, pengembang atau aplikasi apa pun dapat mengonversi file HTML ke XML hanya dengan beberapa baris kode Python.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk Python mengekspor file HTML ke format file XML dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi HTML ke XML dan banyak format file lainnya

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara mengonversi HTML ke XML menggunakan Aspose.Slides untuk Python API" intro="Ini adalah langkah-langkah untuk mengonversi HTML ke XML dengan Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/id/python-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Python Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file sumber HTML dengan Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan hasilnya sebagai file XML.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Konverter Daring Gratis"
  description="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversikan HTML Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi HTML dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah ini" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
