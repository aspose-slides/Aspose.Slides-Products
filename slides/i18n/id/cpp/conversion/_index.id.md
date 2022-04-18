---
title: Konversi Presentasi Microsoft PowerPoint ke Berbagai Format menggunakan C++
url: /id/cpp/conversion/
description: Konversikan Microsoft PowerPoint Slides ke beberapa file termasuk HTML, PDF, dan format gambar dalam aplikasi berbasis C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi Presentasi PowerPoint Microsoft<sup>®</sup> melalui C++" h2="Kode contoh C++ untuk skenario konversi yang berbeda untuk mengonversi slide ke Gambar, HTML, PDF, dan format lainnya." >}}

{{% blocks/products/pf/feature-page-summary %}}

Proses konversi format Microsoft<sup>®</sup> PowerPoint sederhana dan mudah untuk mengotomatisasi proses menggunakan pustaka C++ PowerPoint. Pengembang dapat meningkatkan kode sumber yang relevan dan mengintegrasikannya dalam aplikasi mereka. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi Antar Format Microsoft PowerPoint" %}}
Interkonversi dokumen Microsoft<sup>®</sup> PowerPoint termasuk PPT, PPTX secara terprogram hanyalah kode dua baris. Muat file menggunakan [Presentation class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) dan memanggil [Save method](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) memiliki file output dan SaveFormat.OutputFormats sebagai parameter.

{{% blocks/products/pf/feature-page-code h3="Kode Konversi C++" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Konversikan File PowerPoint ke PDF" %}}

Mengonversi Microsoft<sup>®</sup> PowerPoint ke PDF adalah skenario umum karena banyaknya berbagi dokumen PDF. Pemrogram dapat mengotomatiskannya dan menyetel setelan konversi PDF yang relevan menggunakan [kelas PdfOptions](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options). Beberapa pengaturan khusus seperti tingkat kompresi teks, kualitas JPEG [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), tingkat kepatuhan PDF [Kepatuhan] (https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), mengonversi slide tersembunyi [ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), slide yang dipilih dan menghasilkan [Kata Sandi] yang terkunci(https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab42606dbbf1956fe00cca45a file PDF yang dilindungi) .

{{% blocks/products/pf/feature-page-code h3="Kode Konversi C++ PowerPoint ke PDF" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Simpan Slide Microsoft PowerPoint Sebagai Gambar" %}}
ketika ada kasus untuk menampilkan konten presentasi di web, maka ada kebutuhan untuk merender file sebagai HTML atau gambar JPG, TIFF, PNG, dll. Proses konversi slide sebagai gambar sederhana. Dapatkan semua slide menggunakan [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) dan ulangi setiap slide satu per satu. Selama setiap iterasi, gunakan [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) untuk gambar slide, lalu simpan ke dalam format gambar yang diperlukan. 

{{% blocks/products/pf/feature-page-code h3="Konversi C++ PowerPoint ke Gambar" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}