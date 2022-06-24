---
title: การแปลงงานนำเสนอ Microsoft PowerPoint เป็น PDF ใน PHP
url: /th/php-java/conversion/
keyslides: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: PHP API เพื่อแปลง PPT เป็น PDF แปลงงานนำเสนอเป็น JPG, PNG และรูปแบบอื่นๆ ใน PHP
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> การนำเสนอ PowerPoint เป็นการแปลง PDF ใน PHP" h2="ซอร์สโค้ด PHP สำหรับกรณีการแปลงต่างๆ เพื่อแปลง PPT เป็น PDF, PNG, HTML, JPEG, PPTX และรูปแบบอื่นๆ" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides สำหรับ PHP ผ่าน Java](https://products.aspose.com/slides/th/php-java/) เป็นไลบรารีคลาสภายในองค์กรที่มีประสิทธิภาพซึ่งใช้สำหรับการประมวลผลและทำงานกับงานนำเสนอ นักพัฒนาสามารถแปลง PowerPoint เป็น PDF ได้อย่างรวดเร็วและแม่นยำ รับผลลัพธ์ภายในเวลาไม่นานสำหรับกระบวนการทางธุรกิจอัตโนมัติ เรากำลังพูดถึงบางกรณีที่จะอ่านหรือโหลดอินพุตใดๆ [รูปแบบ PowerPoint ที่รองรับ](https://docs.aspose.com/slides/php-java/supported-file-formats/) และเขียนหรือบันทึกเป็นรูปแบบเอาต์พุตที่รองรับ . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="การแปลง PowerPoint เป็น PDF ใน PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/th/php-java/) ให้คุณแปลงไฟล์ในรูปแบบ PowerPoint PPT, PPTX และ OpenOffice ODP เป็น PDF ในการแปลงงานนำเสนอเป็น PDF เพียงส่งชื่อไฟล์และบันทึกรูปแบบไปยังวิธี 'Presentation.save' คลาส 'การนำเสนอ' เปิดเผยวิธีการ 'บันทึก' ที่สามารถเรียกให้แปลงงานนำเสนอ PPT, PPTX หรือ ODP ทั้งหมดเป็นเอกสาร PDF

{{% blocks/products/pf/feature-page-code h3="การแปลง PHP PowerPoint เป็น PDF" %}}

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

{{% blocks/products/pf/feature-page-section  h2="การแปลง PDF เป็น PPT ใน PHP" %}}
[Aspose.Slides](https://products.aspose.com/slides/th/php-java/) ให้คุณนำเข้างานนำเสนอจาก PDF ได้ โดยพื้นฐานแล้ว คุณจะต้องแปลง PDF เป็นงานนำเสนอ PowerPoint ในการแปลง PDF เป็น Powerpoint ให้ทำตามขั้นตอนเหล่านี้:
- ยกตัวอย่างวัตถุของคลาส 'การนำเสนอ'
- เรียกใช้เมธอด `addFromPdf และส่งไฟล์ PDF
- ใช้วิธี "บันทึก" เพื่อบันทึกไฟล์ในรูปแบบ PowerPoint

{{% blocks/products/pf/feature-page-code h3="PHP PDF เป็น Powerpoint Conversion" %}}

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


{{% blocks/products/pf/feature-page-section  h2="แปลง PPT เป็น PDF ด้วยตัวเลือกที่กำหนดเองใน PHP" %}}

สำหรับการแปลงสไลด์ PowerPoint เป็น PDF อย่างแม่นยำ โปรแกรมเมอร์สามารถโหลดเอกสารโดยใช้คลาส 'Presentation' และใช้คลาส 'PdfOptions' สำหรับตัวเลือกเฉพาะและกำหนดเองทั้งหมด เช่น ระดับการบีบอัดข้อความ คุณภาพ Jpeg การทำงานของ metafiles การแปลงสไลด์ที่ซ่อนอยู่ รวมถึงการเลือก สไลด์เฉพาะและอื่นๆ มีตัวเลือกในการป้องกันไฟล์ PDF ที่แปลงแล้วด้วยรหัสผ่าน
{{% blocks/products/pf/feature-page-code h3="การแปลง PHP PowerPoint เป็น PDF ด้วยการตั้งค่าที่กำหนดเอง" %}}

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


{{% blocks/products/pf/feature-page-section  h2="การแปลง Microsoft PowerPoint เป็น HTML ใน PHP" %}}
เมื่อจำเป็นต้องฝังงานนำเสนอภายในหน้าเว็บ ก็จำเป็นต้องแปลงสไลด์เป็น HTML 
{{% blocks/products/pf/feature-page-code h3="โค้ด PHP สำหรับการแปลง PowerPoint เป็น HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="แปลง PowerPoint เป็น JPG" %}}
การแปลงรูปแบบ Microsoft<sup>®</sup> PowerPoint เป็นรูปภาพ JPEG, PNG, TIFF เป็นต้น เป็นอีกกรณีการใช้งานทั่วไปที่ใช้สำหรับสร้างภาพขนาดย่อของสไลด์เป็นส่วนใหญ่ 
{{% blocks/products/pf/feature-page-code h3="PHP PPT เป็น JPG Converter Code" %}}
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