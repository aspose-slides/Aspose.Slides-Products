---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง PPTX เป็น SWF ใน PHP
weight: 2710
url: /th/php-java/conversion/pptx-to-swf/ 
keywords: "Convert, PowerPoint, PPTX, SWF, Presentation, PHP"
description: โค้ดตัวอย่างสำหรับการแปลง PPTX เป็น SWF PHP ใช้ PowerPoint PHP API สำหรับการแปลงไฟล์เป็นชุด PPTX เป็นไฟล์ SWF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง PPTX เป็น SWF ใน PHP" h2="ไลบรารี PowerPoint PHP อันทรงพลังสำหรับการแปลง PPTX เป็น SWF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง PPTX เป็น SWF ใน PHP" %}}

ต้องการแปลงไฟล์ PPTX เป็น SWF โดยทางโปรแกรมหรือไม่ การใช้ [*Aspose.Slides สำหรับ PHP ผ่าน Java*](https://products.aspose.com/slides/th/php-java/) นักพัฒนาซอฟต์แวร์ทุกคนสามารถแปลงรูปแบบ PPTX เป็น SWF ด้วยโค้ด PHP เพียงไม่กี่บรรทัด .

ในฐานะที่เป็น API การประมวลผลการนำเสนอที่ทันสมัย ​​Aspose.Slides สำหรับ PHP จะสร้าง SWF จาก PPTX อย่างรวดเร็ว ทดสอบคุณภาพของการแปลงจาก PPTX เป็น SWF ใน [เบราว์เซอร์](https://products.aspose.app/slides/conversion) Aspose ไลบรารี PowerPoint PPTX ช่วยให้คุณสามารถแปลงไฟล์ PPTX เป็นรูปแบบยอดนิยมได้มากมาย

คุณติดตั้งไลบรารีได้จาก [Composer](https://packagist.org/packages/aspose/slides) โดยใช้คำสั่งต่อไปนี้

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="คอนโซล/เทอร์มินัล" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="บันทึก PPTX เป็น SWF ใน PHP" %}}

ใช้แอปฟรีเพื่อดูการสาธิตกระบวนการแปลงจาก PPTX เป็น SWF

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="โค้ดตัวอย่างนี้แสดง PPTX ถึง SWF PHP Conversion" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pptx");
try
{
    $pres->save("output.swf", SaveFormat::Swf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแปลง PPTX เป็น SWF ใน PHP" intro="นี่คือขั้นตอนในการแปลงไฟล์ PPTX เป็น SWF โดยใช้ PHP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPTX ด้วยตัวอย่างของ Presentation class{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกเมธอด `save` ขณะที่ระบุพาธไฟล์เอาต์พุต & SaveFormat.SWF เป็นพารามิเตอร์{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX ไฟล์จะถูกบันทึกที่เส้นทางที่ระบุ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="ความต้องการของระบบ" intro="ก่อนรันซอร์สโค้ดตัวอย่างการแปลง PHP ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง PHP 7 เพิ่มพาธไปยัง PHP ให้กับตัวแปร `PATH` ของระบบ และตั้งค่า `allow_url_include` เป็น `On` ในไฟล์ `php.ini`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง JRE 8. ตั้งค่าตัวแปรสภาพแวดล้อม `JAVA_HOME` เป็นพาธไปยังตำแหน่ง JRE ที่ติดตั้ง{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง Apache Tomcat 8.0 (ดู [เพิ่มเติม](https://docs.aspose.com/slides/php-java/installation/)){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="สร้างด้วย Aspose.Slides" title="แปลง PPTX เป็น SWF ออนไลน์" description="แอป Aspose.Slides Conversion ฟรีนี้สร้างด้วย [Aspose.Slides for PHP via Java](https://products.aspose.com/slides/th/php-java/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Conversion" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" upload="วางหรืออัปโหลดไฟล์ของคุณ" saveAs="บันทึกเป็น" convert="แปลง" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides แปลงไฟล์อย่างไรก่อนที่คุณจะเขียนโค้ด
- อัปโหลดไฟล์ PPTX แล้วบันทึกเป็น SWF
- ดาวน์โหลดผลลัพธ์หรือแปลงไฟล์เพิ่มเติม
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PPTX เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย ดูคอนเวอร์ชั่นอื่นที่รองรับด้านล่าง" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="ภาพบิตแมป" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-fodp/" name="PPTX TO FODP" description="การนำเสนอ OpenDocument Flat XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-gif/" name="PPTX TO GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-html/" name="PPTX TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-jpg/" name="PPTX TO JPG" description="ภาพ JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-odp/" name="PPTX TO ODP" description="รูปแบบการนำเสนอ OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-otp/" name="PPTX TO OTP" description="รูปแบบมาตรฐานของ OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="รูปแบบเอกสารพกพา" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-png/" name="PPTX TO PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-pot/" name="PPTX TO POT" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-potm/" name="PPTX TO POTM" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-potx/" name="PPTX TO POTX" description="การนำเสนอเทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-pps/" name="PPTX TO PPS" description="สไลด์โชว์ PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="สไลด์โชว์ที่เปิดใช้งานมาโคร" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="สไลด์โชว์ PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="ไฟล์นำเสนอที่เปิดใช้งานมาโคร" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-svg/" name="PPTX TO SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/pptx-to-xps/" name="PPTX TO XPS" description="ข้อมูลจำเพาะกระดาษ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
