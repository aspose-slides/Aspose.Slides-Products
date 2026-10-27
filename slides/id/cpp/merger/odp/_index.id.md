---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Gabungkan File ODP melalui C++
weight: 7420
url: /id/cpp/merger/odp/ 
description: Contoh kode C++ untuk menggabungkan dokumen ODP pada C++ Runtime Environment untuk Windows 32 bit, Windows 64 bit dan Linux 64 bit.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Gabungkan File ODP menggunakan C++" h2="Penggabungan dokumen ODP menggunakan C++ API sisi server."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cara Menggabungkan File ODP Menggunakan C++" %}}

Untuk menggabungkan file ODP, kami akan menggunakan
 [Aspose.Slides untuk C++](https://products.aspose.com/slides/id/cpp/)
 API yang merupakan API penggabungan dokumen yang kaya fitur, kuat, dan mudah digunakan untuk platform C++. Bisa langsung download versi terbarunya, tinggal buka
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 manajer paket, cari
 **Aspose.Slides.Cpp**
 dan menginstal. Anda juga dapat menggunakan perintah berikut dari Package Manager Console.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Memerintah" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Gabungkan File ODP - C++" >}}
```cs
// The path to the documents directory.
const String sourceFilePath1 = u"SourceFile2.odp";
const String sourceFilePath2 = u"SourceFile3.odp";
const String outputFilePath = u"mergedOutput.odp";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides()){
	// Merge from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Odp);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Langkah-langkah Menggabungkan File ODP di C++" intro="Penggabungan dan penggabungan dokumen dasar dengan [Aspose.Slides for C++](https://products.aspose.com/slides/id/cpp/) API dapat dilakukan hanya dengan beberapa baris kode." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat kedua file ODP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gunakan metode get\_Slides() untuk mengulangi setiap slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gunakan fungsi AddClone untuk menggabungkan dengan file yang diinginkan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gunakan metode Save() untuk menyimpan di jalur yang ditentukan{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Persyaratan sistem" intro="Aspose.Slides untuk C++ mendukung pada semua platform utama dan Sistem Operasi. Harap pastikan bahwa Anda memiliki prasyarat berikut." %}}

- Microsoft Windows atau OS yang kompatibel dengan C++ Runtime Environment untuk Windows 32 bit, Windows 64 bit dan Linux 64 bit.
- Aspose.Slides untuk C++ DLL yang dirujuk dalam proyek Anda.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="Menggabungkan File PDF Online"
  description="[Cara Menggabungkan PDF dengan Python](https://products.aspose.com/slides/id/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

File dengan ekstensi `.ODP` menggunakan format OpenDocument Presentation yang ditetapkan oleh standar OASIS OpenDocument. File ODP berisi kumpulan slide yang dapat memuat teks, gambar, pemformatan, animasi, dan media lainnya. Aplikasi yang mendukung presentasi OpenDocument, seperti LibreOffice Impress dan Apache OpenOffice Impress, dapat membuka file ODP.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Penggabungan Lainnya yang Didukung" subTitle="Menggunakan C++, Seseorang juga dapat menggabungkan banyak format file lain termasuk.." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/merger/otp/" name="OTP" description="Format Standar OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/merger/pot/" name="POT" description="File Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/merger/potm/" name="POTM" description="File Templat Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/merger/potx/" name="POTX" description="Presentasi Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/merger/pps/" name="PPS" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/merger/ppsm/" name="PPSM" description="Slide Show yang mendukung makro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/merger/ppsx/" name="PPSX" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/merger/pptm/" name="PPTM" description="File Presentasi berkemampuan makro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/merger/pptx/" name="PPTX" description="Buka Format presentasi XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
