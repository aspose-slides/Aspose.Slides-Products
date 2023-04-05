---
title: Gabungkan File OTP Ke PDF Menggunakan Python
url: /id/python-net/merge/otp-to-pdf/
keywords: Gabungkan OTP ke PDF, Gabungkan OTP ke PDF, Gabungkan OTP ke PDF, PowerPoint, Presentasi, PDF, Python, Aspose
description: Gabungkan beberapa file OTP dengan Python.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Gabungkan file OTP ke PDF bersama-sama dengan Python" h2="Python API berkecepatan tinggi dan lintas platform yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Gabungkan OTP ke PDF dengan Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/id/python-net/) adalah library Python yang kuat untuk membuat dan memanipulasi file presentasi. Selain itu, ini menyediakan cara yang fleksibel untuk menggabungkan beberapa presentasi OTP. Saat Anda menggabungkan satu presentasi ke presentasi lainnya, Anda secara efektif menggabungkan slide mereka dalam satu presentasi untuk mendapatkan satu file. Aspose.Slides memungkinkan Anda menggabungkan dua presentasi dengan cara yang berbeda. Anda dapat menggabungkan presentasi dengan semua bentuk, gaya, teks, pemformatan, komentar, animasi, dll. tanpa harus khawatir kehilangan kualitas atau data.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Gabungkan file OTP ke PDF menggunakan Python" %}}
Untuk menggabungkan presentasi PowerPoint, Anda perlu mengkloning slide dari satu presentasi ke presentasi lainnya.

{{% blocks/products/pf/agp/code-block title="Kode python untuk menggabungkan beberapa OTP menjadi satu file PDF" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.otp") as pres1:
    with slides.Presentation("presentation2.otp") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.pdf", slides.export.SaveFormat.PDF)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara menggabungkan OTP ke PDF menggunakan Aspose.Slides for Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk menggabungkan dua file OTP dan menyimpan hasilnya sebagai PDF dengan Python." >}}

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
Buka file sumber OTP dengan Python.
```
pres1 = slides.Presentation('pres1.otp')
pres2 = slides.Presentation('pres2.otp')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gabungkan file OTP menggunakan metode [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods).
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan presentasi dan dapatkan hasilnya sebagai file PDF tunggal.
```
pres1.save("presentation.pdf", slides.export.SaveFormat.PDF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Menggabungkan File PDF Online" sectionDescription="[Cara Menggabungkan PDF dengan Python](https://products.aspose.com/slides/id/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Ekspor OTP Ke Format Lain yang Didukung" subTitle="Anda juga dapat menggabungkan OTP dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-pptx/" name="OTP TO PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-ppt/" name="OTP TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-html/" name="OTP TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-png/" name="OTP TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-bmp/" name="OTP TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-jpg/" name="OTP TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-fodp/" name="OTP TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-gif/" name="OTP TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-odp/" name="OTP TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-pot/" name="OTP TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-potm/" name="OTP TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-potx/" name="OTP TO POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-pps/" name="OTP TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-ppsm/" name="OTP TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-ppsx/" name="OTP TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-pptm/" name="OTP TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-svg/" name="OTP TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-tiff/" name="OTP TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/merge/otp-to-xps/" name="OTP TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}