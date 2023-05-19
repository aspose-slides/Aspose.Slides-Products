---
title: Cari Teks di File Presentasi PPTX menggunakan C++
url: /id/cpp/search/pptx/
keywords: cari kata dalam PPTX, cari dan ganti teks dalam PPTX, cari teks PPTX Presentasi
description: kode sumber C++ untuk mencari teks dalam Presentasi PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Telusuri Teks PPTX menggunakan C++" h2="Bangun aplikasi C++ Anda sendiri untuk menelusuri dan mengganti teks dalam file presentasi menggunakan API sisi server. Pelajari cara menemukan semua pintu masuk dari kata atau frasa tertentu dalam dokumen presentasi. Cari teks dengan pencocokan data yang tepat dan pencocokan ekspresi reguler." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Cari dan Ganti Teks Presentasi PPTX melalui C++" %}}
Pencarian dokumen dasar dan mengganti teks dalam konten, komentar, catatan slide, atau metadata dengan API Aspose.Slides for C++ dapat dilakukan hanya dengan beberapa baris kode. Gunakan pencocokan ekspresi reguler, cocokkan huruf besar-kecil untuk mencari teks dalam presentasi. Cari teks dalam judul, konten, footer atau header.
{{% blocks/products/pf/agp/code-block title="Cari teks PPTX Presentasi menggunakan C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.pptx", SaveFormat::Pptx);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara Menelusuri Teks dalam PPTX melalui C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk mencari file teks PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat PPTX dengan contoh Presentasi.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gunakan metode [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) untuk mencari dan mengganti teks.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil dalam format PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Demo Langsung Penelusuran PPTX Online" sectionDescription="Cari dan ganti teks dalam konten, komentar, atau metadata dalam dokumen PPTX sekarang juga." >}}

{{< blocks/products/pf/agp/other-supported-section title="Format Pencarian Lain yang Didukung" subTitle="Menggunakan C++, Anda juga dapat menelusuri teks dalam format berikut:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}