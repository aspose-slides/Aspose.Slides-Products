---
title: تبدیل مایکروسافت پاورپوینت به چندین فایل با استفاده از جاوا
url: /fa/java/conversion/
description: اسلایدهای پاورپوینت مایکروسافت را به فایل های مختلف از جمله فرمت های HTML، PDF و تصویر در برنامه های کاربردی مبتنی بر جاوا تبدیل کنید.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تبدیل پاورپوینت مایکروسافت<sup>®</sup> از طریق جاوا" h2="کدهای منبع جاوا برای سناریوهای مختلف تبدیل برای تبدیل اسلایدها به تصاویر، HTML، PDF و فرمت های دیگر." >}}

{{% blocks/products/pf/feature-page-summary %}}

کتابخانه جاوا پاورپوینت تبدیل مایکروسافت<sup>®</sup> PowerPoint Presentations را ساده و آسان برای خودکارسازی فرآیندها کرده است. توسعه دهندگان می توانند سناریوی مربوطه را انتخاب کرده و کد را برای بهبود عملکرد برنامه یکپارچه کنند. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="تبدیل بین فایل های پاورپوینت مایکروسافت" %}}
تبدیل فایل های Microsoft<sup>®</sup> PowerPoint به صورت برنامه ای فقط یک کد دو خطی است. فایل را با استفاده از [Presentation class] (https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) بارگیری کنید و متد ذخیره را با فایل خروجی و [SaveFormat] (https://apireference) فراخوانی کنید. .aspose.com/slides/java/com.aspose.slides/SaveFormat) به عنوان پارامتر.

{{% blocks/products/pf/feature-page-code h3="کد تبدیل جاوا" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="تبدیل پاورپوینت به پی دی اف" %}}

تبدیل پاورپوینت به PDF به دلیل اشتراک گذاری زیاد فایل های PDF یک مورد رایج است. به‌جای تبدیل‌های دستی، برنامه‌نویسان می‌توانند آن را خودکار کرده و در وقت خود برای ارائه‌های پاورپوینت به PDF صرفه‌جویی کنند. کتابخانه ارائه [کلاس PdfOptions] (https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) را برای سفارشی کردن تنظیمات خاص مانند تنظیم سطح فشرده سازی متن، سطح انطباق PDF، کیفیت JPEG، تعریف رفتار فراهم می کند. متافایل ها، تبدیل اسلایدهای مخفی، انتخاب اسلایدهای انتخاب شده و تولید فایل های PDF محافظت شده با رمز عبور قفل شده.

{{% blocks/products/pf/feature-page-code h3="کد تبدیل پاورپوینت جاوا به پی دی اف" %}}

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


{{% blocks/products/pf/feature-page-section  h2="تبدیل پاورپوینت مایکروسافت به HTML" %}}

از آنجایی که اسلایدهای پاورپوینت مستقیماً در صفحات وب نمایش داده نمی شوند، بنابراین نیاز به تبدیل وجود دارد. برنامه نویسان می توانند فایل را با استفاده از کلاس Presentation بارگذاری کنند، از [کلاس HtmlOptions] (https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) برای تنظیمات خاص HTML استفاده کنند و روش ذخیره را فراخوانی کنند.

{{% blocks/products/pf/feature-page-code h3="کد جاوا برای تبدیل پاورپوینت به HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="تبدیل پاورپوینت مایکروسافت به تصاویر" %}}
تبدیل فرمت‌های Microsoft<sup>®</sup> PowerPoint به تصاویر JPG، TIFF، PNG، و غیره معمولاً برای ایجاد تصاویر کوچک اسلایدها و همچنین موارد بسیار بیشتر است. فرآیند کدنویسی ساده است. در هر اسلاید از طریق [واسط ISlide] (https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) پس از بارگیری سند، تصویر کوچک ISlide را دریافت کنید ISlide.getThumbnail(1f, 1f) [BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) و سپس در قالب تصویر مورد نیاز ذخیره کنید. 

{{% blocks/products/pf/feature-page-code h3="کد تبدیل پاورپوینت جاوا به تصویر" %}}
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