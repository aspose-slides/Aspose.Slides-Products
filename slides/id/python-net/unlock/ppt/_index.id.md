---
title: Buka Kunci File Presentasi PPT menggunakan Python
url: /id/python-net/unlock/ppt/
keywords: Hapus Write Protection PPT, Mendekripsi PPT, Buka Presentasi PPT, Unprotect PPT
description: kode sumber Python untuk menghapus perlindungan dari Presentasi PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Buka kunci PPT menggunakan Python" h2="Bangun aplikasi Python Anda sendiri untuk menghapus kata sandi dari PowerPoint dan mendekripsi file presentasi menggunakan API sisi server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Menghapus Enkripsi dari Presentasi PPT melalui Python" %}}
Dengan menggunakan Aspose.Slides for Python via .NET, Anda dapat menghapus enkripsi atau perlindungan sandi pada presentasi PPT. Dengan cara ini, pengguna dapat mengakses atau memodifikasi presentasi PPT tanpa batasan.
{{% blocks/products/pf/agp/code-block title="Menonaktifkan Perlindungan Kata Sandi dari PPT menggunakan Python" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.ppt", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Menghapus Write Protection dari Presentasi PPT menggunakan Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.ppt") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.ppt", slides.export.SaveFormat.PPT)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara Menghapus Kata Sandi Dari PPT melalui Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk menghapus perlindungan dari file PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat PPT dengan contoh Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hapus Write Protection menggunakan kelas ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil dalam format PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Format lain yang Didukung" subTitle="Menggunakan Python, Anda juga dapat menghapus perlindungan dari format berikut:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/python-net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}