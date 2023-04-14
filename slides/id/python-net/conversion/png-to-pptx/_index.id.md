---
title: Konversikan PNG ke PPTX dengan Python
url: /id/python-net/conversion/png-to-pptx/
keywords: Konversi PNG ke PPTX, PNG ke PPTX, PowerPoint, PNG, PPTX, API Python, Perpustakaan Python
description: Konversikan PNG ke PPTX dengan Python. Gunakan API pustaka Python untuk mengonversi gambar PNG ke PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversikan PNG ke PPTX dengan Python" h2="API Python lintas platform yang kuat untuk mengonversi PNG ke PPTX menggunakan kode Python" >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan PNG ke PPTX menggunakan Aspose.Slides" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/id/python-net/) adalah pustaka Python andal yang digunakan untuk membuat, mengonversi, dan memanipulasi presentasi PowerPoint, PDF, dokumen HTML, dan file lainnya. Saat Anda mengonversi PNG ke PPTX, pada dasarnya Anda membuat presentasi PowerPoint yang berisi slide berdasarkan gambar PNG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Konversikan PNG ke PPTX dengan Python" %}}
Menggunakan [**Aspose.Slides untuk Python via .NET**](https://products.aspose.com/slides/id/python-net/), Anda dapat mengonversi gambar PNG menjadi presentasi PowerPoint hanya dengan beberapa baris kode:

{{% blocks/products/pf/agp/code-block title="Kode python untuk mengonversi PNG ke PPTX" offSpacer="true" %}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.png", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Bagaimana mengkonversi PNG ke PPTX dengan Python" >}}


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
Muat gambar PNG yang ingin Anda konversi ke PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan file yang dihasilkan sebagai presentasi PPTX.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Konverter Daring Gratis" sectionDescription="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversi PowerPoint Lainnya yang Didukung" subTitle="Anda juga dapat mengonversi file dalam format lain ke PowerPoint" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}