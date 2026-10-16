---
lastmod: 2024-04-16
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversikan FODP ke JPG dengan Python
url: /id/python-java/conversion/fodp-to-jpg/
keywords: Konversi presentasi Python, konversi presentasi ke Python, Python untuk presentasi, Aspose.Slides Python, konversi FODP ke JPG, pustaka presentasi Python
description: Konversikan FODP ke JPG dengan Python. Gunakan API perpustakaan Python untuk mengonversi file FODP ke JPG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversikan FODP ke JPG dengan mudah menggunakan Python: Aspose.Slides to the Rescue!" h2="Berikan kehidupan baru ke dalam presentasi Anda dengan Python. Panduan kami memandu Anda mengubah slide PowerPoint yang ada menjadi presentasi Python yang menarik." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan FODP ke JPG menggunakan Python" variant="code" %}}

Untuk mengonversi FODP ke JPG, Anda perlu membuat Presentasi dari file FODP dan menyimpannya sebagai JPG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tutorial Python untuk mengubah FODP menjadi JPG" >}}
```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.fodp");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "JPEG", File("slide" + str(i) + ".jpg"))

jpype.shutdownJVM()
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan FODP ke JPG dengan Python" %}}

Bosan bergulat dengan perangkat lunak presentasi yang rumit? Kunjungi [**Aspose.Slides untuk Python melalui Java**](https://products.aspose.com/slides/id/python-java/)! Pustaka canggih ini memberdayakan Anda untuk membuat, mengedit, dan mengonversi presentasi antara berbagai format dengan mudah. Perlu beralih dari FODP ke JPG? Aspose.Slides membuatnya mudah, hanya membutuhkan beberapa baris kode Python.

Sebagai API pemrosesan dokumen mutakhir, **Aspose.Slides untuk Python melalui Java** menawarkan kecepatan konversi yang sangat cepat, memastikan transformasi cepat presentasi FODP Anda ke format JPG. Hilangkan keterbatasan alat tradisional - Aspose.Slides memberi Anda fleksibilitas untuk mengonversi presentasi dari FODP menjadi tidak hanya JPG tetapi juga berbagai format lainnya, sehingga memberdayakan Anda untuk menyesuaikan presentasi Anda dengan sempurna untuk situasi apa pun.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Tutorial Python. Cara mengonversi FODP ke JPG menggunakan Aspose.Slides untuk Python melalui Java API." intro="Untuk mengonversi FODP ke JPG menggunakan Aspose.Slides untuk Python melalui Java, Anda perlu mengimpor paket ke dalam skrip Python Anda dan membuat instance kelas Presentation. Kelas Presentasi mewakili dokumen PowerPoint dan menyediakan metode untuk mengakses dan memanipulasi elemen-elemennya." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal [**Aspose.Slides untuk Python melalui Java**](https://products.aspose.com/slides/id/python-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Python Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file sumber FODP dengan Python.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan hasil sebagai file JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversikan FODP Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi FODP dan menyimpannya ke format file lain. Lihat semua format yang didukung di bawah" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-png/" name="FODP TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-bmp/" name="FODP TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-svg/" name="FODP TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
