---
title: 使用 Java 將 Microsoft PowerPoint 演示文稿轉換為多個文件
url: /zh-hant/java/conversion/
description: 在基於 Java 的應用程序中將 Microsoft PowerPoint 幻燈片轉換為不同的文件，包括 HTML、PDF 和圖像格式。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 Java 進行 Microsoft<sup>®</sup> PowerPoint 演示文稿轉換" h2="各種轉換場景的Java源代碼，將幻燈片轉換為圖片、HTML、PDF等格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

Java PowerPoint 庫使 Microsoft<sup>®</sup> PowerPoint 演示文稿的轉換變得簡單且易於自動化流程。開發者可以選擇相關場景並集成代碼來增強應用功能。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 文件的相互轉換" %}}
以編程方式相互轉換 Microsoft<sup>®</sup> PowerPoint 文件只是兩行代碼。使用 [Presentation class](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) 加載文件並調用具有輸出文件和 [SaveFormat](https://apireference) 的保存方法.aspose.com/slides/java/com.aspose.slides/SaveFormat）作為參數。

{{% blocks/products/pf/feature-page-code h3="Java 轉換代碼" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPoint 到 PDF 轉換" %}}

由於 PDF 文件的大量共享，PowerPoint 到 PDF 的轉換是一種常見情況。程序員可以自動轉換，而不是手動轉換，並節省將一堆 PowerPoint 演示文稿轉換為 PDF 的時間。演示庫提供 [PdfOptions 類](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) 用於自定義特定設置，例如設置文本壓縮級別、PDF 合規級別、JPEG 質量、定義行為元文件，轉換隱藏的幻燈片，選擇選定的幻燈片和生成鎖定的密碼保護的 PDF 文件。

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint 到 PDF 轉換代碼" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 到 HTML 轉換" %}}

由於 PowerPoint 幻燈片不直接顯示在網頁上，因此需要轉換。程序員可以使用 Presentation 類加載文件，利用 [HtmlOptions 類](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) 進行特定的 HTML 設置並調用 save 方法。

{{% blocks/products/pf/feature-page-code h3="用於 PowerPoint 到 HTML 轉換的 Java 代碼" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 到圖像的轉換" %}}
Microsoft<sup>®</sup> PowerPoint 格式到圖像 JPG、TIFF、PNG 等的轉換通常用於創建幻燈片縮略圖以及更多情況。編碼過程很簡單。加載文檔後通過[ISlide接口](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide)遍歷每張幻燈片，得到ISlide縮略圖ISlide.getThumbnail(1f, 1f)進入[BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) 然後保存成需要的圖片格式。 

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint 到圖像轉換器代碼" %}}
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

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}