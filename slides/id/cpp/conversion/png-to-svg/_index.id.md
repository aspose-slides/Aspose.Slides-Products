---
title: Konversikan PNG ke SVG di C++
url: /id/cpp/conversion/png-to-svg/
keywords: PNG ke SVG, Konversikan PNG ke SVG, C++ API, C++ Library, PNG, SVG
description: Konversikan PNG ke SVG di C++. Gunakan C++ library API untuk mengonversi file PNG menjadi SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversikan PNG ke SVG di C++" h2="Pustaka C++ berkecepatan tinggi dan lintas platform yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan PNG ke SVG di C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/id/cpp/) adalah library C++ yang andal untuk membuat dan memanipulasi file presentasi. Selain itu, ini memberikan cara yang fleksibel untuk mengonversi PNG ke SVG. Menggunakan **Aspose.Slides untuk C++**, pengembang atau aplikasi apa pun dapat mengonversi file PNG ke SVG hanya dengan beberapa baris kode C++.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk C++ mengekspor file PNG ke format file SVG dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi PNG ke SVG dan banyak format file lainnya

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversikan PNG ke SVG menggunakan C++" %}}
Untuk mengonversi PNG ke SVG, Anda perlu membuat Presentasi dari file PNG dan menyimpannya sebagai SVG.

{{% blocks/products/pf/agp/code-block title="Kode C++ untuk mengonversi PNG menjadi SVG" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto fileName = String::Format(u"slide-{0}.svg", index);
    auto fileStream = System::MakeObject<FileStream>(fileName, FileMode::Create, FileAccess::Write);

    auto slide = pres->get_Slides()->idx_get(index);
    slide->WriteAsSvg(fileStream);
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara mengonversi PNG ke SVG menggunakan Aspose.Slides untuk C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk mengonversi PNG ke SVG di C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal [**Aspose.Slides for C++**](https://products.aspose.com/slides/id/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek C++ Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buka file sumber PNG di C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasilnya sebagai file SVG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversikan PNG Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi PNG dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah ini" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/png-to-pdf/" name="PNG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}