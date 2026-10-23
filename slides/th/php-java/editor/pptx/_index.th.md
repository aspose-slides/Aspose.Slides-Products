---
lastmod: 2023-02-06
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แก้ไข PPTX ใน PHP
url: /th/php-java/editor/pptx/
keywords: แก้ไข PPTX, แก้ไข PowerPoint, PPTX, PowerPoint, PHP API, PHP Library
description: แก้ไข PPTX ใน PHP ใช้ PHP library API เพื่อแก้ไขไฟล์ PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แก้ไข PPTX ใน PHP" h2="ไลบรารี PHP ข้ามแพลตฟอร์มความเร็วสูงสำหรับแก้ไข PPTX โดยใช้โค้ด PHP" related="FODP,HTML,ODP,OTP,PDF,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แก้ไข PPTX ใน PHP" variant="code" %}}

เมื่อใช้ [**Aspose.Slides สำหรับ PHP ผ่าน Java**](https://products.aspose.com/slides/th/php-java/) คุณสามารถเพิ่มข้อความบรรทัดใหม่ลงในเอกสาร PPTX โดยใช้เพียง รหัสไม่กี่บรรทัด

{{< blocks/products/pf/slides-design-update-10-2026/code title="โค้ด PHP สำหรับแก้ไข PPTX" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptx");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.pptx", SaveFormat::Pptx);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แก้ไข PPTX โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ PHP ผ่าน Java**](https://products.aspose.com/slides/th/php-java/) เป็นไลบรารี PHP ที่ทรงพลังสำหรับการแก้ไขงานนำเสนออย่างรวดเร็วและง่ายดาย ให้ผู้ใช้มีคุณสมบัติที่หลากหลายเพื่อช่วยให้พวกเขาสร้างสไลด์ที่ดูเป็นมืออาชีพในเวลาไม่นาน เมื่อใช้ Aspose ผู้ใช้สามารถแก้ไขข้อความ เพิ่มรูปภาพ ภาพเคลื่อนไหว และการเปลี่ยนผ่านไปยังงานนำเสนอ ตลอดจนใช้ตัวเลือกการจัดรูปแบบต่างๆ เช่น แบบอักษรและการเลือกสี นอกจากนี้ ไลบรารียังให้การสนับสนุนทั้งไฟล์ PowerPoint (PPT) และรูปแบบ OpenOffice Presentation (ODP) ซึ่งช่วยให้แชร์งานนำเสนอบนแพลตฟอร์มต่างๆ ได้ง่ายกว่าที่เคย โดยไม่มีปัญหาความเข้ากันได้ใดๆ เกิดขึ้น ด้วยการใช้พลังของไลบรารีของ Aspose เมื่อสร้างหรือแก้ไขงานนำเสนอครั้งต่อไป คุณจะมั่นใจได้ว่าสไลด์ของคุณจะดูดีทุกครั้ง!
คุณแก้ไขไฟล์ PPTX ได้โดยเพิ่มข้อความบรรทัดใหม่

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแก้ไข PPTX ใน PHP" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง **Aposose.Slides สำหรับ PHP ผ่าน Java** ดู [**การติดตั้ง**](https://docs.aspose.com/slides/php-java/installation/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างอินสแตนซ์ของคลาสการนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดงานนำเสนอ PPTX ที่คุณต้องการแก้ไข{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มบรรทัดใหม่ของข้อความ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ที่เปลี่ยนแปลง{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="สร้างด้วย Aspose.Slides" title="แก้ไขไฟล์ PPTX ออนไลน์" description="แอป Aspose.Slides Editor ฟรีนี้สร้างด้วย [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/th/php-java/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Editor" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides จัดการไฟล์ของคุณอย่างไรก่อนเขียนโค้ด
- อัปโหลดไฟล์ PPTX แล้วแก้ไขได้ทันที
- บันทึกและดาวน์โหลดไฟล์ที่แก้ไขแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="แก้ไขไฟล์อื่นๆ" subTitle="คุณยังสามารถแก้ไขไฟล์ในรูปแบบอื่นๆ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/editor/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/editor/pptm/" name="PPTM" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
