---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ดูหรือแก้ไขข้อมูลเมตา PPTX ด้วย Python
url: /th/python-net/metadata/pptx/
description: ดูและแก้ไขคุณสมบัติข้อมูลเมตาในตัวและกำหนดเองในไฟล์ PPTX ด้วย Python
keywords: แก้ไขข้อมูลเมตา PPTX, ดูข้อมูลเมตา PPTX, แก้ไขคุณสมบัติ PPTX, ดูคุณสมบัติ PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ดูและแก้ไขข้อมูลเมตา PPTX ด้วย Python" h2="สร้างแอป Python ที่อ่านและแก้ไขคุณสมบัติในตัวและคุณสมบัติกำหนดเองของงานนำเสนอด้วย Aspose.Slides" related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ดูและปรับเปลี่ยนข้อมูลเมตา PPTX ด้วย Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/th/python-net/) ช่วยให้คุณอ่านและอัปเดตข้อมูลเมตาในตัว รวมถึงเพิ่ม อัปเดต หรือลบคุณสมบัติเอกสารกำหนดเองในงานนำเสนอ PPTX เข้าถึงออบเจ็กต์ [`IDocumentProperties`](https://reference.aspose.com/slides/python-net/aspose.slides/idocumentproperties/) ผ่าน `Presentation.document_properties` แก้ไข แล้วบันทึกงานนำเสนอในรูปแบบ PPTX

{{< blocks/products/pf/slides-design-update-10-2026/code title="อัปเดตคุณสมบัติในตัวของ PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    document_properties = presentation.document_properties
    document_properties.author = "Aspose.Slides for Python"
    document_properties.title = "Quarterly Review"
    document_properties.subject = "Presentation Metadata"
    document_properties.comments = "Built-in properties updated with Aspose.Slides."
    document_properties.manager = "Project Manager"

    presentation.save("presentation_with_updated_metadata.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="เพิ่มและลบคุณสมบัติกำหนดเองของ PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    document_properties = presentation.document_properties
    document_properties.set_custom_property_value("Department", "Engineering")
    document_properties.set_custom_property_value("Review Count", 3)
    document_properties.set_custom_property_value("Obsolete Status", "Draft")
    document_properties.remove_custom_property("Obsolete Status")

    presentation.save("presentation_with_custom_metadata.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแก้ไขข้อมูลเมตา PPTX ด้วย Python" intro="ทำตามขั้นตอนเหล่านี้เพื่อแก้ไขข้อมูลเมตาในไฟล์ PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เปิดไฟล์ PPTX ด้วย `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เข้าถึงออบเจ็กต์ `IDocumentProperties` ผ่าน `Presentation.document_properties`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}อัปเดตคุณสมบัติในตัว หรือใช้ `set_custom_property_value` และ `remove_custom_property` สำหรับคุณสมบัติกำหนดเอง{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกงานนำเสนอด้วย `Presentation.save` และ `SaveFormat.PPTX`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="สร้างด้วย Aspose.Slides" title="ดูและแก้ไขข้อมูลเมตา PPTX ออนไลน์" description="แอป Aspose.Slides Metadata ฟรีนี้สร้างด้วย [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/th/python-net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Metadata" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides อ่านและเขียนคุณสมบัติอย่างไรก่อนเขียนโค้ด
- ดูและแก้ไขคุณสมบัติในตัวและคุณสมบัติกำหนดเองของไฟล์ PPTX
- บันทึกและดาวน์โหลดไฟล์ที่อัปเดตแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบข้อมูลเมตาอื่นที่รองรับ" subTitle="ด้วย Python คุณยังสามารถจัดการข้อมูลเมตาของรูปแบบงานนำเสนออื่นที่รองรับได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/metadata/pptm/" name="PPTM" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
