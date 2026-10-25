---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ดูหรือแก้ไขข้อมูลเมตา PPTX ด้วย C++
url: /th/cpp/metadata/pptx/
description: ดูและแก้ไขข้อมูลเมตา PPTX ใน C++ ใช้ Aspose.Slides for C++ เพื่ออัปเดตคุณสมบัติในตัวและคุณสมบัติกำหนดเองของงานนำเสนอ
keywords: แก้ไขข้อมูลเมตา PPTX, ดูข้อมูลเมตา PPTX, แก้ไขคุณสมบัติ PPTX, ดูคุณสมบัติ PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แก้ไขข้อมูลเมตา PPTX ด้วย C++" h2="ใช้ Aspose.Slides for C++ เพื่อดูและอัปเดตคุณสมบัติในตัวและคุณสมบัติกำหนดเองในไฟล์งานนำเสนอ" related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แก้ไขคุณสมบัติ PPTX ผ่าน C++" variant="code" %}}

Aspose.Slides for C++ ช่วยให้คุณอ่านและอัปเดตข้อมูลเมตาในไฟล์ PPTX ได้โดยไม่ต้องใช้ Microsoft PowerPoint ใช้ออบเจ็กต์ [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) ที่ได้จาก `Presentation::get_DocumentProperties` เพื่อเปลี่ยนคุณสมบัติในตัว เช่น `Author` และ `Title` หรือจัดการคุณสมบัติกำหนดเองด้วย `idx_set`, `GetCustomPropertyName` และ `RemoveCustomProperty`

{{< blocks/products/pf/slides-design-update-10-2026/code title="แก้ไขคุณสมบัติในตัวของ PPTX – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="เพิ่มคุณสมบัติกำหนดเองให้ PPTX – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีดูหรือแก้ไขข้อมูลเมตา PPTX ใน C++" intro="ทำตามขั้นตอนเหล่านี้เพื่อดูหรือแก้ไขข้อมูลเมตา PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPTX ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ดึงออบเจ็กต์ `DocumentProperties` ด้วย `get_DocumentProperties`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}อ่านหรืออัปเดตคุณสมบัติในตัว เช่น `Author` และ `Title`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่ม อ่าน หรือลบคุณสมบัติกำหนดเองด้วย `idx_set`, `GetCustomPropertyName` และ `RemoveCustomProperty`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="สร้างด้วย Aspose.Slides" title="ดูและแก้ไขข้อมูลเมตา PPTX ออนไลน์" description="แอป Aspose.Slides Metadata ฟรีนี้สร้างด้วย [Aspose.Slides for C++](https://products.aspose.com/slides/th/cpp/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Metadata" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides อ่านและเขียนคุณสมบัติอย่างไรก่อนเขียนโค้ด
- ดูและแก้ไขคุณสมบัติในตัวและคุณสมบัติกำหนดเองของไฟล์ PPTX
- บันทึกและดาวน์โหลดไฟล์ที่อัปเดตแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบข้อมูลเมตาอื่นที่รองรับ" subTitle="ด้วย C++ คุณยังสามารถจัดการข้อมูลเมตาของรูปแบบต่อไปนี้ได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/metadata/pptm/" name="PPTM" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
