---
title: Konversi JPG ke PPT dalam C++
url: /id/cpp/conversion/jpg-to-ppt/
keywords: Konversi JPG ke PPT, JPG ke PPT, PowerPoint, JPG, PPT, C++ API, Perpustakaan C++
description: Konversi JPG ke PPT dalam C++. Gunakan C++ library API untuk mengonversi gambar JPG ke PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversi JPG ke PPT dalam C++" h2="C++ API lintas platform yang kuat untuk mengonversi JPG ke PPT menggunakan kode C++" >}}

{{% blocks/products/pf/feature-page-section h2="Konversi JPG ke PPT menggunakan Aspose.Slides" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/id/cpp/) adalah library C++ andal yang digunakan untuk membuat, mengonversi, dan memanipulasi presentasi PowerPoint, PDF, dokumen HTML, dan lainnya file. Saat Anda mengonversi JPG ke PPT, pada dasarnya Anda membuat presentasi PowerPoint yang berisi slide berdasarkan gambar JPG.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Konversi JPG ke PPT dalam C++" %}}
Menggunakan [**Aspose.Slides for C++**](https://products.aspose.com/slides/id/cpp/), Anda dapat mengonversi gambar JPG menjadi presentasi PowerPoint hanya dengan beberapa baris kode:

{{% blocks/products/pf/agp/code-block title="Kode C++ untuk mengonversi JPG ke PPT" offSpacer="true" %}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Bagaimana mengkonversi JPG ke PPT di C++" >}}


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
Muat gambar JPG yang ingin Anda konversi ke PPT.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan file yang dihasilkan sebagai presentasi PPT.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Konverter Daring Gratis" sectionDescription="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversi PowerPoint Lainnya yang Didukung" subTitle="Anda juga dapat mengonversi file dalam format lain ke PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}