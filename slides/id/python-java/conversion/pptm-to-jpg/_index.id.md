---
title: Konversikan PPTM ke JPG dengan Python
url: /id/python-java/conversion/pptm-to-jpg/
keywords: Konversi presentasi Python, konversi presentasi ke Python, Python untuk presentasi, Aspose.Slides Python, konversi PPTM ke JPG, pustaka presentasi Python
description: Konversikan PPTM ke JPG dengan Python. Gunakan API perpustakaan Python untuk mengonversi file PPTM ke JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversikan PPTM ke JPG dengan mudah menggunakan Python: Aspose.Slides to the Rescue!" h2="Berikan kehidupan baru ke dalam presentasi Anda dengan Python. Panduan kami memandu Anda mengubah slide PowerPoint yang ada menjadi presentasi Python yang menarik." >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan PPTM ke JPG dengan Python" %}}

Bosan bergulat dengan perangkat lunak presentasi yang rumit? Kunjungi [**Aspose.Slides untuk Python melalui Java**](https://products.aspose.com/slides/id/python-java/)! Pustaka canggih ini memberdayakan Anda untuk membuat, mengedit, dan mengonversi presentasi antara berbagai format dengan mudah. Perlu beralih dari PPTM ke JPG? Aspose.Slides membuatnya mudah, hanya membutuhkan beberapa baris kode Python.

Sebagai API pemrosesan dokumen mutakhir, **Aspose.Slides untuk Python melalui Java** menawarkan kecepatan konversi yang sangat cepat, memastikan transformasi cepat presentasi PPTM Anda ke format JPG. Hilangkan keterbatasan alat tradisional - Aspose.Slides memberi Anda fleksibilitas untuk mengonversi presentasi dari PPTM menjadi tidak hanya JPG tetapi juga berbagai format lainnya, sehingga memberdayakan Anda untuk menyesuaikan presentasi Anda dengan sempurna untuk situasi apa pun.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversikan PPTM ke JPG menggunakan Python" %}}
Untuk mengonversi PPTM ke JPG, Anda perlu membuat Presentasi dari file PPTM dan menyimpannya sebagai JPG.

{{% blocks/products/pf/agp/code-block title="Tutorial Python untuk mengubah PPTM menjadi JPG" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.pptm");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Tutorial Python. Cara mengonversi PPTM ke JPG menggunakan Aspose.Slides untuk Python melalui Java API." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Untuk mengonversi PPTM ke JPG menggunakan Aspose.Slides untuk Python melalui Java, Anda perlu mengimpor paket ke dalam skrip Python Anda dan membuat instance kelas Presentation. Kelas Presentasi mewakili dokumen PowerPoint dan menyediakan metode untuk mengakses dan memanipulasi elemen-elemennya." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal [**Aspose.Slides untuk Python melalui Java**](https://products.aspose.com/slides/id/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Python Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buka file sumber PPTM dengan Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil sebagai file JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversikan PPTM Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi PPTM dan menyimpannya ke format file lain. Lihat semua format yang didukung di bawah" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-pptx/" name="PPTM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-ppt/" name="PPTM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-pdf/" name="PPTM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-html/" name="PPTM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-png/" name="PPTM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-bmp/" name="PPTM TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-fodp/" name="PPTM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-gif/" name="PPTM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-odp/" name="PPTM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-otp/" name="PPTM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-pot/" name="PPTM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-potm/" name="PPTM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-potx/" name="PPTM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-pps/" name="PPTM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-svg/" name="PPTM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}