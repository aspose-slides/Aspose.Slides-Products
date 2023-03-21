---
title: تحويل عرض تقديمي من Microsoft PowerPoint إلى ملفات متعددة باستخدام C#
url: /ar/net/conversion/
description: قم بتحويل شرائح Microsoft PowerPoint إلى ملفات مختلفة بما في ذلك تنسيقات PDF و HTML والصور على .NET Framework أو .NET Core أو Windows Azure أو Mono أو Xamarin الأنظمة الأساسية.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> ® </sup> تحويل عرض PowerPoint التقديمي عبر C#" h2="C# Source Codes لحالات التحويل المختلفة لتحويل الملفات إلى صور و PDF و HTML وتنسيقات أخرى." >}}

{{% blocks/products/pf/feature-page-summary %}}

من السهل على المطورين تحويل عروض PowerPoint التقديمية لـ Microsoft <sup> ® </sup> بسرعة ودقة. احصل على النتائج في أي وقت من الأوقات لأتمتة عمليات الأعمال. نناقش هنا حالات قليلة لقراءة أو تحميل أي إدخال [تنسيقات PowerPoint مدعومة](https://docs.aspose.com/slides/net/supported-file-formats/) والكتابة أو الحفظ بأي تنسيق إخراج مدعوم. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل بين ملفات مايكروسوفت باوربوينت" %}}
متى دعت الحاجة إلى أتمتة التحويل الداخلي لتنسيقات PowerPoint <sup> ® </sup> Microsoft. توفر مكتبة ** C# PowerPoint ** دروسًا لتحقيق هذا الهدف. قم بتحميل الملف باستخدام [فئة العرض التقديمي](https://apireference.aspose.com/net/slides/aspose.slides/presentation) لتحميل أو قراءة التنسيق المطلوب واستدعاء [طريقة الحفظ](https: // apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) من نفس الفئة عن طريق تحديد ملف الإخراج و [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export / تنسيق الحفظ). 
{{% blocks/products/pf/feature-page-code h3="كود محول C# لعروض Microsoft PowerPoint التقديمية" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="C# PowerPoint لتحويل PDF" %}}

لتحويل شرائح PowerPoint إلى PDF بدقة ، يمكن للمبرمجين تحميل المستند باستخدام فئة العرض التقديمي واستخدام [PdfOptions class](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) لجميع أنواع محددة ومخصصة خيارات مثل مستوى ضغط النص وجودة Jpeg وسلوك ملفات التعريف وتحويل الشرائح المخفية بالإضافة إلى تحديد شرائح محددة والمزيد. حتى أن هناك خيارًا لحماية ملف PDF المحول بكلمة مرور.
{{% blocks/products/pf/feature-page-code h3="C# رمز محول PowerPoint إلى PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="مايكروسوفت باوربوينت لتحويل HTML" %}}
عندما تكون هناك حاجة لتضمين العروض التقديمية في صفحات الويب ، فهناك حاجة لتحويل الشرائح إلى HTML. توفر واجهة برمجة التطبيقات [HtmlOptions class](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions) ، استخدمها بعد تحميل الملفات لإعدادات خاصة مثل الشرائح المخفية ، افتراضيًا ، لن أن يتم تضمينها أثناء عملية التحويل. قم بتمرير الخيارات النهائية لحفظ طريقة التحويل.
{{% blocks/products/pf/feature-page-code h3="كود C# لتحويل PowerPoint إلى HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="تحويل شرائح PowerPoint إلى تنسيقات الصور" %}}
يعد تحويل تنسيقات PowerPoint <sup> ® </sup> Microsoft إلى صور JPEG و PNG و TIFF وما إلى ذلك حالة استخدام مشتركة أخرى تُستخدم غالبًا لإنشاء صور مصغرة للشرائح. عملية الترميز بسيطة. بعد تحميل المستند ، استخدم [واجهة ISlide](https://apireference.aspose.com/net/slides/aspose.slides/islide) للتكرار خلال كل شريحة. أثناء كل تكرار ، استخدم (كائن نقطي) [https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap؟view=netframework-4.8] جنبًا إلى جنب مع GetThumbnail mehtod الذي يحتوي على أبعاد صورة مخصصة. أخيرًا احفظ الصورة بالتنسيق المطلوب.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint to Image Converter Code" %}}
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