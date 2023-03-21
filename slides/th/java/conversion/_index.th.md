---
title: การแปลงงานนำเสนอ Microsoft PowerPoint เป็นหลายไฟล์โดยใช้ Java
url: /th/java/conversion/
description: แปลง Microsoft PowerPoint Slides เป็นไฟล์ต่างๆ รวมถึงรูปแบบ HTML, PDF และรูปภาพภายในแอปพลิเคชันที่ใช้ Java
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> การแปลงงานนำเสนอ PowerPoint ผ่าน Java" h2="ซอร์สโค้ด Java สำหรับสถานการณ์การแปลงต่างๆ เพื่อแปลงสไลด์เป็นรูปภาพ, HTML, PDF และรูปแบบอื่นๆ" >}}

{{% blocks/products/pf/feature-page-summary %}}

ไลบรารี Java PowerPoint ทำให้การแปลง Microsoft<sup>®</sup> PowerPoint Presentations เป็นเรื่องง่ายและง่ายต่อการทำให้กระบวนการอัตโนมัติ นักพัฒนาสามารถเลือกสถานการณ์ที่เกี่ยวข้องและรวมโค้ดเพื่อเพิ่มประสิทธิภาพการทำงานของแอปพลิเคชัน 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="การแปลงระหว่างไฟล์ Microsoft PowerPoint" %}}
การแปลงไฟล์ PowerPoint<sup>®</sup> Microsoft<sup>®</sup> โดยทางโปรแกรมเป็นเพียงโค้ดสองบรรทัด โหลดไฟล์โดยใช้ [คลาสการนำเสนอ](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) และเรียกวิธีการบันทึกที่มีไฟล์เอาต์พุตและ [SaveFormat](https://apireference .aspose.com/slides/java/com.aspose.slides/SaveFormat) เป็นพารามิเตอร์

{{% blocks/products/pf/feature-page-code h3="รหัสการแปลง Java" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="การแปลง PowerPoint เป็น PDF" %}}

การแปลง PowerPoint เป็น PDF เป็นกรณีทั่วไปเนื่องจากการแชร์ไฟล์ PDF จำนวนมาก แทนที่จะแปลงด้วยตนเอง โปรแกรมเมอร์สามารถทำให้เป็นอัตโนมัติและประหยัดเวลาสำหรับการนำเสนอ PowerPoint เป็น PDF จำนวนมาก ไลบรารีการนำเสนอมี [คลาส PdfOptions](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) สำหรับกำหนดการตั้งค่าเฉพาะ เช่น การตั้งค่าระดับการบีบอัดข้อความ ระดับการปฏิบัติตามข้อกำหนดของ PDF คุณภาพ JPEG กำหนดลักษณะการทำงาน ของ metafiles, การแปลงสไลด์ที่ซ่อนอยู่, เลือกสไลด์ที่เลือกและสร้างไฟล์ PDF ที่ล็อคด้วยรหัสผ่าน

{{% blocks/products/pf/feature-page-code h3="รหัสการแปลง Java PowerPoint เป็น PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="การแปลง Microsoft PowerPoint เป็น HTML" %}}

เนื่องจากสไลด์ PowerPoint จะไม่แสดงบนหน้าเว็บโดยตรง ดังนั้นจึงจำเป็นต้องมีการแปลง โปรแกรมเมอร์สามารถโหลดไฟล์โดยใช้คลาสการนำเสนอ ใช้ [คลาส HtmlOptions](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) สำหรับการตั้งค่า HTML เฉพาะและเรียกใช้วิธีการบันทึก

{{% blocks/products/pf/feature-page-code h3="โค้ด Java สำหรับการแปลง PowerPoint เป็น HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="การแปลง Microsoft PowerPoint เป็นรูปภาพ" %}}
Microsoft<sup>®</sup> รูปแบบ PowerPoint เป็นรูปภาพ JPG, TIFF, PNG และอื่น ๆ การแปลงเป็นปกติสำหรับการสร้างภาพขนาดย่อของสไลด์รวมถึงกรณีอื่น ๆ อีกมากมาย ขั้นตอนการเข้ารหัสเป็นเรื่องง่าย วนซ้ำแต่ละสไลด์ผ่าน [อินเทอร์เฟซ ISlide](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) หลังจากโหลดเอกสารแล้ว ให้โหลดภาพขนาดย่อของ ISlide ISlide.getThumbnail(1f, 1f) เข้าไป [BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) จากนั้นบันทึกลงในรูปแบบรูปภาพที่ต้องการ 

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint เป็น Image Converter Code" %}}
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