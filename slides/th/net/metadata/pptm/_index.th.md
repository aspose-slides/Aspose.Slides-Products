---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ดูหรือแก้ไขข้อมูลเมตาของไฟล์ PPTM ด้วย .NET
url: /th/net/metadata/pptm/
description: ซอร์สโค้ด C# สำหรับดูหรือแก้ไขข้อมูลเมตา PPTM
keywords: แก้ไขข้อมูลเมตา PPTM, ดูข้อมูลเมตา PPTM, แก้ไขคุณสมบัติ PPTM, ดูคุณสมบัติ PPTM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แก้ไขคุณสมบัติ PPTM ด้วย C#" h2="สร้างแอป .NET ที่อ่านและแก้ไขคุณสมบัติในตัวและคุณสมบัติกำหนดเองของงานนำเสนอด้วย API ฝั่งเซิร์ฟเวอร์" related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แก้ไขคุณสมบัติ PPTM ผ่าน C#" variant="code" %}}

ด้วย [Aspose.Slides for .NET](/slides/th/net/) นักพัฒนาสามารถเข้าถึงและแก้ไขคุณสมบัติในตัวและคุณสมบัติกำหนดเองของงานนำเสนอได้ ใช้พร็อพเพอร์ตี [`DocumentProperties`](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) ของออบเจ็กต์ `Presentation` เพื่ออ่านและอัปเดตข้อมูลเมตา PPTM

{{< blocks/products/pf/slides-design-update-10-2026/code title="แก้ไขคุณสมบัติในตัวของ PPTM – C#" >}}
```cs
using var presentation = new Presentation("presentation.pptm");
var documentProperties = presentation.DocumentProperties;

documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

presentation.Save("DocumentProperties_out.pptm", SaveFormat.Pptm);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="เพิ่มคุณสมบัติกำหนดเองให้ PPTM – C#" >}}
```cs
using var presentation = new Presentation();
var documentProperties = presentation.DocumentProperties;

documentProperties["New Custom"] = 12;
documentProperties["My Name"] = "Aspose Metadata Editor";
documentProperties["Custom"] = 124;

var propertyName = documentProperties.GetCustomPropertyName(2);
documentProperties.RemoveCustomProperty(propertyName);

presentation.Save("CustomDocumentProperties_out.pptm", SaveFormat.Pptm);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีดูหรือแก้ไขข้อมูลเมตา PPTM ใน C#" intro="ทำตามขั้นตอนเหล่านี้เพื่อดูหรือแก้ไขข้อมูลเมตา PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPTM ด้วย `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ดึงออบเจ็กต์ `DocumentProperties` จากงานนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}อ่านหรืออัปเดตคุณสมบัติในตัว เช่น `Author`, `Title` และ `Subject`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เข้าถึงและแก้ไขคุณสมบัติกำหนดเองด้วย `DocumentProperties`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="สร้างด้วย Aspose.Slides" title="ดูและแก้ไขข้อมูลเมตา PPTM ออนไลน์" description="แอป Aspose.Slides Metadata ฟรีนี้สร้างด้วย [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTM ของคุณเอง" button="เปิด Aspose.Slides Metadata" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides อ่านและเขียนคุณสมบัติอย่างไรก่อนเขียนโค้ด
- ดูและแก้ไขคุณสมบัติในตัวและคุณสมบัติกำหนดเองของไฟล์ PPTM
- บันทึกและดาวน์โหลดไฟล์ที่อัปเดตแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบข้อมูลเมตาอื่นที่รองรับ" subTitle="ด้วย C# คุณยังสามารถจัดการข้อมูลเมตาของรูปแบบต่อไปนี้ได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
