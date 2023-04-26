---
title: Lindungi File Presentasi PPTX menggunakan Python
url: /id/python-net/protect/pptx/
keywords: Perlindungan Tulis PPTX, Enkripsi PPTX, Kunci Presentasi PPTX, Lindungi PPTX
description: kode sumber Python untuk melindungi Presentasi PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Kunci atau Proteksi Kata Sandi PPTX menggunakan Python" h2="Bangun aplikasi Python Anda sendiri untuk melindungi file presentasi menggunakan API sisi server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Melindungi Presentasi PPTX melalui Python" %}}
Dengan menggunakan Aspose.Slides for Python via .NET, Anda dapat melindungi presentasi PPTX dari pembukaan atau modifikasi dengan menyetel sandi. Kemudian, untuk membuka atau memodifikasi presentasi yang dikunci, pengguna harus memberikan kata sandi.
{{% blocks/products/pf/agp/code-block title="Mengenkripsi Presentasi PPTX menggunakan Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.pptx") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Menyetel Write Protection ke Presentasi PPTX menggunakan Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.pptx") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara Melindungi Kata Sandi PPTX melalui Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk Melindungi file PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat PPTX dengan contoh Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lindungi presentasi menggunakan kelas ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil dalam format PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Format Perlindungan Lain yang Didukung" subTitle="Menggunakan Python, Anda juga dapat memproteksi format berikut:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}