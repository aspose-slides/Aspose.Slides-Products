---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ป้องกันไฟล์งานนำเสนอ PPTX ด้วย .NET
url: /th/net/protect/pptx/
description: ซอร์สโค้ด C# สำหรับป้องกันงานนำเสนอ PPTX ด้วยรหัสผ่าน
keywords: การป้องกันการเขียน PPTX, เข้ารหัส PPTX, ล็อกงานนำเสนอ PPTX, ป้องกัน PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ล็อกหรือป้องกันไฟล์ PPTX ด้วยรหัสผ่านโดยใช้ C#" h2="สร้างแอป .NET ที่เข้ารหัสงานนำเสนอและจำกัดการแก้ไขด้วย API ฝั่งเซิร์ฟเวอร์" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ป้องกันงานนำเสนอ PPTX โดยใช้ C#" variant="code" %}}

ด้วย [Aspose.Slides for .NET](/slides/th/net/) คุณสามารถเข้ารหัสงานนำเสนอ PPTX หรือจำกัดการแก้ไขด้วยรหัสผ่าน การเปิดงานนำเสนอที่เข้ารหัสด้วย `ProtectionManager.Encrypt` ต้องใช้รหัสผ่าน ใช้ `ProtectionManager.SetWriteProtection` เพื่อให้เปิดงานนำเสนอได้แต่จำกัดการเปลี่ยนแปลง

{{< blocks/products/pf/slides-design-update-10-2026/code title="เข้ารหัสงานนำเสนอ PPTX โดยใช้ C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="ตั้งค่าการป้องกันการเขียนให้งานนำเสนอ PPTX โดยใช้ C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีป้องกันงานนำเสนอ PPTX ด้วยรหัสผ่านโดยใช้ C#" intro="ทำตามขั้นตอนต่อไปนี้เพื่อป้องกันงานนำเสนอ PPTX ด้วยรหัสผ่าน" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPTX ด้วย `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เข้ารหัสงานนำเสนอด้วย `ProtectionManager.Encrypt` หรือจำกัดการเปลี่ยนแปลงด้วย `ProtectionManager.SetWriteProtection`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ที่ป้องกันแล้วด้วย `SaveFormat.Pptx`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="สร้างด้วย Aspose.Slides" title="ป้องกันไฟล์ PPTX ด้วยรหัสผ่านทางออนไลน์" description="แอป Aspose.Slides Lock ฟรีนี้สร้างด้วย [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Lock" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ป้องกันงานนำเสนออย่างไรก่อนเขียนโค้ด
- ตั้งรหัสผ่านสำหรับเปิดหรือแก้ไขไฟล์ PPTX ของคุณ
- ดาวน์โหลดไฟล์ที่ป้องกันแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการป้องกัน" subTitle="เมื่อใช้ C# คุณยังป้องกันรูปแบบต่อไปนี้ได้ด้วย" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
