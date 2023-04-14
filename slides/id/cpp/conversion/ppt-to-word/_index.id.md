---
title: Konversikan PPT ke Word dalam C++
url: /id/cpp/conversion/ppt-to-word/
keywords: Konversi PPT ke Word, PPT ke Word, PPT ke DOC, PowerPoint ke Word, C++ API, Perpustakaan C++, CPP
description: Konversikan PPT ke Word dalam C++. Gunakan C++ library API untuk mengonversi PowerPoint ke Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversikan PPT ke Word dalam C++" h2="C++ API lintas platform yang kuat untuk mengonversi PowerPoint ke Word menggunakan kode C++ tanpa Microsoft PowerPoint atau Office" >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan PowerPoint ke Word menggunakan Aspose.Slides dan Aspose.Words" %}}

[**Aspose.Slides untuk C++**](https://products.aspose.com/slides/id/cpp/) dan [**Aspose.Words untuk C++**](https://products.aspose.com/ kata/cpp/) adalah pustaka C++ yang kuat yang digunakan untuk memanipulasi dan mengonversi presentasi PowerPoint, dokumen Word, dan file lainnya. Saat Anda mengonversi PowerPoint ke Word, pada dasarnya Anda memindahkan konten slide presentasi ke halaman dalam dokumen Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Konversikan PowerPoint ke Word dalam C++" %}}
Anda dapat mengonversi PPT ke Word dengan cepat hanya dengan beberapa baris kode

{{% blocks/products/pf/agp/code-block title="Kode C++ untuk mengonversi PowerPoint ke Word" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Bagaimana mengkonversi PPT ke Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instal **Aspose.Slides untuk C++** dan **Aspose.Words untuk C++** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buat instance kelas Presentation dan kelas Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat presentasi PPT yang ingin Anda konversi ke Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hasilkan gambar dan teks berdasarkan konten slide.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan dokumen Word yang dihasilkan.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Konverter Daring Gratis" sectionDescription="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi PowerPoint ke file dalam format lain" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}