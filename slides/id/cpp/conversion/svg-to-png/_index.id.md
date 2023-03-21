---
title: Konversikan SVG ke PNG di C++
url: /id/cpp/conversion/svg-to-png/
keywords: SVG ke PNG, Konversikan SVG ke PNG, C++ API, C++ Library, SVG, PNG
description: Konversikan SVG ke PNG di C++. Gunakan C++ library API untuk mengonversi file SVG menjadi PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversikan SVG ke PNG di C++" h2="Pustaka C++ berkecepatan tinggi dan lintas platform yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan SVG ke PNG di C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/id/cpp/) adalah library C++ yang andal untuk membuat dan memanipulasi file presentasi. Selain itu, ini memberikan cara yang fleksibel untuk mengonversi SVG ke PNG. Menggunakan **Aspose.Slides untuk C++**, pengembang atau aplikasi apa pun dapat mengonversi file SVG ke PNG hanya dengan beberapa baris kode C++.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk C++ mengekspor file SVG ke format file PNG dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi SVG ke PNG dan banyak format file lainnya

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversikan SVG ke PNG menggunakan C++" %}}
Untuk mengonversi SVG ke PNG, Anda perlu membuat Presentasi dari file SVG dan menyimpannya sebagai PNG.

{{% blocks/products/pf/agp/code-block title="Kode C++ untuk mengonversi SVG menjadi PNG" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
System::String svgContent = System::IO::File::ReadAllText(svgPath);
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(svgContent);
System::SharedPtr<IPPImage> ppImage = pres->get_Images()->AddImage(svgImage);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(Aspose::Slides::ShapeType::Rectangle, 0.0f, 0.0f, 
    static_cast<float>(ppImage->get_Width()), 
    static_cast<float>(ppImage->get_Height()), ppImage);
for (int32_t i = 0; i < pres->get_Slides()->get_Count(); i++)
{
    // Control hidden slides (do not render hidden slides)
    if (pres->get_Slides()->idx_get(i)->get_Hidden())
    {
        continue;
    }
    
    // Convert slide to a Bitmap object
    System::SharedPtr<Bitmap> bmp = pres->get_Slides()->idx_get(i)->GetThumbnail(2.f, 2.f);

    // Create file name for an image
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".png");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Png());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara mengonversi SVG ke PNG menggunakan Aspose.Slides untuk C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk mengonversi SVG ke PNG di C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal [**Aspose.Slides for C++**](https://products.aspose.com/slides/id/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek C++ Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buka file sumber SVG di C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasilnya sebagai file PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Konverter Daring Gratis" sectionDescription="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversikan SVG Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi SVG dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah ini" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}