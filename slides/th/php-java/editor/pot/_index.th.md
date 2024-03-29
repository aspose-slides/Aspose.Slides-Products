---
title: แก้ไข POT ใน PHP
url: /th/php-java/editor/pot/
keywords: แก้ไข POT, แก้ไข PowerPoint, POT, PowerPoint, PHP API, PHP Library
description: แก้ไข POT ใน PHP ใช้ PHP library API เพื่อแก้ไขไฟล์ POT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แก้ไข POT ใน PHP" h2="ไลบรารี PHP ข้ามแพลตฟอร์มความเร็วสูงสำหรับแก้ไข POT โดยใช้โค้ด PHP" >}}

{{% blocks/products/pf/feature-page-section h2="แก้ไข POT โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ PHP ผ่าน Java**](https://products.aspose.com/slides/th/php-java/) เป็นไลบรารี PHP ที่ทรงพลังสำหรับการแก้ไขงานนำเสนออย่างรวดเร็วและง่ายดาย ให้ผู้ใช้มีคุณสมบัติที่หลากหลายเพื่อช่วยให้พวกเขาสร้างสไลด์ที่ดูเป็นมืออาชีพในเวลาไม่นาน เมื่อใช้ Aspose ผู้ใช้สามารถแก้ไขข้อความ เพิ่มรูปภาพ ภาพเคลื่อนไหว และการเปลี่ยนผ่านไปยังงานนำเสนอ ตลอดจนใช้ตัวเลือกการจัดรูปแบบต่างๆ เช่น แบบอักษรและการเลือกสี นอกจากนี้ ไลบรารียังให้การสนับสนุนทั้งไฟล์ PowerPoint (PPT) และรูปแบบ OpenOffice Presentation (ODP) ซึ่งช่วยให้แชร์งานนำเสนอบนแพลตฟอร์มต่างๆ ได้ง่ายกว่าที่เคย โดยไม่มีปัญหาความเข้ากันได้ใดๆ เกิดขึ้น ด้วยการใช้พลังของไลบรารีของ Aspose เมื่อสร้างหรือแก้ไขงานนำเสนอครั้งต่อไป คุณจะมั่นใจได้ว่าสไลด์ของคุณจะดูดีทุกครั้ง!
คุณแก้ไขไฟล์ POT ได้โดยเพิ่มข้อความบรรทัดใหม่ 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แก้ไข POT ใน PHP" %}}
เมื่อใช้ [**Aspose.Slides สำหรับ PHP ผ่าน Java**](https://products.aspose.com/slides/th/php-java/) คุณสามารถเพิ่มข้อความบรรทัดใหม่ลงในเอกสาร POT โดยใช้เพียง รหัสไม่กี่บรรทัด

{{% blocks/products/pf/agp/code-block title="โค้ด PHP สำหรับแก้ไข POT" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pot");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.pot", SaveFormat::Pot);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีแก้ไข POT ใน PHP" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง **Aposose.Slides สำหรับ PHP ผ่าน Java** ดู [**การติดตั้ง**](https://docs.aspose.com/slides/php-java/installation/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
สร้างอินสแตนซ์ของคลาสการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดงานนำเสนอ POT ที่คุณต้องการแก้ไข
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มบรรทัดใหม่ของข้อความ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกไฟล์ที่เปลี่ยนแปลง
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="แก้ไขไฟล์อื่นๆ" subTitle="คุณยังสามารถแก้ไขไฟล์ในรูปแบบอื่นๆ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}