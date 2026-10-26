---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ปลดล็อกไฟล์งานนำเสนอ PPT โดยใช้ Java
url: /th/java/unlock/ppt/
description: ลบรหัสผ่านและการป้องกันการเขียนออกจากงานนำเสนอ PPT ใน Java ด้วย Aspose.Slides for Java
keywords: ลบการป้องกันการเขียน PPT, ถอดรหัส PPT, ปลดล็อกงานนำเสนอ PPT, ยกเลิกการป้องกัน PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ปลดล็อก PPT โดยใช้ Java" h2="สร้างแอปพลิเคชัน Java ที่ลบรหัสผ่านและการป้องกันการเขียนออกจากไฟล์งานนำเสนอด้วย API ฝั่งเซิร์ฟเวอร์" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ลบการป้องกันออกจากงานนำเสนอ PPT ผ่าน Java" variant="code" %}}

ด้วย [Aspose.Slides for Java](/slides/th/java/) คุณสามารถลบการเข้ารหัสหรือการป้องกันการเขียนออกจากงานนำเสนอ PPT ได้ ใช้ `LoadOptions.setPassword` เพื่อเปิดงานนำเสนอที่เข้ารหัส และใช้เมธอด `removeEncryption` และ `removeWriteProtection` ของ `ProtectionManager` เพื่อลบการตั้งค่าการป้องกัน

{{< blocks/products/pf/slides-design-update-10-2026/code title="ลบการป้องกันด้วยรหัสผ่านออกจาก PPT โดยใช้ Java" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.ppt", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="ลบการป้องกันการเขียนออกจากงานนำเสนอ PPT โดยใช้ Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีลบรหัสผ่านออกจาก PPT ผ่าน Java" intro="ทำตามขั้นตอนต่อไปนี้เพื่อลบการป้องกันออกจากงานนำเสนอ PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPT ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ใช้ `LoadOptions.setPassword` เมื่องานนำเสนอถูกเข้ารหัส{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียก `removeEncryption` หรือ `removeWriteProtection` จากออบเจ็กต์ `ProtectionManager`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกงานนำเสนอที่ปลดล็อกแล้วด้วย `SaveFormat.Ppt`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="สร้างด้วย Aspose.Slides" title="ปลดล็อกไฟล์ PPT ทางออนไลน์" description="แอป Aspose.Slides Unlock ฟรีนี้สร้างด้วย [Aspose.Slides for Java](https://products.aspose.com/slides/th/java/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPT ของคุณเอง" button="เปิด Aspose.Slides Unlock" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ลบการป้องกันอย่างไรก่อนเขียนโค้ด
- ลบรหัสผ่านหรือการป้องกันการเขียนออกจากไฟล์ PPT ของคุณ
- ดาวน์โหลดไฟล์ที่ปลดล็อกแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการปลดล็อก" subTitle="เมื่อใช้ Java คุณยังลบการป้องกันออกจากรูปแบบต่อไปนี้ได้ด้วย" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
