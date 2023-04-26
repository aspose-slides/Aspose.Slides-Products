---
title: Lindungi File Presentasi PPT menggunakan C++
url: /id/cpp/protect/ppt/
keywords: Perlindungan Tulis PPT, Enkripsi PPT, Kunci Presentasi PPT, Lindungi PPT
description: kode sumber C++ untuk melindungi Presentasi PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Kunci atau Proteksi Kata Sandi PPT menggunakan C++" h2="Bangun aplikasi C++ Anda sendiri untuk melindungi file presentasi menggunakan API sisi server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Melindungi Presentasi PPT melalui C++" %}}
Dengan menggunakan Aspose.Slides for C++, Anda dapat melindungi presentasi PPT dari pembukaan atau modifikasi dengan menyetel sandi. Kemudian, untuk membuka atau memodifikasi presentasi yang dikunci, pengguna harus memberikan kata sandi.
{{% blocks/products/pf/agp/code-block title="Mengenkripsi Presentasi PPT menggunakan C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.ppt");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Menyetel Write Protection ke Presentasi PPT menggunakan C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.ppt");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara Melindungi Kata Sandi PPT melalui C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk Melindungi file PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat PPT dengan contoh Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Lindungi presentasi menggunakan kelas ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil dalam format PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Format Perlindungan Lain yang Didukung" subTitle="Menggunakan C++, Anda juga dapat memproteksi format berikut:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}