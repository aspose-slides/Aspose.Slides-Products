---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ปลดล็อกไฟล์งานนำเสนอ ODP ด้วย .NET
url: /th/net/unlock/odp/
description: ซอร์สโค้ด C# สำหรับลบการป้องกันด้วยรหัสผ่านออกจากงานนำเสนอ ODP
keywords: ลบการป้องกันการเขียน ODP, ถอดรหัส ODP, ปลดล็อกงานนำเสนอ ODP, ยกเลิกการป้องกัน ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ปลดล็อกไฟล์ ODP โดยใช้ C#" h2="สร้างแอป .NET ที่ลบการเข้ารหัสและการป้องกันการเขียนออกจากงานนำเสนอด้วย API ฝั่งเซิร์ฟเวอร์" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ลบการป้องกันออกจากงานนำเสนอ ODP โดยใช้ C#" variant="code" %}}

ด้วย [Aspose.Slides for .NET](/slides/th/net/) คุณสามารถลบการเข้ารหัสหรือการป้องกันการเขียนออกจากงานนำเสนอ ODP ได้ หากต้องการลบการเข้ารหัส ให้โหลดงานนำเสนอด้วยรหัสผ่านที่ถูกต้องแล้วเรียก `ProtectionManager.RemoveEncryption` หากต้องการลบการป้องกันการเขียน ให้เรียก `ProtectionManager.RemoveWriteProtection`

{{< blocks/products/pf/slides-design-update-10-2026/code title="ลบการเข้ารหัสออกจากงานนำเสนอ ODP โดยใช้ C#" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.odp", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="ลบการป้องกันการเขียนออกจากงานนำเสนอ ODP โดยใช้ C#" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.odp");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีลบการป้องกันออกจากงานนำเสนอ ODP โดยใช้ C#" intro="ทำตามขั้นตอนต่อไปนี้เพื่อลบการป้องกันออกจากงานนำเสนอ ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ ODP ด้วย `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สำหรับไฟล์ที่เข้ารหัส ให้ระบุรหัสผ่านผ่าน `LoadOptions.Password` ก่อนโหลด{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียก `ProtectionManager.RemoveEncryption` หรือ `ProtectionManager.RemoveWriteProtection` ตามการป้องกันที่ใช้อยู่{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกงานนำเสนอที่ปลดล็อกแล้วด้วย `SaveFormat.Odp`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="สร้างด้วย Aspose.Slides" title="ปลดล็อกไฟล์ ODP ทางออนไลน์" description="แอป Aspose.Slides Unlock ฟรีนี้สร้างด้วย [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ ODP ของคุณเอง" button="เปิด Aspose.Slides Unlock" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ลบการป้องกันอย่างไรก่อนเขียนโค้ด
- ลบรหัสผ่านหรือการป้องกันการเขียนออกจากไฟล์ ODP ของคุณ
- ดาวน์โหลดไฟล์ที่ปลดล็อกแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการปลดล็อก" subTitle="เมื่อใช้ C# คุณยังลบการป้องกันออกจากรูปแบบต่อไปนี้ได้ด้วย" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
