---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Lihat atau Edit Metadata ODP dengan Python
url: /id/python-net/metadata/odp/
description: Lihat dan edit properti metadata bawaan dan kustom dalam file ODP dengan Python.
keywords: edit metadata ODP, lihat metadata ODP, edit properti ODP, lihat properti ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lihat dan Edit Metadata ODP dengan Python" h2="Bangun aplikasi Python yang membaca dan mengubah properti bawaan dan kustom presentasi dengan Aspose.Slides." related="FODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Lihat dan Ubah Metadata ODP dengan Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/id/python-net/) memungkinkan Anda membaca dan memperbarui metadata bawaan, serta menambahkan, memperbarui, atau menghapus properti dokumen kustom dalam presentasi ODP. Akses objek [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) melalui `Presentation.document_properties`, ubah, lalu simpan presentasi dalam format ODP.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Perbarui Properti Bawaan ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Tambah dan Hapus Properti Kustom ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Mengedit Metadata ODP dengan Python" intro="Ikuti langkah-langkah berikut untuk mengedit metadata dalam file ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file ODP dengan `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Akses objek `IDocumentProperties` melalui `Presentation.document_properties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Perbarui properti bawaan atau gunakan `set_custom_property_value` dan `remove_custom_property` untuk properti kustom.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi dengan `Presentation.save` dan `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Dibuat dengan Aspose.Slides" title="Lihat dan Edit Metadata ODP Secara Online" description="Aplikasi Aspose.Slides Metadata gratis dibuat dengan [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/id/python-net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file ODP Anda sendiri." button="Buka Aspose.Slides Metadata" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides membaca dan menulis properti sebelum menulis kode.
- Lihat dan edit properti bawaan dan kustom file ODP Anda.
- Simpan dan unduh file yang diperbarui.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Metadata Lain yang Didukung" subTitle="Dengan Python, Anda juga dapat mengelola metadata format presentasi lain yang didukung." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/python-net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
