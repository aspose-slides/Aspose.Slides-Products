---
title: Menggabungkan HTML ke Gambar di C++
url: /id/cpp/merger/html-to-image/
keywords: Gabungkan HTML ke gambar, HTML ke gambar, Gabung HTML, Gabungkan HTML, Gambar, C++ API, Perpustakaan C++
description: Menggabungkan HTML ke gambar dalam C++. Gunakan C++ library API untuk menggabungkan HTML ke gambar
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Menggabungkan gambar dalam C++" h2="Pustaka C++ berkecepatan tinggi dan lintas platform untuk menggabungkan HTML ke gambar menggunakan kode C++" >}}

{{% blocks/products/pf/feature-page-section h2="Menggabungkan HTML ke gambar menggunakan Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/id/cpp/) adalah library C++ andal yang digunakan untuk menggabungkan dan memanipulasi presentasi, dokumen HTML, dan file lainnya. Saat Anda menggabungkan HTML ke gambar, Anda secara efektif menggabungkan konten dalam dokumen HTML untuk mendapatkan satu gambar. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Menggabungkan HTML ke gambar dalam C++" %}}
Menggunakan [**Aspose.Slides for C++**](https://products.aspose.com/slides/id/cpp/), Anda dapat menggabungkan file gambar dengan cepat hanya dengan beberapa baris kode

{{% blocks/products/pf/agp/code-block title="Kode C++ untuk menggabungkan HTML ke gambar" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromHtml(htmlText1);
pres->get_Slides()->AddFromHtml(htmlText2);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.png", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Png());
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Cara menggabungkan HTML ke gambar di C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instal **Aspose.Slides untuk C++**. Lihat [**Penginstalan**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan perpustakaan sebagai referensi dalam proyek Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buat sebuah instance dari kelas Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Muat dokumen HTML yang ingin Anda gabungkan.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan gambar yang dihasilkan.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="Menggabungkan File PDF Online" sectionDescription="[Cara Menggabungkan PDF dengan Python](https://products.aspose.com/slides/id/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Menggabungkan file lain" subTitle="Anda juga dapat menggabungkan file dalam format lain untuk mendapatkan satu file" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
    
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}