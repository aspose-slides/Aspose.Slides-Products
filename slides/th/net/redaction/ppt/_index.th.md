---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ปกปิดข้อมูลในไฟล์งานนำเสนอ PPT ด้วย .NET
url: /th/net/redaction/ppt/
description: ซอร์สโค้ด C# สำหรับค้นหาและแทนที่ข้อความในงานนำเสนอ PPT
keywords: ปกปิดข้อมูล PPT, ค้นหาและแทนที่ข้อความใน PPT, อัปเดตงานนำเสนอ PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ปกปิดข้อมูลในไฟล์ PPT ด้วย C#" h2="สร้างแอป .NET ที่ค้นหาและแทนที่ข้อความในงานนำเสนอด้วย API ฝั่งเซิร์ฟเวอร์" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ปกปิดข้อมูลในงานนำเสนอ PPT ด้วย C#" variant="code" %}}

ด้วย [Aspose.Slides for .NET](/slides/th/net/) คุณสามารถค้นหาและแทนที่ข้อความในงานนำเสนอ PPT ได้ ใช้ `Presentation.ReplaceText` ร่วมกับ `TextSearchOptions` เพื่อควบคุมการค้นหา แล้วบันทึกงานนำเสนอที่แก้ไขแล้ว

{{< blocks/products/pf/slides-design-update-10-2026/code title="ปกปิดข้อมูลในงานนำเสนอ PPT ด้วย C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีปกปิดข้อมูลในงานนำเสนอ PPT ด้วย C#" intro="ทำตามขั้นตอนต่อไปนี้เพื่อแทนที่ข้อความในงานนำเสนอ PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPT ด้วย `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ใช้ [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) ร่วมกับ `TextSearchOptions` เพื่อแทนที่ข้อความที่ต้องการ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกงานนำเสนอที่แก้ไขแล้วด้วย `SaveFormat.Ppt`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="สร้างด้วย Aspose.Slides" title="ปกปิดข้อมูลในไฟล์ PPT ออนไลน์" description="แอป Aspose.Slides Redaction ฟรีนี้สร้างด้วย [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPT ของคุณเอง" button="เปิด Aspose.Slides Redaction" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ค้นหาและแทนที่ข้อความอย่างไรก่อนเขียนโค้ด
- ค้นหาและแทนที่ข้อความในไฟล์ PPT ของคุณ รวมถึงด้วยนิพจน์ทั่วไป
- ดาวน์โหลดไฟล์ที่ปกปิดข้อมูลแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการปกปิดข้อมูล" subTitle="ด้วย C# คุณยังสามารถปกปิดข้อมูลในรูปแบบต่อไปนี้ได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
