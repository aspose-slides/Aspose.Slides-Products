---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversi PPT ke PNG melalui aplikasi C++
weight: 4260
url: /id/cpp/conversion/ppt-to-png/ 
description: Contoh kode konversi C++ untuk dokumen PPT ke format PNG. Gunakan kode contoh untuk konversi batch PPT ke PNG dalam Aplikasi C++ apa pun.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversi PPT ke PNG melalui C++" h2="Konversi PPT ke PNG kinerja tinggi menggunakan pustaka C++ tanpa perlu instalasi Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cara Mengonversi PPT ke PNG Menggunakan C++" %}}

Untuk mengonversi PPT ke PNG, kami akan menggunakan
 [Aspose.Slides untuk C++](https://products.aspose.com/slides/id/cpp/)
 API yang kaya fitur, kuat, dan mudah digunakan untuk manipulasi dokumen dan API konversi untuk platform C++. Bisa langsung download versi terbarunya, tinggal buka
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 manajer paket, cari
 Aspose.Slides.Cpp
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode Sumber Konversi PPT ke PNG C++" >}}
```cs
// Load the PPT
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.ppt");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.png", ImageFormat::get_Png());
	
//Iterate through each slide via index and convert

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Langkah-langkah untuk Mengonversi PPT ke PNG melalui C++" intro="Pengembang C++ dapat dengan mudah mengonversi file PPT ke PNG hanya dalam beberapa baris kode." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPT dengan Aspose.Slides untuk Objek Presentasi C++.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pilih slide pertama.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Atur dimensi yang diinginkan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dapatkan thumbnail dengan dimensi yang diinginkan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode Save() yang memiliki parameter output PNG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file PNG di program yang kompatibel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Persyaratan sistem" intro="Sebelum menjalankan kode contoh konversi C++, pastikan Anda memiliki prasyarat berikut." %}}

- Microsoft Windows atau OS yang kompatibel dengan C++ Runtime Environment untuk Windows 32 bit, Windows 64 bit dan Linux 64 bit.
- Aspose.Slides untuk C++ DLL yang dirujuk dalam proyek Anda.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Dibuat dengan Aspose.Slides" title="Konversi PPT ke PNG Secara Online" description="Aplikasi Aspose.Slides Conversion gratis dibuat dengan [Aspose.Slides for C++](https://products.aspose.com/slides/id/cpp/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Conversion" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" upload="Letakkan atau unggah file Anda" saveAs="Simpan sebagai" convert="Konversi" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides mengonversi file sebelum Anda menulis kode.
- Unggah file PPT dan simpan sebagai PNG.
- Unduh hasilnya atau konversi lebih banyak file.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversi lain yang Didukung" subTitle="Anda juga dapat mengonversi PPT ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" description="Gambar bitmap" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" description="Format Metafile yang Ditingkatkan" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" description="Format Pertukaran Grafis" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-html/" name="PPT TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" description="Gambar JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-odp/" name="PPT TO ODP" description="Format Presentasi OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-otp/" name="PPT TO OTP" description="Format Standar OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-pdf/" name="PPT TO PDF" description="Format Dokumen Portabel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-pot/" name="PPT TO POT" description="File Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-potm/" name="PPT TO POTM" description="File Templat Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-potx/" name="PPT TO POTX" description="Presentasi Template Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-pps/" name="PPT TO PPS" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="Slide Show yang mendukung makro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="Pertunjukan Slide PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="File Presentasi berkemampuan makro" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="Buka Format presentasi XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" description="Grafik Vektor Skalabel" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="Format Gambar yang Ditandai" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-xml/" name="PPT TO XML" description="Bahasa Markup yang Dapat Diperluas" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/cpp/conversion/ppt-to-xps/" name="PPT TO XPS" description="Spesifikasi Kertas XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
