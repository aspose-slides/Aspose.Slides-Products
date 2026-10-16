---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversi gambar ke PPTX di C#
url: /id/net/conversion/image-to-pptx/
keywords: Konversi gambar ke PPTX, gambar ke PPTX, PowerPoint, gambar, PPTX, C# API, .NET Library
description: Konversi gambar ke PPTX dalam C#. Gunakan .NET library API untuk mengonversi gambar ke PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversi gambar ke PPTX di C#" h2=".NET API lintas platform yang kuat untuk mengonversi gambar ke PPTX menggunakan kode C# pada Platform NET Framework, .NET Core, Windows Azure, Mono atau Xamarin" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversi gambar ke PPTX di C#" variant="code" %}}

Menggunakan [**Aspose.Slides for .NET**](https://products.aspose.com/slides/id/net/), Anda dapat mengonversi gambar menjadi presentasi PowerPoint hanya dengan beberapa baris kode:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode C# untuk mengonversi gambar ke PPTX" >}}
```cs

using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.pptx", SaveFormat.Pptx);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan gambar ke PPTX menggunakan Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/id/net/) adalah pustaka .NET andal yang digunakan untuk membuat, mengonversi, dan memanipulasi presentasi PowerPoint, PDF, dokumen HTML, dan file lainnya. Saat Anda mengonversi gambar ke PPTX, pada dasarnya Anda membuat presentasi PowerPoint yang berisi slide berdasarkan gambar tersebut.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara mengonversi gambar ke PPTX di C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal **Aspose.Slides untuk .NET**. Lihat [**Penginstalan**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan perpustakaan sebagai referensi dalam proyek Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buat sebuah instance dari kelas Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat gambar yang ingin Anda konversi ke PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan file yang dihasilkan sebagai presentasi PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Konverter Daring Gratis"
  description="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversi PowerPoint Lainnya yang Didukung" subTitle="Anda juga dapat mengonversi file dalam format lain ke PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
