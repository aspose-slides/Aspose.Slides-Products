---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tambahkan Watermark ke Presentasi ODP menggunakan C++
url: /id/cpp/watermark/odp/
description: Tambahkan watermark teks atau gambar ke presentasi ODP di C++. Gunakan Aspose.Slides for C++ untuk menempatkan watermark pada slide presentasi.
keywords: tambahkan watermark ke ODP, tambahkan watermark teks ke ODP, tambahkan watermark gambar ke ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tambahkan Watermark ke Presentasi ODP dengan C++" h2="Gunakan Aspose.Slides for C++ untuk menambahkan watermark teks atau gambar ke file presentasi tanpa Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tambahkan Watermark ke Presentasi ODP melalui C++" variant="code" %}}

Aspose.Slides for C++ memungkinkan Anda menambahkan watermark teks atau gambar ke presentasi ODP. Tambahkan bentuk watermark ke slide master dengan `AddAutoShape`, tambahkan teks dengan `AddTextFrame`, atau isi bentuk dengan gambar yang dimuat melalui `File::ReadAllBytes` dan `AddImage`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tambahkan Watermark Teks ke ODP menggunakan C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Tambahkan Watermark Gambar ke Presentasi ODP menggunakan C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menambahkan Watermark ke ODP melalui C++" intro="Ikuti langkah-langkah berikut untuk menambahkan watermark teks atau gambar ke file ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file ODP dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pilih slide master dari koleksi `Presentation::get_Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan bentuk watermark dengan metode `AddAutoShape`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan teks watermark dengan metode `AddTextFrame` atau atur isian gambar dengan `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan file yang diberi watermark dengan `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Dibuat dengan Aspose.Slides" title="Tambahkan Watermark ke File ODP Secara Online" description="Aplikasi Aspose.Slides Watermark gratis dibuat dengan [Aspose.Slides for C++](https://products.aspose.com/slides/id/cpp/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file ODP Anda sendiri." button="Buka Aspose.Slides Watermark" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menambahkan watermark sebelum menulis kode.
- Tambahkan watermark teks atau gambar ke file ODP Anda.
- Unduh file yang diberi watermark.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Mendukung Watermark" subTitle="Dengan C++, Anda juga dapat menambahkan watermark ke format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
