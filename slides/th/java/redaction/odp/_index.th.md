---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ปกปิดข้อมูลในไฟล์งานนำเสนอ ODP ด้วย Java
url: /th/java/redaction/odp/
description: ค้นหาและแทนที่ข้อความในงานนำเสนอ ODP ด้วย Java โดยใช้ Aspose.Slides for Java
keywords: ปกปิดข้อมูล ODP, ค้นหาและแทนที่ข้อความใน ODP, อัปเดตงานนำเสนอ ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ปกปิดข้อมูลใน ODP ด้วย Java" h2="สร้างแอปพลิเคชัน Java ที่ค้นหาและแทนที่ข้อความในไฟล์งานนำเสนอด้วย API ฝั่งเซิร์ฟเวอร์" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ปกปิดข้อมูลในงานนำเสนอ ODP ผ่าน Java" variant="code" %}}

ด้วย [Aspose.Slides for Java](/slides/th/java/) คุณสามารถค้นหาและแทนที่ข้อความในงานนำเสนอ ODP ได้ ใช้เมธอด `SlideUtil.findAndReplaceText` เพื่อค้นหาในงานนำเสนอและแทนที่ข้อความที่ตรงกันด้วยค่าใหม่

{{< blocks/products/pf/slides-design-update-10-2026/code title="ปกปิดข้อมูลในงานนำเสนอ ODP โดยใช้ Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีปกปิดข้อมูลใน ODP ผ่าน Java" intro="ทำตามขั้นตอนต่อไปนี้เพื่อปกปิดข้อมูลในงานนำเสนอ ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ ODP ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกเมธอด `SlideUtil.findAndReplaceText` เพื่อค้นหาและแทนที่ข้อความ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกงานนำเสนอที่อัปเดตแล้วด้วย `SaveFormat.Odp`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="สร้างด้วย Aspose.Slides" title="ปกปิดข้อมูลในไฟล์ ODP ออนไลน์" description="แอป Aspose.Slides Redaction ฟรีนี้สร้างด้วย [Aspose.Slides for Java](https://products.aspose.com/slides/th/java/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ ODP ของคุณเอง" button="เปิด Aspose.Slides Redaction" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ค้นหาและแทนที่ข้อความอย่างไรก่อนเขียนโค้ด
- ค้นหาและแทนที่ข้อความในไฟล์ ODP ของคุณ รวมถึงด้วยนิพจน์ทั่วไป
- ดาวน์โหลดไฟล์ที่ปกปิดข้อมูลแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการปกปิดข้อมูล" subTitle="ด้วย Java คุณยังสามารถปกปิดข้อมูลในรูปแบบต่อไปนี้ได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
