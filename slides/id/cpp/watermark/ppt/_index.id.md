---
title: Tambahkan Watermark ke File Presentasi PPT menggunakan C++
url: /id/cpp/watermark/ppt/
keywords: Tambahkan Tanda Air PPT, Tambahkan Tanda Air Teks PPT, Tambahkan Tanda Air Gambar PPT
description: Kode sumber C++ untuk menambahkan Tanda Air ke Presentasi PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Tambahkan Tanda Air ke Presentasi PPT menggunakan C++" h2="Bangun aplikasi C++ Anda sendiri untuk menyisipkan watermark teks atau gambar ke dalam presentasi PPT, PPTX, atau ODP menggunakan API sisi server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Tambahkan Tanda Air ke Presentasi PPT melalui C++" %}}
Menggunakan Aspose.Slides for C++, Anda dapat menambahkan watermark ke presentasi PPT. Tanda air adalah bagian penting dari presentasi apa pun. Mereka digunakan untuk melindungi konten presentasi agar tidak disalin atau digunakan tanpa izin. Tanda air adalah gambar atau teks yang terlihat atau tidak terlihat yang ditempatkan di atas presentasi. Ini dapat digunakan untuk mengidentifikasi pemilik presentasi dan untuk mencegah penggunaan yang tidak sah. Tanda air juga dapat digunakan untuk menambahkan sentuhan profesional pada presentasi dan membuatnya terlihat lebih halus. 
{{% blocks/products/pf/agp/code-block title="Tambahkan Watermark Teks ke PPT menggunakan C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermark.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Tambahkan Tanda Air Gambar ke Presentasi PPT menggunakan C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto image = presentation->get_Images()->AddImage(:File::ReadAllBytes(u"watermark.png"));

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(image);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"watermark2.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara Menambahkan Tanda Air ke PPT melalui C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk menambahkan watermark teks ke file PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat PPT dengan contoh Presentasi
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Pilih presentasi master
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan tipe bentuk menggunakan metode AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan teks tanda air menggunakan metode AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil dalam format PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Format lain yang Didukung" subTitle="Menggunakan C++, Anda juga dapat menambahkan Watermark ke format berikut:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}