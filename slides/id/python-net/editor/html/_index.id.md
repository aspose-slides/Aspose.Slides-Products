---
title: Edit HTML dengan Python
url: /id/python-net/editor/html/
keywords: Edit HTML, HTML, API Python, Perpustakaan Python
description: Edit HTML dengan Python. Gunakan API perpustakaan Python untuk mengedit file HTML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Edit HTML dengan Python" h2="Pustaka Python berkecepatan tinggi dan lintas platform untuk mengedit HTML menggunakan kode Python" >}}

{{% blocks/products/pf/feature-page-section h2="Edit HTML menggunakan Aspose.Slides" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/id/python-net/) adalah library Python andal yang digunakan untuk memanipulasi dan mengedit presentasi, dokumen HTML, dan file lainnya . Anda dapat mengedit dokumen HTML dengan menambahkan baris teks baru ke dalamnya. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Edit HTML dengan Python" %}}
Menggunakan [**Aspose.Slides untuk Python via .NET**](https://products.aspose.com/slides/id/python-net/), Anda dapat menambahkan baris teks baru ke dokumen HTML hanya dengan beberapa baris kode.

{{% blocks/products/pf/agp/code-block title="Kode python untuk mengedit HTML" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    with open("page.html", "rt") as stream:
        data = stream.read()
    pres.slides.add_from_html(data)

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("page.html", slides.export.SaveFormat.HTML5)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cara mengedit HTML dengan Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instal **Aspose.Slides untuk Python melalui .NET**. Lihat [**Penginstalan**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan perpustakaan sebagai referensi dalam proyek Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buat sebuah instance dari kelas Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat dokumen HTML yang ingin Anda edit.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan baris teks baru.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan file HTML yang diubah.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Mengedit file lain" subTitle="Anda juga dapat mengedit file dalam format lain" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}