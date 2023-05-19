---
title: Cari Teks di File Presentasi ODP menggunakan Python
url: /id/python-net/search/odp/
keywords: cari kata dalam ODP, cari dan ganti teks dalam ODP, cari teks ODP Presentasi
description: kode sumber Python untuk mencari teks dalam Presentasi ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Telusuri Teks ODP menggunakan Python" h2="Bangun aplikasi Python Anda sendiri untuk menelusuri dan mengganti teks dalam file presentasi menggunakan API sisi server. Pelajari cara menemukan semua pintu masuk dari kata atau frasa tertentu dalam dokumen presentasi. Cari teks dengan pencocokan data yang tepat dan pencocokan ekspresi reguler." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Cari dan Ganti Teks Presentasi ODP melalui Python" %}}
Pencarian dokumen dasar dan mengganti teks dalam konten, komentar, catatan slide, atau metadata dengan API Aspose.Slides for Python via .NET dapat dilakukan hanya dengan beberapa baris kode. Gunakan pencocokan ekspresi reguler, cocokkan huruf besar-kecil untuk mencari teks dalam presentasi. Cari teks dalam judul, konten, footer atau header.
{{% blocks/products/pf/agp/code-block title="Cari teks ODP Presentasi menggunakan Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.odp") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara Menelusuri Teks dalam ODP melalui Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk mencari file teks ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat ODP dengan contoh Presentasi.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gunakan metode [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) untuk mencari dan mengganti teks.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil dalam format ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Demo Langsung Penelusuran ODP Online" sectionDescription="Cari dan ganti teks dalam konten, komentar, atau metadata dalam dokumen ODP sekarang juga." >}}

{{< blocks/products/pf/agp/other-supported-section title="Format Pencarian Lain yang Didukung" subTitle="Menggunakan Python, Anda juga dapat menelusuri teks dalam format berikut:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}