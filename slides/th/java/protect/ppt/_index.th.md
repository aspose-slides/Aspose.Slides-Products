---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ป้องกันไฟล์งานนำเสนอ PPT โดยใช้ Java
url: /th/java/protect/ppt/
description: ป้องกันงานนำเสนอ PPT ใน Java ใช้ Aspose.Slides for Java เพื่อเข้ารหัสไฟล์งานนำเสนอและตั้งค่าการป้องกันการเขียน
keywords: การป้องกันการเขียน PPT, เข้ารหัสไฟล์ PPT, ล็อกงานนำเสนอ PPT, ป้องกัน PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ล็อกหรือป้องกัน PPT ด้วยรหัสผ่านโดยใช้ Java" h2="สร้างแอปพลิเคชัน Java ที่ป้องกันไฟล์งานนำเสนอด้วย API ฝั่งเซิร์ฟเวอร์" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ป้องกันงานนำเสนอ PPT ผ่าน Java" variant="code" %}}

ด้วย [Aspose.Slides for Java](/slides/th/java/) คุณสามารถป้องกันไม่ให้งานนำเสนอ PPT ถูกเปิดหรือแก้ไขได้โดยตั้งรหัสผ่าน ใช้ออบเจ็กต์ `ProtectionManager` จากคลาส `Presentation` เพื่อเรียกเมธอดต่าง ๆ เช่น `encrypt` และ `setWriteProtection`

{{< blocks/products/pf/slides-design-update-10-2026/code title="เข้ารหัสงานนำเสนอ PPT โดยใช้ Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="ตั้งค่าการป้องกันการเขียนให้งานนำเสนอ PPT โดยใช้ Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีป้องกัน PPT ด้วยรหัสผ่านผ่าน Java" intro="ทำตามขั้นตอนต่อไปนี้เพื่อป้องกันงานนำเสนอ PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPT ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกเมธอด `encrypt` หรือเมธอด `setWriteProtection` จากออบเจ็กต์ `ProtectionManager`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ที่ป้องกันแล้วด้วย `SaveFormat.Ppt`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="สร้างด้วย Aspose.Slides" title="ป้องกันไฟล์ PPT ด้วยรหัสผ่านทางออนไลน์" description="แอป Aspose.Slides Lock ฟรีนี้สร้างด้วย [Aspose.Slides for Java](https://products.aspose.com/slides/th/java/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPT ของคุณเอง" button="เปิด Aspose.Slides Lock" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ป้องกันงานนำเสนออย่างไรก่อนเขียนโค้ด
- ตั้งรหัสผ่านสำหรับเปิดหรือแก้ไขไฟล์ PPT ของคุณ
- ดาวน์โหลดไฟล์ที่ป้องกันแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการป้องกัน" subTitle="เมื่อใช้ Java คุณยังป้องกันรูปแบบต่อไปนี้ได้ด้วย" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
