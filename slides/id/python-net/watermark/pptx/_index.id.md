---
title: Tambahkan Watermark ke File Presentasi PPTX menggunakan Python
url: /id/python-net/watermark/pptx/
keywords: Tambahkan Tanda Air PPTX, Tambahkan Tanda Air Teks PPTX, Tambahkan Tanda Air Gambar PPTX
description: Kode sumber Python untuk menambahkan Tanda Air ke Presentasi PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Tambahkan Tanda Air ke Presentasi PPTX menggunakan Python" h2="Bangun aplikasi Python Anda sendiri untuk menyisipkan watermark teks atau gambar ke dalam presentasi PPT, PPTX, atau ODP menggunakan API sisi server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Tambahkan Tanda Air ke Presentasi PPTX melalui Python" %}}
Menggunakan Aspose.Slides for Python via .NET, Anda dapat menambahkan watermark ke presentasi PPTX. Tanda air adalah bagian penting dari presentasi apa pun. Mereka digunakan untuk melindungi konten presentasi agar tidak disalin atau digunakan tanpa izin. Tanda air adalah gambar atau teks yang terlihat atau tidak terlihat yang ditempatkan di atas presentasi. Ini dapat digunakan untuk mengidentifikasi pemilik presentasi dan untuk mencegah penggunaan yang tidak sah. Tanda air juga dapat digunakan untuk menambahkan sentuhan profesional pada presentasi dan membuatnya terlihat lebih halus. 
{{% blocks/products/pf/agp/code-block title="Tambahkan Watermark Teks ke PPTX menggunakan Python" offSpacer="true" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as draw

with slides.Presentation() as pres:
    master = pres.masters[0]

    watermarkShape = master.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 0, 0, 100, 100)
    watermarkTextFrame = watermarkShape.add_text_frame("Watermark")

    # Lock Watermark from Editing
    watermarkShape.shape_lock.select_locked = True
    watermarkShape.shape_lock.size_locked = True
    watermarkShape.shape_lock.text_locked = True
    watermarkShape.shape_lock.position_locked = True
    watermarkShape.shape_lock.grouping_locked = True
    
    # Set Text Watermark Transparency
    watermarkPortion = watermarkTextFrame.paragraphs[0].portions[0]
    watermarkPortion.portion_format.fill_format.fill_type = slides.FillType.SOLID
    watermarkPortion.portion_format.fill_format.solid_fill_color.color = draw.Color.from_argb(150, 200, 200, 200)
    
    # Set Font Size of Text Watermark
    watermarkPortion.portion_format.font_height = 16

    pres.save("watermark.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Tambahkan Tanda Air Gambar ke Presentasi PPTX menggunakan Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation() as presentation:
    with open("image1.png", "rb") as fs:
        data = fs.read()
    image = presentation.images.add_image(data)

    master = presentation.masters[0]
    watermarkShape = master.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 0, 0, image.width, image.height)
    
    watermarkShape.fill_format.fill_type = slides.FillType.PICTURE
    watermarkShape.fill_format.picture_fill_format.picture.image = image
    watermarkShape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH

    presentation.save("watermark2.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara Menambahkan Tanda Air ke PPTX melalui Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk menambahkan watermark teks ke file PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat PPTX dengan contoh Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Pilih presentasi master
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan tipe bentuk menggunakan metode AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan teks tanda air menggunakan metode AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil dalam format PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Format lain yang Didukung" subTitle="Menggunakan Python, Anda juga dapat menambahkan Watermark ke format berikut:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}