---
title: แปลง PDF เป็น XML ใน PHP
url: /th/php-java/conversion/pdf-to-xml/
keywords: PDF เป็น XML, แปลง PDF เป็น XML, PHP API, PHP Library, PDF, XML
description: แปลง PDF เป็น XML ใน PHP ใช้ PowerPoint PHP API เพื่อแปลงไฟล์ PDF เป็น XML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง PDF เป็น XML ใน PHP" h2="ไลบรารี PowerPoint PHP อันทรงพลังที่ช่วยในการพัฒนาแอปพลิเคชันด้วยความสามารถในการสร้าง รวม ตรวจสอบ หรือแปลงไฟล์งานนำเสนอ Microsoft PowerPoint และ OpenOffice โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Open Office, Adobe PDF" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง PDF เป็น XML ใน PHP" %}}

[**Aspose.Slides สำหรับ PHP ผ่าน Java**](https://products.aspose.com/slides/th/php-java/) เป็นไลบรารี PHP ที่มีประสิทธิภาพสำหรับการสร้างและจัดการไฟล์งานนำเสนอ นอกจากนี้ ยังมีวิธีที่ยืดหยุ่นในการแปลง PDF เป็น XML เมื่อใช้ **Aspose.Slides สำหรับ PHP ผ่าน Java** นักพัฒนาหรือแอปพลิเคชันใดๆ ก็สามารถแปลงไฟล์ PDF เป็น XML ด้วยโค้ด PHP เพียงไม่กี่บรรทัด

ในฐานะ API การประมวลผลเอกสารสมัยใหม่ Aspose.Slides สำหรับ PHP จะส่งออกไฟล์ PDF เป็นรูปแบบไฟล์ XML ได้อย่างรวดเร็ว ไลบรารี Aspose PowerPoint ช่วยให้คุณแปลง PDF เป็น XML และรูปแบบไฟล์อื่นๆ อีกมากมาย

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลง PDF เป็น XML โดยใช้ PHP" %}}
หากต้องการแปลง PDF เป็น XML คุณจะต้องสร้างงานนำเสนอจากไฟล์ PDF และบันทึกเป็น XML

{{% blocks/products/pf/agp/code-block title="โค้ด PHP สำหรับแปลง PDF เป็น XML" offSpacer="true" %}}

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
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $slide = $pres->getSlides()->get_Item($i);
        $javafos = new Java("java.io.FileOutputStream", "slide_". $i .".xml");
        $slide->writeAsSvg($javafos);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง PDF เป็น XML โดยใช้ Aspose.Slides สำหรับ PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการแปลง PDF เป็น XML ใน PHP" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง [**Aspose.Slides สำหรับ PHP ผ่าน Java**](https://products.aspose.com/slides/th/php-java/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ในโครงการ PHP ของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เปิดไฟล์ต้นฉบับ PDF ใน PHP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์เป็นไฟล์ XML
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="ตัวแปลงออนไลน์ฟรี" sectionDescription="[วิธีแปลง PPT เป็น HTML ใน Python](https://products.aspose.com/slides/th/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="แปลง PDF เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง PDF และบันทึกเป็นรูปแบบไฟล์อื่นๆ ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}