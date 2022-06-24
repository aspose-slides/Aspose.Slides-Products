---
title: تبدیل مایکروسافت پاورپوینت به PDF در PHP
url: /fa/php-java/conversion/
keyslides: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API برای تبدیل PPT به PDF. ارائه ها را به JPG، PNG و فرمت های دیگر در PHP تبدیل کنید.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> ارائه پاورپوینت به تبدیل PDF در PHP" h2="کدهای منبع PHP برای موارد تبدیل مختلف برای تبدیل PPT به PDF، PNG، HTML، JPEG، PPTX و فرمت های دیگر." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides for PHP via Java](https://products.aspose.com/slides/fa/php-java/) یک کتابخانه قدرتمند کلاس داخلی است که برای پردازش و کار با ارائه ها استفاده می شود. تبدیل پاورپوینت به PDF با سرعت و دقت برای توسعه دهندگان آسان است. برای خودکارسازی فرآیندهای کسب و کار در کمترین زمان ممکن نتایج را دریافت کنید. ما در اینجا چند مورد برای خواندن یا بارگیری هر ورودی [فرمت‌های پاورپوینت پشتیبانی شده](https://docs.aspose.com/slides/php-java/supported-file-formats/) و نوشتن یا ذخیره در هر فرمت خروجی پشتیبانی شده مورد بحث قرار می‌دهیم. . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="تبدیل پاورپوینت به PDF در PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/fa/php-java/) به شما امکان می دهد فایل ها را با فرمت های PowerPoint PPT، PPTX و OpenOffice ODP به PDF تبدیل کنید. برای تبدیل یک ارائه به PDF، به سادگی نام فایل را ارسال کرده و فرمت را به روش «Presentation.save» ذخیره کنید. کلاس «Presentation» متد «save» را نشان می‌دهد که می‌تواند برای تبدیل کل ارائه PPT، PPTX یا ODP به یک سند PDF فراخوانی شود.

{{% blocks/products/pf/feature-page-code h3="تبدیل پاورپوینت PHP به PDF" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    $pres->save("output.pdf", SaveFormat::Pdf); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf potm-to-pdf potx-to-pdf ppsm-to-pdf odp-to-pdf" >}}

{{% blocks/products/pf/feature-page-section  h2="تبدیل PDF به PPT در PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/fa/php-java/) به شما امکان می دهد ارائه ها را از فایل های PDF وارد کنید. در اصل، شما می توانید یک PDF را به یک ارائه پاورپوینت تبدیل کنید. برای تبدیل PDF به پاورپوینت مراحل زیر را طی کنید:
- نمونه سازی یک شی از کلاس «Presentation».
- متد «addFromPdf» را فراخوانی کنید و فایل PDF را پاس کنید.
- برای ذخیره فایل در قالب پاورپوینت از روش «ذخیره» استفاده کنید.

{{% blocks/products/pf/feature-page-code h3="تبدیل پی اچ پی پی دی اف به پاورپوینت" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
    $pres->save("output.pptx", SaveFormat::Pptx); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-ppt pdf-to-pptx pdf-to-odp pdf-to-png pdf-to-jpg pdf-to-html" >}}


{{% blocks/products/pf/feature-page-section  h2="تبدیل PPT به PDF با گزینه های سفارشی در PHP" %}}

برای تبدیل دقیق اسلایدهای پاورپوینت به PDF، برنامه نویسان می توانند سند را با استفاده از کلاس «Presentation» بارگذاری کنند و از کلاس «PdfOptions» برای همه گزینه های خاص و سفارشی مانند سطح فشرده سازی متن، کیفیت Jpeg، رفتار متافایل ها، تبدیل اسلایدهای مخفی و همچنین انتخاب استفاده کنند. اسلایدهای خاص و موارد دیگر. حتی گزینه ای برای محافظت از فایل PDF تبدیل شده با رمز عبور وجود دارد.
{{% blocks/products/pf/feature-page-code h3="تبدیل PHP PowerPoint به PDF با تنظیمات دلخواه" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\PdfOptions;
use aspose\slides\PdfTextCompression;
use aspose\slides\PdfCompliance;
 
$pres = new Presentation("input.pptx");
try
{
    $pdfOptions = new PdfOptions();
    $pdfOptions->setJpegQuality(90);
    $pdfOptions->setSaveMetafilesAsPng(true);
    $pdfOptions->setTextCompression(PdfTextCompression::Flate);
    $pdfOptions->setCompliance(PdfCompliance::Pdf15);
    $pres->save("output.pdf", SaveFormat::Pdf, $pdfOptions);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="تبدیل پاورپوینت مایکروسافت به HTML در PHP" %}}
زمانی که نیاز به جاسازی ارائه ها در صفحات وب وجود داشته باشد، نیاز به تبدیل اسلایدها به HTML وجود دارد. 
{{% blocks/products/pf/feature-page-code h3="کد PHP برای تبدیل پاورپوینت به HTML" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\Html5Options;
 
$pres = new Presentation("input.pptx");
try
{
    $html5Options = new Html5Options();
    $html5Options->setAnimateShapes(false);
    $html5Options->setAnimateTransitions(false);
    $pres->save("output.html", SaveFormat::Html5, $html5Options);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="تبدیل پاورپوینت به JPG" %}}
تبدیل فرمت های Microsoft<sup>®</sup> PowerPoint به تصاویر JPEG، PNG، TIFF و غیره یکی دیگر از موارد استفاده رایج است که بیشتر برای ایجاد تصاویر کوچک اسلایدها استفاده می شود. 
{{% blocks/products/pf/feature-page-code h3="کد تبدیل PHP PPT به JPG" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
 
$pres = new Presentation("input.pptx");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(1, 1);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPEG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>  
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-jpg pptx-to-jpg ppt-to-png pptx-to-png ppt-to-gif pptx-to-gif" >}}