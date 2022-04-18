---
title: Konversi Presentasi Microsoft PowerPoint ke Banyak File menggunakan Java
url: /id/java/conversion/
description: Konversikan Microsoft PowerPoint Slides ke berbagai file termasuk HTML, PDF, dan format gambar dalam aplikasi berbasis Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi Presentasi PowerPoint Microsoft<sup>®</sup> melalui Java" h2="Kode sumber Java untuk berbagai skenario konversi untuk mengonversi slide ke gambar, HTML, PDF, dan format lainnya." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pustaka PowerPoint Java telah membuat konversi Microsoft<sup>®</sup> Presentasi PowerPoint menjadi sederhana dan mudah untuk mengotomatisasi proses. Pengembang dapat memilih skenario yang relevan dan mengintegrasikan kode untuk meningkatkan fungsionalitas aplikasi. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi Antar File Microsoft PowerPoint" %}}
Interkonversi file Microsoft<sup>®</sup> PowerPoint secara terprogram hanyalah kode dua baris. Muat file menggunakan [Presentation class](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) dan panggil metode simpan yang memiliki file output dan [SaveFormat](https://apireference .aspose.com/slides/java/com.aspose.slides/SaveFormat) sebagai parameter.

{{% blocks/products/pf/feature-page-code h3="Kode Konversi Java" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Konversi PowerPoint ke PDF" %}}

Konversi PowerPoint ke PDF adalah kasus umum karena berbagi file PDF dalam jumlah besar. Alih-alih konversi manual, pemrogram dapat mengotomatiskannya dan menghemat waktu untuk banyak presentasi PowerPoint ke PDF. Pustaka presentasi menyediakan [kelas PdfOptions](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) untuk menyesuaikan pengaturan tertentu seperti mengatur tingkat kompresi teks, tingkat kepatuhan PDF, kualitas JPEG, menentukan perilaku metafile, mengonversi slide tersembunyi, memilih slide yang dipilih, dan menghasilkan file PDF yang dilindungi kata sandi terkunci.

{{% blocks/products/pf/feature-page-code h3="Kode Konversi Java PowerPoint ke PDF" %}}

```cs
// Load file
Presentation powerpointopdf = new Presentation("srcFile.pptx");

// Create PdfOptions class object
PdfOptions slidetopdfOpt = new PdfOptions();
               
// Set JPEG Quality
slidetopdfOpt.setJpegQuality((byte) 90);

// Define behavior for Metafiles
slidetopdfOpt.setSaveMetafilesAsPng(true);

// Set Text Compression level
slidetopdfOpt.setTextCompression(PdfTextCompression.Flate);

// Define the PDF standard
slidetopdfOpt.setCompliance(PdfCompliance.Pdf15);
              
INotesCommentsLayoutingOptions options = slidetopdfOpt.getNotesCommentsLayouting();
options.setNotesPosition(NotesPositions.BottomFull);

// Specify that the generated document should include hidden slides
slidetopdfOpt.setShowHiddenSlides(true);
	
// Setting PDF password
slidetopdfOpt.setPassword("password");	

// Save the presentation to PDF with specified options
powerpointopdf.save("java-powerpoint-to.pdf", SaveFormat.Pdf, slidetopdfOpt);


// Setting array of slides positions
// int[] slides = new int[] { 2, 3, 5 };

// Save the presentation to PDF
// powerpointopdf.save("java-powerpoint-to.pdf", slides, SaveFormat.Pdf);

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Konversi Microsoft PowerPoint ke HTML" %}}

Karena slide PowerPoint tidak langsung ditampilkan di halaman web, maka diperlukan konversi. Pemrogram dapat memuat file menggunakan kelas Presentasi, menggunakan [kelas HtmlOptions](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) untuk pengaturan HTML tertentu dan memanggil metode simpan.

{{% blocks/products/pf/feature-page-code h3="Kode Java untuk Konversi PowerPoint ke HTML" %}}

```cs

// Load the file
Presentation powerpointohtml = new Presentation("srcFile.pptx");

// Create HTML options
HtmlOptions pptxhtmlOpt = new HtmlOptions();

// Displaying hidden slides
pptxhtmlOpt.setShowHiddenSlides(true);

// Save the PPTX as HTML
powerpointohtml.save("java-powerpoint-to.html", SaveFormat.Html, pptxhtmlOpt); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Konversi Microsoft PowerPoint ke Gambar" %}}
Microsoft<sup>®</sup> format PowerPoint ke gambar JPG, TIFF, PNG, dll. Konversi biasanya untuk membuat gambar mini slide serta lebih banyak kasus. Proses pengkodean sederhana. Ulangi setiap slide melalui [antarmuka ISlide](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) setelah memuat dokumen, dapatkan gambar mini ISlide ISlide.getThumbnail(1f, 1f) ke [BufferedImage Object](https://docs.Oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) lalu simpan ke dalam format gambar yang diperlukan. 

{{% blocks/products/pf/feature-page-code h3="Kode Konverter Java PowerPoint ke Gambar" %}}
```cs
// Load the PowerPoint document
Presentation PowerPointtoImage = new Presentation("templatefile.pptx");


// for generating a full scale image
// BufferedImage bi = sld.getThumbnail(1f, 1f);

// for Customized dimensions, define dimensions
int finalX = 1200;
int finalY = 800;

// Get scaled values of X and Y
float DimensionX = (float)(1.0 / PowerPointtoImage.getSlideSize().getSize().getWidth()) * finalX;
float DimensionY = (float)(1.0 / PowerPointtoImage.getSlideSize().getSize().getHeight()) * finalY;

// Loop through each slide in the presentation
for (ISlide sld : PowerPointtoImage.getSlides()) {
	
// Create a full scale image
BufferedImage bi = sld.getThumbnail(DimensionX, DimensionY);

// Create a new file
File outputfile = new File(sld.getSlideNumber() + "_Slide.jpg");
	
// Save the image to disk in JPEG format
ImageIO.write(bi, "jpg", outputfile);
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}