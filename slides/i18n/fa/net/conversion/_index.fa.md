---
title: تبدیل مایکروسافت پاورپوینت به چندین فایل با استفاده از سی شارپ
url: /fa/net/conversion/
description: اسلایدهای پاورپوینت مایکروسافت را به فایل‌های مختلف از جمله PDF، HTML و فرمت‌های تصویر در .NET Framework، .NET Core، Windows Azure، Mono یا Xamarin تبدیل کنید.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تبدیل پاورپوینت مایکروسافت<sup>®</sup> از طریق سی شارپ" h2="کدهای منبع C# برای موارد تبدیل مختلف برای تبدیل فایل ها به تصاویر، PDF، HTML و فرمت های دیگر." >}}

{{% blocks/products/pf/feature-page-summary %}}

تبدیل کردن پاورپوینت مایکروسافت<sup>®</sup> با سرعت و دقت برای توسعه دهندگان آسان است. برای خودکارسازی فرآیندهای کسب و کار در کمترین زمان ممکن نتایج را دریافت کنید. ما در اینجا چند مورد را برای خواندن یا بارگیری هر ورودی [قالب‌های پاورپوینت پشتیبانی‌شده] (https://docs.aspose.com/slides/net/supported-file-formats/) و نوشتن یا ذخیره در هر قالب خروجی پشتیبانی‌شده مورد بحث قرار می‌دهیم. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="تبدیل بین فایل های پاورپوینت مایکروسافت" %}}
هر زمان که نیاز به خودکار سازی تبدیل بین فرمت های پاورپوینت مایکروسافت<sup>®</sup> وجود داشته باشد. **کتابخانه پاورپوینت سی شارپ** کلاس هایی را برای دستیابی به این هدف فراهم می کند. فایل را با استفاده از [Presentation class] (https://apireference.aspose.com/net/slides/aspose.slides/presentation) برای بارگیری یا خواندن قالب مورد نظر و فراخوانی [Save method] (https://apireference) بارگیری کنید. aspose.com/slides/net/aspose.slides/presentation/methods/save) از همان کلاس با مشخص کردن فایل خروجی و [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export /saveformat).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="کد مبدل سی شارپ برای ارائه پاورپوینت مایکروسافت" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="تبدیل پاورپوینت سی شارپ به پی دی اف" %}}

برای تبدیل دقیق اسلایدهای پاورپوینت به PDF، برنامه نویسان می توانند سند را با استفاده از کلاس Presentation بارگذاری کنند و از [کلاس PdfOptions] (https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) برای همه موارد خاص و سفارشی استفاده کنند. گزینه هایی مانند سطح فشرده سازی متن، کیفیت Jpeg، رفتار متافایل ها، تبدیل اسلایدهای مخفی و همچنین انتخاب اسلایدهای خاص و موارد دیگر. حتی گزینه ای برای محافظت از فایل PDF تبدیل شده با رمز عبور وجود دارد.
{{% blocks/products/pf/feature-page-code h3="کد تبدیل پاورپوینت سی شارپ به پی دی اف" %}}

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


{{% blocks/products/pf/feature-page-section  h2="تبدیل پاورپوینت مایکروسافت به HTML" %}}
زمانی که نیاز به جاسازی ارائه ها در صفحات وب وجود داشته باشد، نیاز به تبدیل اسلایدها به HTML وجود دارد. API [کلاس HtmlOptions] (https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions) را ارائه می‌کند، پس از بارگیری فایل‌ها برای تنظیمات خاص مانند اسلایدهای مخفی، از آن استفاده کنید، زیرا به طور پیش‌فرض، این کارها انجام نمی‌شود. در طول فرآیند تبدیل گنجانده شود. گزینه های نهایی شده را برای تبدیل به روش ذخیره کنید.
{{% blocks/products/pf/feature-page-code h3="کد سی شارپ برای تبدیل پاورپوینت به HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="اسلایدهای پاورپوینت را به فرمت های تصویری تبدیل کنید" %}}
تبدیل فرمت‌های Microsoft<sup>®</sup> PowerPoint به تصاویر JPEG، PNG، TIFF و غیره یکی دیگر از موارد استفاده رایج است که بیشتر برای ایجاد تصاویر کوچک اسلایدها استفاده می‌شود. فرآیند کدنویسی ساده است. پس از بارگیری سند، از [واسط ISlide] (https://apireference.aspose.com/net/slides/aspose.slides/islide) برای تکرار در هر اسلاید استفاده کنید. در طول هر تکرار، از (Bitmap Object)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] همراه با روش GetThumbnail آن که ابعاد تصویر سفارشی شده دارد، استفاده کنید. در نهایت تصویر را در فرمت مورد نیاز ذخیره کنید.
{{% blocks/products/pf/feature-page-code h3="پاورپوینت سی شارپ به کد تبدیل تصویر" %}}
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