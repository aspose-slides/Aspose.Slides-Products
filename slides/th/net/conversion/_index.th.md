---
title: การแปลงงานนำเสนอ Microsoft PowerPoint เป็นหลายไฟล์โดยใช้ C #
url: /th/net/conversion/
description: แปลง Microsoft PowerPoint Slides เป็นไฟล์ต่างๆ รวมถึง PDF, HTML และรูปแบบรูปภาพบน .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> การแปลงงานนำเสนอ PowerPoint ผ่าน C#" h2="ซอร์สโค้ด C# สำหรับกรณีการแปลงต่างๆ เพื่อแปลงไฟล์เป็นรูปภาพ, PDF, HTML และรูปแบบอื่นๆ" >}}

{{% blocks/products/pf/feature-page-summary %}}

นักพัฒนาสามารถแปลงงานนำเสนอ Microsoft<sup>®</sup> PowerPoint ได้อย่างรวดเร็วและแม่นยำ รับผลลัพธ์ภายในเวลาไม่นานสำหรับกระบวนการทางธุรกิจอัตโนมัติ เรากำลังพูดถึงบางกรณีที่จะอ่านหรือโหลดอินพุตใดๆ [รูปแบบ PowerPoint ที่รองรับ](https://docs.aspose.com/slides/net/supported-file-formats/) และเขียนหรือบันทึกเป็นรูปแบบเอาต์พุตที่รองรับ 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="การแปลงระหว่างไฟล์ Microsoft PowerPoint" %}}
เมื่อใดก็ตามที่จำเป็นต้องแปลงระหว่างรูปแบบ Microsoft<sup>®</sup> PowerPoint โดยอัตโนมัติ **ไลบรารี C# PowerPoint** มีคลาสเพื่อให้บรรลุเป้าหมายนี้ โหลดไฟล์โดยใช้ [คลาสการนำเสนอ](https://apireference.aspose.com/net/slides/aspose.slides/presentation) เพื่อโหลดหรืออ่านรูปแบบที่ต้องการและเรียก [วิธีบันทึก](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) ของคลาสเดียวกันโดยระบุไฟล์เอาต์พุตและ [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export /บันทึกรูปแบบ).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="C# Converter Code สำหรับงานนำเสนอ Microsoft PowerPoint" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="การแปลง C# PowerPoint เป็น PDF" %}}

สำหรับการแปลงสไลด์ PowerPoint เป็น PDF อย่างแม่นยำ โปรแกรมเมอร์สามารถโหลดเอกสารโดยใช้คลาสการนำเสนอและใช้ [คลาส PdfOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) สำหรับข้อมูลเฉพาะและกำหนดเองทั้งหมด ตัวเลือกต่างๆ เช่น ระดับการบีบอัดข้อความ, คุณภาพของ Jpeg, การทำงานของ metafiles, การแปลงสไลด์ที่ซ่อนอยู่ตลอดจนการเลือกสไลด์เฉพาะ และอื่นๆ มีตัวเลือกในการป้องกันไฟล์ PDF ที่แปลงแล้วด้วยรหัสผ่าน
{{% blocks/products/pf/feature-page-code h3="C # PowerPoint เป็น PDF Converter Code" %}}

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
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="การแปลง Microsoft PowerPoint เป็น HTML" %}}
เมื่อจำเป็นต้องฝังงานนำเสนอภายในหน้าเว็บ ก็จำเป็นต้องแปลงสไลด์เป็น HTML API ให้ [คลาส HtmlOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions) ใช้หลังจากโหลดไฟล์สำหรับการตั้งค่าพิเศษ เช่น สไลด์ที่ซ่อนอยู่ ตามค่าเริ่มต้น สิ่งเหล่านี้จะไม่ รวมอยู่ในกระบวนการแปลง ผ่านตัวเลือกที่สรุปผลไปยังวิธีบันทึกสำหรับการแปลง
{{% blocks/products/pf/feature-page-code h3="รหัส C # สำหรับการแปลง PowerPoint เป็น HTML" %}}

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

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="แปลงสไลด์ PowerPoint เป็นรูปแบบรูปภาพ" %}}
การแปลงรูปแบบ Microsoft<sup>®</sup> เป็นรูปภาพ JPEG, PNG, TIFF เป็นต้น เป็นอีกกรณีหนึ่งที่ใช้กันทั่วไปซึ่งส่วนใหญ่ใช้สำหรับสร้างภาพขนาดย่อของสไลด์ ขั้นตอนการเข้ารหัสเป็นเรื่องง่าย หลังจากโหลดเอกสารแล้ว ให้ใช้ [ISlide interface](https://apireference.aspose.com/net/slides/aspose.slides/islide) เพื่อวนซ้ำในแต่ละสไลด์ ในระหว่างการทำซ้ำแต่ละครั้ง ให้ใช้ (Bitmap Object)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] พร้อมกับ GetThumbnail mehtod ที่มีขนาดรูปภาพที่กำหนดเอง สุดท้ายบันทึกภาพในรูปแบบที่ต้องการ
{{% blocks/products/pf/feature-page-code h3="C # PowerPoint เป็นรหัสแปลงรูปภาพ" %}}
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

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}