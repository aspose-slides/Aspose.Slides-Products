---
title: แปลง HTML เป็น XML ใน PHP
url: /th/php-java/conversion/html-to-xml/
keywords: HTML เป็น XML, แปลง HTML เป็น XML, PHP API, PHP Library, HTML, XML
description: แปลง HTML เป็น XML ใน PHP ใช้ PowerPoint PHP API เพื่อแปลงไฟล์ HTML เป็น XML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง HTML เป็น XML ใน PHP" h2="ไลบรารี PowerPoint PHP อันทรงพลังที่ช่วยในการพัฒนาแอปพลิเคชันด้วยความสามารถในการสร้าง รวม ตรวจสอบ หรือแปลงไฟล์งานนำเสนอ Microsoft PowerPoint และ OpenOffice โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Open Office, Adobe PDF" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง HTML เป็น XML ใน PHP" %}}

[**Aspose.Slides สำหรับ PHP ผ่าน Java**](https://products.aspose.com/slides/th/php-java/) เป็นไลบรารี PHP ที่มีประสิทธิภาพสำหรับการสร้างและจัดการไฟล์งานนำเสนอ นอกจากนี้ ยังมีวิธีที่ยืดหยุ่นในการแปลง HTML เป็น XML เมื่อใช้ **Aspose.Slides สำหรับ PHP ผ่าน Java** นักพัฒนาหรือแอปพลิเคชันใดๆ ก็สามารถแปลงไฟล์ HTML เป็น XML ด้วยโค้ด PHP เพียงไม่กี่บรรทัด

ในฐานะ API การประมวลผลเอกสารสมัยใหม่ Aspose.Slides สำหรับ PHP จะส่งออกไฟล์ HTML เป็นรูปแบบไฟล์ XML ได้อย่างรวดเร็ว ไลบรารี Aspose PowerPoint ช่วยให้คุณแปลง HTML เป็น XML และรูปแบบไฟล์อื่นๆ อีกมากมาย

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลง HTML เป็น XML โดยใช้ PHP" %}}
หากต้องการแปลง HTML เป็น XML คุณจะต้องสร้างงานนำเสนอจากไฟล์ HTML และบันทึกเป็น XML

{{% blocks/products/pf/agp/code-block title="โค้ด PHP สำหรับแปลง HTML เป็น XML" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
        
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $filename = 'file.html';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $pres->getSlides()->addFromHtml($contents);        
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

{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง HTML เป็น XML โดยใช้ Aspose.Slides สำหรับ PHP API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการแปลง HTML เป็น XML ใน PHP" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง [**Aspose.Slides สำหรับ PHP ผ่าน Java**](https://products.aspose.com/slides/th/php-java/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ในโครงการ PHP ของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เปิดไฟล์ต้นฉบับ HTML ใน PHP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์เป็นไฟล์ XML
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="ตัวแปลงออนไลน์ฟรี" sectionDescription="[วิธีแปลง PPT เป็น HTML ใน Python](https://products.aspose.com/slides/th/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="แปลง HTML เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง HTML และบันทึกเป็นรูปแบบไฟล์อื่นๆ ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}