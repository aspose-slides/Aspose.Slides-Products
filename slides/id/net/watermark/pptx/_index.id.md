---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tambahkan Watermark ke Presentasi PPTX menggunakan C#
url: /id/net/watermark/pptx/
description: Tambahkan watermark teks dan gambar ke presentasi PPTX di C# menggunakan Aspose.Slides for .NET.
keywords: tambahkan watermark ke PPTX, tambahkan watermark teks ke PPTX, tambahkan watermark gambar ke PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tambahkan Watermark ke Presentasi PPTX dengan C#" h2="Bangun aplikasi .NET yang menyisipkan watermark teks atau gambar ke dalam file presentasi." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tambahkan Watermark ke Presentasi PPTX melalui C#" variant="code" %}}

Dengan [Aspose.Slides for .NET](/slides/id/net/), Anda dapat menambahkan watermark teks dan gambar ke presentasi PPTX. Tambahkan bentuk watermark ke slide master agar watermark muncul pada slide yang menggunakan master tersebut.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tambahkan Watermark Teks ke PPTX menggunakan C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Tambahkan Watermark Gambar ke Presentasi PPTX menggunakan C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menambahkan Watermark ke PPTX melalui C#" intro="Ikuti langkah-langkah berikut untuk menambahkan watermark teks atau gambar ke file PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file `PPTX` dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pilih slide master dari koleksi `Presentation.Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode `AddAutoShape` untuk menambahkan bentuk watermark.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode `AddTextFrame` untuk menambahkan teks watermark atau gunakan `AddImage` untuk watermark gambar.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan file yang diberi watermark dengan `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Dibuat dengan Aspose.Slides" title="Tambahkan Watermark ke File PPTX Secara Online" description="Aplikasi Aspose.Slides Watermark gratis dibuat dengan [Aspose.Slides for .NET](https://products.aspose.com/slides/id/net/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPTX Anda sendiri." button="Buka Aspose.Slides Watermark" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menambahkan watermark sebelum menulis kode.
- Tambahkan watermark teks atau gambar ke file PPTX Anda.
- Unduh file yang diberi watermark.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Mendukung Watermark" subTitle="Dengan C#, Anda juga dapat menambahkan watermark ke format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
