---
title: Konversikan PPT ke Word dalam C#
url: /id/net/conversion/ppt-to-word/
keywords: Konversikan PPT ke Word, PPT ke Word, PPT ke DOC, PowerPoint ke Word, C# API, .NET Library
description: Konversikan PPT ke Word dalam C#. Gunakan .NET library API untuk mengonversi PowerPoint ke Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversikan PPT ke Word dalam C#" h2=".NET API lintas platform yang kuat untuk mengonversi PowerPoint ke Word menggunakan kode C# pada Platform NET Framework, .NET Core, Windows Azure, Mono atau Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan PowerPoint ke Word menggunakan Aspose.Slides dan Aspose.Words" %}}

[**Aspose.Slides untuk .NET**](https://products.aspose.com/slides/id/net/) dan [**Aspose.Words untuk .NET**](https://products.aspose. com/words/net/) adalah pustaka .NET andal yang digunakan untuk memanipulasi dan mengonversi presentasi PowerPoint, dokumen Word, dan file lainnya. Saat Anda mengonversi PowerPoint ke Word, pada dasarnya Anda memindahkan konten slide presentasi ke halaman dalam dokumen Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Konversikan PowerPoint ke Word dalam C#" %}}
Anda dapat mengonversi PPT ke Word dengan cepat hanya dengan beberapa baris kode

{{% blocks/products/pf/agp/code-block title="Kode C# untuk mengonversi PowerPoint ke Word" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
var doc = new Document();
var builder = new DocumentBuilder(doc);
foreach (var slide in presentation.Slides)
{
    // generates and inserts slide image
    using var bitmap = slide.GetThumbnail(1, 1);
    using var stream = new MemoryStream();
    bitmap.Save(stream, ImageFormat.Png);
    stream.Seek(0, SeekOrigin.Begin);
    using var skBitmap = SKBitmap.Decode(stream);
    builder.InsertImage(skBitmap);

    // inserts slide texts
    foreach (var shape in slide.Shapes)
    {
        if (shape is AutoShape autoShape)
        {
            builder.Writeln(autoShape.TextFrame.Text);
        }
    }

    builder.InsertBreak(BreakType.PageBreak);
}
doc.Save("document.docx");
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Bagaimana mengkonversi PPT ke Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instal **Aspose.Slides untuk .NET** dan **Aspose.Words untuk .NET** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan kedua pustaka tersebut sebagai referensi dalam proyek Anda.
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


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}