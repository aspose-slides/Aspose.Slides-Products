---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ดูหรือแก้ไขข้อมูลเมตาของไฟล์ POTM ด้วย Java
url: /th/java/metadata/potm/
description: ดูและแก้ไขข้อมูลเมตา POTM ใน Java ใช้ Aspose.Slides for Java เพื่ออัปเดตคุณสมบัติในตัวและคุณสมบัติกำหนดเองของงานนำเสนอ
keywords: แก้ไขข้อมูลเมตา POTM, ดูข้อมูลเมตา POTM, แก้ไขคุณสมบัติ POTM, ดูคุณสมบัติ POTM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แก้ไขคุณสมบัติ POTM ด้วย Java" h2="สร้างแอป Java ที่แก้ไขคุณสมบัติในตัวและคุณสมบัติกำหนดเองในไฟล์งานนำเสนอด้วย API ฝั่งเซิร์ฟเวอร์" related="FODP,ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แก้ไขคุณสมบัติ POTM ผ่าน Java" variant="code" %}}

ด้วย [Aspose.Slides for Java](/slides/th/java/) นักพัฒนาสามารถเข้าถึงและแก้ไขคุณสมบัติในตัวและคุณสมบัติกำหนดเองของงานนำเสนอได้ ใช้เมธอด `getDocumentProperties` ของออบเจ็กต์ `Presentation` เพื่อเข้าถึงออบเจ็กต์ `IDocumentProperties` ของไฟล์งานนำเสนอ

{{< blocks/products/pf/slides-design-update-10-2026/code title="แก้ไขคุณสมบัติในตัวของ POTM – Java" >}}
```java
Presentation presentation = new Presentation("Presentation.potm");
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.setAuthor("Aspose.Slides for Java");
    documentProperties.setTitle("Modifying Presentation Properties");
    documentProperties.setSubject("Aspose Subject");
    documentProperties.setComments("Aspose Description");
    documentProperties.setManager("Aspose Manager");

    presentation.save("DocProps.potm", SaveFormat.Potm);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="เพิ่มคุณสมบัติกำหนดเองให้ POTM – Java" >}}
```java
Presentation presentation = new Presentation();
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.set_Item("New Custom", 12);
    documentProperties.set_Item("My Name", "Aspose Metadata Editor");
    documentProperties.set_Item("Custom", 124);

    String customPropertyName = documentProperties.getCustomPropertyName(2);
    documentProperties.removeCustomProperty(customPropertyName);

    presentation.save("CustomDemo.potm", SaveFormat.Potm);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีดูหรือแก้ไขข้อมูลเมตา POTM ใน Java" intro="ทำตามขั้นตอนเหล่านี้เพื่อดูหรือแก้ไขข้อมูลเมตา POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ `POTM` ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกเมธอด `getDocumentProperties` เพื่อรับออบเจ็กต์ `IDocumentProperties`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}อ่านหรืออัปเดตคุณสมบัติในตัว เช่น `Author`, `Title`, `Subject` และ `Comments`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เข้าถึงและแก้ไขคุณสมบัติกำหนดเองด้วย `set_Item`, `getCustomPropertyName` และ `removeCustomProperty`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="สร้างด้วย Aspose.Slides" title="ดูและแก้ไขข้อมูลเมตา POTM ออนไลน์" description="แอป Aspose.Slides Metadata ฟรีนี้สร้างด้วย [Aspose.Slides for Java](https://products.aspose.com/slides/th/java/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ POTM ของคุณเอง" button="เปิด Aspose.Slides Metadata" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides อ่านและเขียนคุณสมบัติอย่างไรก่อนเขียนโค้ด
- ดูและแก้ไขคุณสมบัติในตัวและคุณสมบัติกำหนดเองของไฟล์ POTM
- บันทึกและดาวน์โหลดไฟล์ที่อัปเดตแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบข้อมูลเมตาอื่นที่รองรับ" subTitle="ด้วย Java คุณยังสามารถจัดการข้อมูลเมตาของรูปแบบต่อไปนี้ได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/java/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
