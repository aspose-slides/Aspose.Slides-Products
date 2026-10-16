---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง PPT เป็น PPTX ใน PHP
weight: 2270
url: /th/php-java/conversion/ppt-to-pptx/ 
keywords: "Convert, PowerPoint, PPT, PPTX, Presentation, PHP"
description: โค้ดตัวอย่างสำหรับการแปลง PPT เป็น PPTX PHP ใช้ PowerPoint PHP API สำหรับการแปลงไฟล์เป็นชุด PPT เป็นไฟล์ PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง PPT เป็น PPTX ใน PHP" h2="ไลบรารี PowerPoint PHP อันทรงพลังสำหรับการแปลง PPT เป็น PPTX"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง PPT เป็น PPTX ใน PHP" %}}

ต้องการแปลงไฟล์ PPT เป็น PPTX โดยทางโปรแกรมหรือไม่ การใช้ [*Aspose.Slides สำหรับ PHP ผ่าน Java*](https://products.aspose.com/slides/th/php-java/) นักพัฒนาซอฟต์แวร์ทุกคนสามารถแปลงรูปแบบ PPT เป็น PPTX ด้วยโค้ด PHP เพียงไม่กี่บรรทัด .

ในฐานะที่เป็น API การประมวลผลการนำเสนอที่ทันสมัย ​​Aspose.Slides สำหรับ PHP จะสร้าง PPTX จาก PPT อย่างรวดเร็ว ทดสอบคุณภาพของการแปลงจาก PPT เป็น PPTX ใน [เบราว์เซอร์](https://products.aspose.app/slides/conversion) Aspose ไลบรารี PowerPoint PPTX ช่วยให้คุณสามารถแปลงไฟล์ PPT เป็นรูปแบบยอดนิยมได้มากมาย

คุณติดตั้งไลบรารีได้จาก [Composer](https://packagist.org/packages/aspose/slides) โดยใช้คำสั่งต่อไปนี้

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="คอนโซล/เทอร์มินัล" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="บันทึก PPT เป็น PPTX ใน PHP" %}}

ใช้แอปฟรีเพื่อดูการสาธิตกระบวนการแปลงจาก PPT เป็น PPTX

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="โค้ดตัวอย่างนี้แสดง PPT ถึง PPTX PHP Conversion" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    $pres->save("output.pptx", SaveFormat::Pptx);
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแปลง PPT เป็น PPTX ใน PHP" intro="นี่คือขั้นตอนในการแปลงไฟล์ PPT เป็น PPTX โดยใช้ PHP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPT ด้วยตัวอย่างของ Presentation class{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกเมธอด `save` ขณะที่ระบุพาธไฟล์เอาต์พุต & SaveFormat.PPTX เป็นพารามิเตอร์{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT ไฟล์จะถูกบันทึกที่เส้นทางที่ระบุ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="ความต้องการของระบบ" intro="ก่อนรันซอร์สโค้ดตัวอย่างการแปลง PHP ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง PHP 7 เพิ่มพาธไปยัง PHP ให้กับตัวแปร `PATH` ของระบบ และตั้งค่า `allow_url_include` เป็น `On` ในไฟล์ `php.ini`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง JRE 8. ตั้งค่าตัวแปรสภาพแวดล้อม `JAVA_HOME` เป็นพาธไปยังตำแหน่ง JRE ที่ติดตั้ง{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง Apache Tomcat 8.0 (ดู [เพิ่มเติม](https://docs.aspose.com/slides/php-java/installation/)){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert PPT to PPTX"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PPT เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย ดูคอนเวอร์ชั่นอื่นที่รองรับด้านล่าง" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-bmp/" name="PPT TO BMP" description="ภาพบิตแมป" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-fodp/" name="PPT TO FODP" description="การนำเสนอ OpenDocument Flat XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-gif/" name="PPT TO GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-html/" name="PPT TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-jpg/" name="PPT TO JPG" description="ภาพ JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-odp/" name="PPT TO ODP" description="รูปแบบการนำเสนอ OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-otp/" name="PPT TO OTP" description="รูปแบบมาตรฐานของ OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-pdf/" name="PPT TO PDF" description="รูปแบบเอกสารพกพา" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-png/" name="PPT TO PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-pot/" name="PPT TO POT" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-potm/" name="PPT TO POTM" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-potx/" name="PPT TO POTX" description="การนำเสนอเทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-pps/" name="PPT TO PPS" description="สไลด์โชว์ PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="สไลด์โชว์ที่เปิดใช้งานมาโคร" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="สไลด์โชว์ PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="ไฟล์นำเสนอที่เปิดใช้งานมาโคร" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-svg/" name="PPT TO SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-swf/" name="PPT TO SWF" description="รูปแบบ SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/php-java/conversion/ppt-to-xps/" name="PPT TO XPS" description="ข้อมูลจำเพาะกระดาษ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
