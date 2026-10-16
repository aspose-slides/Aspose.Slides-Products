---
lastmod: 2024-04-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversikan POTX ke PNG dengan Python
url: /id/python-java/conversion/potx-to-png/
keywords: Konversi presentasi Python, konversi presentasi ke Python, Python untuk presentasi, Aspose.Slides Python, konversi POTX ke PNG, pustaka presentasi Python
description: Konversikan POTX ke PNG dengan Python. Gunakan API perpustakaan Python untuk mengonversi file POTX ke PNG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversikan POTX ke PNG dengan mudah menggunakan Python: Aspose.Slides to the Rescue!" h2="Berikan kehidupan baru ke dalam presentasi Anda dengan Python. Panduan kami memandu Anda mengubah slide PowerPoint yang ada menjadi presentasi Python yang menarik." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan POTX ke PNG menggunakan Python" variant="code" %}}

Untuk mengonversi POTX ke PNG, Anda perlu membuat Presentasi dari file POTX dan menyimpannya sebagai PNG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tutorial Python untuk mengubah POTX menjadi PNG" >}}
```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.potx");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "PNG", File("slide" + str(i) + ".png"))

jpype.shutdownJVM()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan POTX ke PNG dengan Python" %}}

Bosan bergulat dengan perangkat lunak presentasi yang rumit? Kunjungi [**Aspose.Slides untuk Python melalui Java**](https://products.aspose.com/slides/id/python-java/)! Pustaka canggih ini memberdayakan Anda untuk membuat, mengedit, dan mengonversi presentasi antara berbagai format dengan mudah. Perlu beralih dari POTX ke PNG? Aspose.Slides membuatnya mudah, hanya membutuhkan beberapa baris kode Python.

Sebagai API pemrosesan dokumen mutakhir, **Aspose.Slides untuk Python melalui Java** menawarkan kecepatan konversi yang sangat cepat, memastikan transformasi cepat presentasi POTX Anda ke format PNG. Hilangkan keterbatasan alat tradisional - Aspose.Slides memberi Anda fleksibilitas untuk mengonversi presentasi dari POTX menjadi tidak hanya PNG tetapi juga berbagai format lainnya, sehingga memberdayakan Anda untuk menyesuaikan presentasi Anda dengan sempurna untuk situasi apa pun.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Tutorial Python. Cara mengonversi POTX ke PNG menggunakan Aspose.Slides untuk Python melalui Java API." intro="Untuk mengonversi POTX ke PNG menggunakan Aspose.Slides untuk Python melalui Java, Anda perlu mengimpor paket ke dalam skrip Python Anda dan membuat instance kelas Presentation. Kelas Presentasi mewakili dokumen PowerPoint dan menyediakan metode untuk mengakses dan memanipulasi elemen-elemennya." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal [**Aspose.Slides untuk Python melalui Java**](https://products.aspose.com/slides/id/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Python Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file sumber POTX dengan Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan hasil sebagai file PNG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversikan POTX Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi POTX dan menyimpannya ke format file lain. Lihat semua format yang didukung di bawah" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-pptx/" name="POTX TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-ppt/" name="POTX TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-pdf/" name="POTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-html/" name="POTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-bmp/" name="POTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-jpg/" name="POTX TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-fodp/" name="POTX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-gif/" name="POTX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-odp/" name="POTX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-otp/" name="POTX TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-pot/" name="POTX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-potm/" name="POTX TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-pps/" name="POTX TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-ppsm/" name="POTX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-ppsx/" name="POTX TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-pptm/" name="POTX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-svg/" name="POTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/potx-to-tiff/" name="POTX TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
