---
title: تحويل Microsoft PowerPoint Presentation إلى ملفات متعددة باستخدام Java
url: /ar/java/conversion/
description: قم بتحويل شرائح Microsoft PowerPoint إلى ملفات مختلفة بما في ذلك تنسيقات HTML و PDF والصور داخل التطبيقات المستندة إلى Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> ® </sup> تحويل عرض PowerPoint التقديمي عبر Java" h2="رموز مصدر Java لسيناريوهات التحويل المختلفة لتحويل الشرائح إلى صور و HTML و PDF وتنسيقات أخرى." >}}

{{% blocks/products/pf/feature-page-summary %}}

جعلت مكتبة Java PowerPoint عملية تحويل عروض PowerPoint التقديمية لـ Microsoft <sup> ® </sup> بسيطة وسهلة لأتمتة العمليات. يمكن للمطورين تحديد السيناريو المناسب ودمج التعليمات البرمجية لتحسين وظائف التطبيق. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل بين ملفات مايكروسوفت باوربوينت" %}}
التحويل البيني لملفات Microsoft <sup> ® </sup> PowerPoint برمجيًا هو مجرد رمز مكون من سطرين. قم بتحميل الملف باستخدام [فئة العرض التقديمي](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) واستدعاء طريقة الحفظ التي تحتوي على ملف الإخراج و [SaveFormat](https: // apireference .aspose.com / slides / java / com.aspose.slides / SaveFormat) كمعلمات.

{{% blocks/products/pf/feature-page-code h3="كود التحويل جافا" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPoint لتحويل PDF" %}}

يعد تحويل PowerPoint إلى PDF حالة شائعة بسبب المشاركة الضخمة لملفات PDF. بدلاً من التحويلات اليدوية ، يمكن للمبرمجين أتمتة ذلك وتوفير الوقت لمجموعة من عروض PowerPoint التقديمية إلى PDF. توفر مكتبة العروض التقديمية [PdfOptions class](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) لتخصيص إعدادات معينة مثل ضبط مستوى ضغط النص ومستوى التوافق مع PDF وجودة JPEG وتحديد السلوك من ملفات التعريف وتحويل الشرائح المخفية واختيار الشرائح المحددة وإنشاء ملفات PDF محمية بكلمة مرور.

{{% blocks/products/pf/feature-page-code h3="جافا باور بوينت إلى كود تحويل PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="مايكروسوفت باوربوينت لتحويل HTML" %}}

نظرًا لأن شرائح PowerPoint لا يتم عرضها مباشرة على صفحات الويب ، فهناك حاجة للتحويل. يمكن للمبرمجين تحميل الملف باستخدام فئة العرض التقديمي واستخدام [HtmlOptions class](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) لإعدادات HTML محددة واستدعاء طريقة الحفظ.

{{% blocks/products/pf/feature-page-code h3="كود جافا لتحويل PowerPoint إلى HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="مايكروسوفت باوربوينت لتحويل الصور" %}}
Microsoft <sup> ® </sup> تنسيقات PowerPoint لصور JPG ، TIFF ، PNG ، إلخ يتم التحويل عادةً لإنشاء صور مصغرة للشرائح بالإضافة إلى المزيد من الحالات. عملية الترميز بسيطة. كرر كل شريحة عبر [واجهة ISlide](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) بعد تحميل المستند ، احصل على الصورة المصغرة ISlide ISlide.getThumbnail (1f، 1f) في [BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) ثم احفظه بتنسيق الصورة المطلوب. 

{{% blocks/products/pf/feature-page-code h3="برنامج Java PowerPoint to Image Converter Code" %}}
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