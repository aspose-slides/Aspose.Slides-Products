---
title: Konversi Presentasi Microsoft PowerPoint ke Banyak File menggunakan C#
url: /id/net/conversion/
description: Konversikan Microsoft PowerPoint Slides ke berbagai file termasuk PDF, HTML, dan format gambar di .NET Framework, .NET Core, Windows Azure, Mono atau Xamarin Platforms.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi Presentasi PowerPoint Microsoft<sup>®</sup> melalui C#" h2="Kode Sumber C# untuk kasus konversi yang berbeda untuk mengonversi file ke gambar, PDF, HTML, dan format lainnya." >}}

{{% blocks/products/pf/feature-page-summary %}}

Sangat mudah bagi para pengembang untuk mengonversi Microsoft<sup>®</sup> Presentasi PowerPoint dengan kecepatan dan akurasi. Dapatkan hasil dalam waktu singkat untuk mengotomatisasi proses bisnis. Kami membahas di sini beberapa kasus untuk membaca atau memuat input apa pun [format PowerPoint yang didukung](https://docs.aspose.com/slides/net/supported-file-formats/) dan menulis atau menyimpan ke format output apa pun yang didukung. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi Antar File Microsoft PowerPoint" %}}
Kapan pun diperlukan untuk mengotomatiskan konversi antar format PowerPoint<sup>®</sup> Microsoft. **C# PowerPoint library** menyediakan kelas untuk mencapai target ini. Muat file menggunakan [Presentation class](https://apireference.aspose.com/net/slides/aspose.slides/presentation) untuk memuat atau membaca format yang diinginkan dan memanggil [Save method](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) dari kelas yang sama dengan menentukan file output dan [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export /saveformat).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="Kode Konverter C# untuk Presentasi Microsoft PowerPoint" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Konversi C# PowerPoint ke PDF" %}}

Untuk mengonversi slide PowerPoint ke PDF secara akurat, Pemrogram dapat memuat dokumen menggunakan kelas Presentasi dan menggunakan [kelas PdfOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) untuk semua spesifik dan kustom pilihan seperti tingkat kompresi teks, kualitas Jpeg, perilaku metafile, mengonversi slide tersembunyi serta memilih slide tertentu dan banyak lagi. Bahkan ada opsi untuk melindungi file PDF yang dikonversi dengan kata sandi.
{{% blocks/products/pf/feature-page-code h3="Kode Konverter C# PowerPoint ke PDF" %}}

```cs
// Load PowerPoint file
Presentation pptxtopdf = new Presentation("sourceFile.pptx");

// Create PdfOptions class object for specific settings
PdfOptions pptPDFOptions = new PdfOptions();

// Set Jpeg quality
pptPDFOptions.JpegQuality = 90;

// Set behavior for metafiles
pptPDFOptions.SaveMetafilesAsPng = true;

// Set text compression level
pptPDFOptions.TextCompression = PdfTextCompression.Flate;

// Define the PDF 15 standard
pptPDFOptions.Compliance = PdfCompliance.Pdf15;

// Include hidden slides
pptPDFOptions.ShowHiddenSlides = true;

// Setting PDF password and access permissions
pptPDFOptions.Password = "password";
pptPDFOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;

// Save the presentation as PDF
pptxtopdf.Save("csharp-PowerPoint-to.pdf", SaveFormat.Pdf, pptPDFOptions);

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf pdf-to-html pdf-to-image pdf-to-jpg pdf-to-png pdf-to-svg pdf-to-tiff pdf-to-xml" >}}


{{% blocks/products/pf/feature-page-section  h2="Konversi Microsoft PowerPoint ke HTML" %}}
Kapan pun ada kebutuhan untuk menyematkan presentasi di dalam halaman web, maka ada kebutuhan untuk mengonversi slide ke HTML. API menyediakan [kelas HtmlOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions), Gunakan setelah memuat file untuk pengaturan khusus seperti slide tersembunyi, karena secara default, ini tidak akan disertakan selama proses konversi. Lewati opsi yang telah diselesaikan ke Simpan metode untuk konversi.
{{% blocks/products/pf/feature-page-code h3="Kode C# untuk Konversi PowerPoint ke HTML" %}}

```cs

// Load source presentation 
Presentation powerpoiontohtml = new Presentation("sourceFile.pptx");

// Create HTML options
HtmlOptions PowerPointhtmlOpt = new HtmlOptions();

// Show hidden slides
PowerPointhtmlOpt.ShowHiddenSlides = true;

// Save the PPTX as HTML
powerpoiontohtml.Save("presentation-to.html", SaveFormat.Html, PowerPointhtmlOpt); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html html-to-image html-to-jpg html-to-pdf html-to-tiff html-to-xml" >}}

{{% blocks/products/pf/feature-page-section  h2="Konversikan Slide PowerPoint ke Format Gambar" %}}
Mengonversi Microsoft<sup>®</sup> format PowerPoint ke gambar JPEG, PNG, TIFF dll adalah kasus penggunaan umum lainnya yang sebagian besar digunakan untuk membuat thumbnail slide. Proses pengkodean sederhana. Setelah memuat dokumen, Gunakan [antarmuka ISlide](https://apireference.aspose.com/net/slides/aspose.slides/islide) untuk mengulangi setiap slide. Selama setiap iterasi, gunakan (Objek Bitmap)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] bersama dengan metode GetThumbnail yang memiliki dimensi gambar yang disesuaikan. Terakhir simpan gambar dalam format yang diperlukan.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint ke Kode Konverter Gambar" %}}
```cs
using (Presentation powerpointtoimage = new Presentation("source-file.ppt")){
foreach (ISlide sld in powerpointtoimage.Slides){

// Create a full scale image
Bitmap bmp = sld.GetThumbnail(1f, 1f);
// or use some customized dimensions as sld.GetThumbnail(x, y)

// Save the image
bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
}
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp image-to-jpg image-to-pdf jpg-to-image jpg-to-pdf jpg-to-png png-to-jpg png-to-pdf png-to-svg svg-to-png" >}}