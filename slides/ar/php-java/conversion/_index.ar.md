---
title: تحويل Microsoft PowerPoint Presentation إلى PDF في PHP
url: /ar/php-java/conversion/
keyslides: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API لتحويل PPT إلى PDF. تحويل العروض التقديمية إلى JPG و PNG وتنسيقات أخرى في PHP.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> ® </sup> عرض تقديمي من PowerPoint لتحويل PDF في PHP" h2="أكواد PHP المصدر لحالات التحويل المختلفة لتحويل PPT إلى PDF و PNG و HTML و JPEG و PPTX وتنسيقات أخرى." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides for PHP via Java](https://products.aspose.com/slides/ar/php-java/) هي مكتبة فصلية قوية في مقر الشركة تُستخدم لمعالجة العروض التقديمية والعمل معها. من السهل على المطورين تحويل PowerPoint إلى PDF بسرعة ودقة. احصل على النتائج في أي وقت من الأوقات لأتمتة عمليات الأعمال. نناقش هنا حالات قليلة لقراءة أو تحميل أي إدخال [تنسيقات PowerPoint مدعومة](https://docs.aspose.com/slides/php-java/supported-file-formats/) والكتابة أو الحفظ بأي تنسيق إخراج مدعوم . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل PowerPoint إلى PDF في PHP" %}}
يتيح لك [Aspose.Slides](https://products.aspose.com/slides/ar/php-java/) تحويل الملفات بتنسيقات PowerPoint PPT و PPTX و OpenOffice ODP إلى PDF. لتحويل عرض تقديمي إلى PDF ، ما عليك سوى تمرير اسم الملف وحفظ التنسيق إلى طريقة "Presentation.save". تعرض فئة "العرض التقديمي" طريقة "الحفظ" التي يمكن استدعاؤها لتحويل عرض PPT أو PPTX أو ODP بالكامل إلى مستند PDF.

{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint لتحويل PDF" %}}

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

{{% blocks/products/pf/feature-page-section  h2="تحويل PDF إلى PPT في PHP" %}}
يسمح لك [Aspose.Slides](https://products.aspose.com/slides/ar/php-java/) باستيراد العروض التقديمية من ملفات PDF. بشكل أساسي ، يمكنك تحويل ملف PDF إلى عرض تقديمي في PowerPoint. لتحويل PDF إلى Powerpoint ، اتبع الخطوات التالية:
- إنشاء كائن من فئة "العرض التقديمي".
- قم باستدعاء طريقة "addFromPdf" وقم بتمرير ملف PDF.
- استخدم طريقة "الحفظ" لحفظ الملف بتنسيق PowerPoint.

{{% blocks/products/pf/feature-page-code h3="PHP PDF لتحويل Powerpoint" %}}

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


{{% blocks/products/pf/feature-page-section  h2="قم بتحويل PPT إلى PDF بخيارات مخصصة في PHP" %}}

لتحويل شرائح PowerPoint إلى PDF بدقة ، يمكن للمبرمجين تحميل المستند باستخدام فئة "العرض التقديمي" واستخدام فئة "PdfOptions" لجميع الخيارات المحددة والمخصصة مثل مستوى ضغط النص وجودة Jpeg وسلوك ملفات التعريف وتحويل الشرائح المخفية بالإضافة إلى التحديد شرائح محددة والمزيد. حتى أن هناك خيارًا لحماية ملف PDF المحول بكلمة مرور.
{{% blocks/products/pf/feature-page-code h3="PHP PowerPoint لتحويل PDF مع إعدادات مخصصة" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint إلى تحويل HTML في PHP" %}}
عندما تكون هناك حاجة لتضمين العروض التقديمية في صفحات الويب ، فهناك حاجة لتحويل الشرائح إلى HTML. 
{{% blocks/products/pf/feature-page-code h3="كود PHP لتحويل PowerPoint إلى HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="تحويل PowerPoint إلى JPG" %}}
يعد تحويل تنسيقات PowerPoint <sup> ® </sup> Microsoft إلى صور JPEG و PNG و TIFF وما إلى ذلك حالة استخدام شائعة أخرى تُستخدم غالبًا لإنشاء صور مصغرة للشرائح. 
{{% blocks/products/pf/feature-page-code h3="كود تحويل PHP PPT إلى JPG" %}}
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