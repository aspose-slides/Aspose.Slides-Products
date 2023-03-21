---
title: Konversikan Image ke PDF di C++
url: /id/cpp/conversion/image-to-pdf/
keywords: Image ke PDF, Konversikan Image ke PDF, C++ API, C++ Library, Image, PDF
description: Konversikan Image ke PDF di C++. Gunakan C++ library API untuk mengonversi file Image menjadi PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversikan Image ke PDF di C++" h2="Pustaka C++ berkecepatan tinggi dan lintas platform yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan Image ke PDF di C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/id/cpp/) adalah library C++ yang andal untuk membuat dan memanipulasi file presentasi. Selain itu, ini memberikan cara yang fleksibel untuk mengonversi Image ke PDF. Menggunakan **Aspose.Slides untuk C++**, pengembang atau aplikasi apa pun dapat mengonversi file Image ke PDF hanya dengan beberapa baris kode C++.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk C++ mengekspor file Image ke format file PDF dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi Image ke PDF dan banyak format file lainnya

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversikan Image ke PDF menggunakan C++" %}}
Untuk mengonversi Image ke PDF, Anda perlu membuat Presentasi dari file Image dan menyimpannya sebagai PDF.

{{% blocks/products/pf/agp/code-block title="Kode C++ untuk mengonversi Image menjadi PDF" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara mengonversi Image ke PDF menggunakan Aspose.Slides untuk C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk mengonversi Image ke PDF di C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal [**Aspose.Slides for C++**](https://products.aspose.com/slides/id/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek C++ Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buka file sumber Image di C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasilnya sebagai file PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Konverter Daring Gratis" sectionDescription="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversikan Image Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi Image dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah ini" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}