---
title: Gabungkan PPSX File Menggunakan Python
url: /id/python-net/merge/ppsx/
keywords: Gabungkan PPSX, Gabung PPSX, Gabungkan PPSX, PowerPoint, Presentasi, Python, Aspose
description: Gabungkan beberapa file PPSX dengan Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Gabungkan file PPSX bersama-sama dengan Python" h2="Python API berkecepatan tinggi dan lintas platform yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Gabungkan PPSX dengan Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/id/python-net/) adalah library Python yang kuat untuk membuat dan memanipulasi file presentasi. Selain itu, ini menyediakan cara yang fleksibel untuk menggabungkan beberapa presentasi PPSX. Saat Anda menggabungkan satu presentasi ke presentasi lainnya, Anda secara efektif menggabungkan slide mereka dalam satu presentasi untuk mendapatkan satu file. Aspose.Slides memungkinkan Anda menggabungkan dua presentasi dengan cara yang berbeda. Anda dapat menggabungkan presentasi dengan semua bentuk, gaya, teks, pemformatan, komentar, animasi, dll. tanpa harus khawatir kehilangan kualitas atau data.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Gabungkan file PPSX menggunakan Python" %}}
Untuk menggabungkan presentasi PowerPoint, Anda perlu mengkloning slide dari satu presentasi ke presentasi lainnya.

{{% blocks/products/pf/agp/code-block title="Kode python untuk menggabungkan beberapa PPSX menjadi satu file" offSpacer="true" %}}


```python

import aspose.slides as slides


with slides.Presentation("presentation1.ppsx") as pres1:
    with slides.Presentation("presentation2.ppsx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.ppsx", slides.export.SaveFormat.PPSX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara menggabungkan PPSX menggunakan Aspose.Slides untuk Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk menggabungkan dua file PPSX dan menyimpan hasilnya sebagai PPSX dengan Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/id/python-net/).
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Python Anda.
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buka file sumber PPSX dengan Python.
```
pres1 = slides.Presentation('pres1.ppsx')
pres2 = slides.Presentation('pres2.ppsx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gabungkan file PPSX menggunakan metode [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan presentasi dan dapatkan hasilnya sebagai file PPSX tunggal.
```
pres1.save("result.ppsx", slides.export.SaveFormat.PPSX)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Ekspor PPSX Ke Format Lain yang Didukung" subTitle="Anda juga dapat menggabungkan PPSX dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-pptx/" name="PPSX TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-ppt/" name="PPSX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-pdf/" name="PPSX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-html/" name="PPSX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-png/" name="PPSX TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-bmp/" name="PPSX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-jpg/" name="PPSX TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-fodp/" name="PPSX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-gif/" name="PPSX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-odp/" name="PPSX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-otp/" name="PPSX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-pot/" name="PPSX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-potm/" name="PPSX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-potx/" name="PPSX TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-pps/" name="PPSX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-pptm/" name="PPSX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-svg/" name="PPSX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-tiff/" name="PPSX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/ppsx-to-xps/" name="PPSX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}