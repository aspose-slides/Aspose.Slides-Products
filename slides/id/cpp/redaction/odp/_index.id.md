---
title: Sunting File Presentasi ODP menggunakan C++
url: /id/cpp/redaction/odp/
keywords: Sunting ODP, cari dan ganti teks di ODP, perbarui Presentasi ODP
description: kode sumber C++ untuk menemukan dan mengganti teks dalam Presentasi ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Sunting ODP menggunakan C++" h2="Bangun aplikasi C++ Anda sendiri untuk menemukan dan mengganti teks dalam file presentasi menggunakan API sisi server. Pelajari cara menelusuri dan mengganti teks dalam konten, komentar, atau metadata presentasi ODP" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Redaksi Presentasi ODP melalui C++" %}}
Pencarian dokumen dasar dan mengganti teks dalam konten, komentar, catatan slide, atau metadata dengan API Aspose.Slides for C++ dapat dilakukan hanya dengan beberapa baris kode. Temukan dan ganti teks di PowerPoint dan OpenOffice. Edit teks, komentar, metadata dalam presentasi melalui pencocokan data regexp.
{{% blocks/products/pf/agp/code-block title="Redact Presentasi ODP menggunakan C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.odp", SaveFormat::Odp);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara Redact ODP melalui C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk menyunting file ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat ODP dengan contoh Presentasi.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gunakan metode [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) untuk mencari dan mengganti teks.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil dalam format ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Demo Langsung Redaksi ODP Online" sectionDescription="Cari dan ganti teks dalam konten, komentar, atau metadata dalam dokumen ODP sekarang juga." >}}

{{< blocks/products/pf/agp/other-supported-section title="Format Redact Lain yang Didukung" subTitle="Menggunakan C++, Anda juga dapat menyunting format berikut:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}