---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversi PPT ke BMP dengan Python
weight: 2210
url: /id/python-net/conversion/ppt-to-bmp/ 
keywords: "Convert, PowerPoint, PPT, BMP, Presentation, Python"
description: Contoh kode untuk konversi PPT ke BMP Python. Gunakan PowerPoint Python API untuk konversi batch file PPT ke file BMP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversi PPT ke BMP dengan Python" h2="Pustaka Python Powerfull PowerPoint untuk mengonversi PPT ke BMP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversi PPT ke BMP dengan Python" %}}

Perlu mengonversi file PPT ke BMP secara terprogram? Menggunakan [*Aspose.Slides untuk Python melalui .NET*](https://products.aspose.com/slides/id/python-net/) pengembang mana pun dapat mengonversi format PPT ke BMP hanya dengan beberapa baris kode Python.

Sebagai API pemrosesan presentasi modern, Aspose.Slides untuk Python membuat BMP dari PPT dengan cepat. Uji kualitas konversi PPT ke BMP langsung di [browser](https://products.aspose.app/slides/conversion) Anda. Perpustakaan Aspose PowerPoint PPTX memungkinkan Anda untuk mengonversi file PPT ke banyak format populer.

Anda dapat menginstal perpustakaan dari [PyPI](https://pypi.org/project/Aspose.Slides/) menggunakan perintah pip berikut:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsol/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Simpan PPT sebagai BMP dengan Python" %}}

Gunakan aplikasi gratis untuk melihat demonstrasi proses konversi PPT ke BMP.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode contoh ini menunjukkan Konversi PPT ke BMP Python" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppt") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.bmp".format(str(slide.slide_number)), drawing.imaging.ImageFormat.bmp)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Bagaimana Mengonversi PPT ke BMP dengan Python" intro="Ini adalah langkah-langkah untuk mengkonversi file PPT ke BMP menggunakan Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPT dengan instance kelas Presentasi{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode `save` sambil menentukan jalur file output & SaveFormat.BMP sebagai parameter{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}File PPT akan disimpan di jalur yang ditentukan{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Persyaratan sistem" intro="Sebelum menjalankan kode sumber contoh konversi Python, pastikan Anda memiliki prasyarat berikut." %}}

- OS berbasis Microsoft Windows atau Linux (lihat [lebih lanjut](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 atau lebih baru
- Aspose.Slides untuk Python direferensikan dalam proyek Anda.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Dibuat dengan Aspose.Slides" title="Konversi PPT ke BMP Secara Online" description="Aplikasi Aspose.Slides Conversion gratis dibuat dengan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/id/python-net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Conversion" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" upload="Letakkan atau unggah file Anda" saveAs="Simpan sebagai" convert="Konversi" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides mengonversi file sebelum Anda menulis kode.
- Unggah file PPT dan simpan sebagai BMP.
- Unduh hasilnya atau konversi lebih banyak file.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi PPT ke banyak format file lainnya. Lihat konversi lain yang didukung di bawah" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-emf/" name="PPT TO EMF" description="Format Metafile yang Ditingkatkan" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-fodp/" name="PPT TO FODP" description="Presentasi XML Datar OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-gif/" name="PPT TO GIF" description="Format Pertukaran Grafis" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/" name="PPT TO HTML" description="Hyper Text Markup Language" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-jpg/" name="PPT TO JPG" description="Gambar JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-odp/" name="PPT TO ODP" description="Format Presentasi OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-otp/" name="PPT TO OTP" description="Format Standar OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-pdf/" name="PPT TO PDF" description="Format Dokumen Portabel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-png/" name="PPT TO PNG" description="Grafik Jaringan Portabel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-pot/" name="PPT TO POT" description="File Template Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-potm/" name="PPT TO POTM" description="File Templat Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-potx/" name="PPT TO POTX" description="Presentasi Template Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-pps/" name="PPT TO PPS" description="Pertunjukan Slide PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Slide Show yang mendukung makro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="Pertunjukan Slide PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="File Presentasi berkemampuan makro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Buka Format presentasi XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-svg/" name="PPT TO SVG" description="Grafik Vektor Skalabel" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-swf/" name="PPT TO SWF" description="Format SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Format Gambar yang Ditandai" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/python-net/conversion/ppt-to-xps/" name="PPT TO XPS" description="Spesifikasi Kertas XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
