---
title: Konversikan PPS ke PNG dengan Python
url: /id/python-java/conversion/pps-to-png/
keywords: Konversi presentasi Python, konversi presentasi ke Python, Python untuk presentasi, Aspose.Slides Python, konversi PPS ke PNG, pustaka presentasi Python
description: Konversikan PPS ke PNG dengan Python. Gunakan API perpustakaan Python untuk mengonversi file PPS ke PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversikan PPS ke PNG dengan mudah menggunakan Python: Aspose.Slides to the Rescue!" h2="Berikan kehidupan baru ke dalam presentasi Anda dengan Python. Panduan kami memandu Anda mengubah slide PowerPoint yang ada menjadi presentasi Python yang menarik." >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan PPS ke PNG dengan Python" %}}

Bosan bergulat dengan perangkat lunak presentasi yang rumit? Kunjungi [**Aspose.Slides untuk Python melalui Java**](https://products.aspose.com/slides/id/python-java/)! Pustaka canggih ini memberdayakan Anda untuk membuat, mengedit, dan mengonversi presentasi antara berbagai format dengan mudah. Perlu beralih dari PPS ke PNG? Aspose.Slides membuatnya mudah, hanya membutuhkan beberapa baris kode Python.

Sebagai API pemrosesan dokumen mutakhir, **Aspose.Slides untuk Python melalui Java** menawarkan kecepatan konversi yang sangat cepat, memastikan transformasi cepat presentasi PPS Anda ke format PNG. Hilangkan keterbatasan alat tradisional - Aspose.Slides memberi Anda fleksibilitas untuk mengonversi presentasi dari PPS menjadi tidak hanya PNG tetapi juga berbagai format lainnya, sehingga memberdayakan Anda untuk menyesuaikan presentasi Anda dengan sempurna untuk situasi apa pun.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversikan PPS ke PNG menggunakan Python" %}}
Untuk mengonversi PPS ke PNG, Anda perlu membuat Presentasi dari file PPS dan menyimpannya sebagai PNG.

{{% blocks/products/pf/agp/code-block title="Tutorial Python untuk mengubah PPS menjadi PNG" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.pps");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "PNG", File("slide" + str(i) + ".png"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Tutorial Python. Cara mengonversi PPS ke PNG menggunakan Aspose.Slides untuk Python melalui Java API." >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Untuk mengonversi PPS ke PNG menggunakan Aspose.Slides untuk Python melalui Java, Anda perlu mengimpor paket ke dalam skrip Python Anda dan membuat instance kelas Presentation. Kelas Presentasi mewakili dokumen PowerPoint dan menyediakan metode untuk mengakses dan memanipulasi elemen-elemennya." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal [**Aspose.Slides untuk Python melalui Java**](https://products.aspose.com/slides/id/python-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Python Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buka file sumber PPS dengan Python.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil sebagai file PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversikan PPS Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi PPS dan menyimpannya ke format file lain. Lihat semua format yang didukung di bawah" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-pptx/" name="PPS TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-ppt/" name="PPS TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-pdf/" name="PPS TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-html/" name="PPS TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-bmp/" name="PPS TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-jpg/" name="PPS TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-fodp/" name="PPS TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-gif/" name="PPS TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-odp/" name="PPS TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-otp/" name="PPS TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-pot/" name="PPS TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-potm/" name="PPS TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-potx/" name="PPS TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-ppsm/" name="PPS TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-ppsx/" name="PPS TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-pptm/" name="PPS TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-svg/" name="PPS TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-java/conversion/pps-to-tiff/" name="PPS TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}