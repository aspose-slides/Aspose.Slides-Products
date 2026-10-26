---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ปกปิดข้อความในงานนำเสนอ PPTX ด้วย Python
url: /th/python-net/redaction/pptx/
description: ค้นหาและแทนที่ข้อความที่ละเอียดอ่อนในงานนำเสนอ PPTX ด้วย Python
keywords: ปกปิดข้อมูล PPTX, ค้นหาและแทนที่ข้อความใน PPTX, อัปเดตงานนำเสนอ PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ปกปิดข้อความในงานนำเสนอ PPTX ด้วย Python" h2="สร้างแอปพลิเคชัน Python ที่ค้นหาและแทนที่ข้อความที่ละเอียดอ่อนในงานนำเสนอด้วย Aspose.Slides" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ปกปิดข้อความในงานนำเสนอ PPTX โดยใช้ Python" variant="code" %}}

ด้วย [Aspose.Slides for Python via .NET](/slides/th/python-net/) คุณสามารถแทนที่ข้อความที่ละเอียดอ่อนทั่วทั้งงานนำเสนอ PPTX ได้ ใช้ `Presentation.replace_text` ร่วมกับ `TextSearchOptions` เพื่อควบคุมการค้นหา แล้วบันทึกงานนำเสนอที่แก้ไขแล้ว

{{< blocks/products/pf/slides-design-update-10-2026/code title="ปกปิดข้อความในงานนำเสนอ PPTX – Python" >}}
```python
search_options = slides.TextSearchOptions()
search_options.whole_words_only = True
search_options.include_notes = True

with slides.Presentation("presentation.pptx") as presentation:
    presentation.replace_text("Confidential", "[REDACTED]", search_options, None)
    presentation.save("redacted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีปกปิดข้อความในงานนำเสนอ PPTX ด้วย Python" intro="ทำตามขั้นตอนต่อไปนี้เพื่อแทนที่ข้อความที่ละเอียดอ่อนในงานนำเสนอ PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เปิดไฟล์ PPTX ด้วย `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ใช้ [`Presentation.replace_text`](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/replace_text/) ร่วมกับ `TextSearchOptions` เพื่อแทนที่ข้อความที่ต้องการ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกงานนำเสนอที่แก้ไขแล้วด้วย `SaveFormat.PPTX`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="สร้างด้วย Aspose.Slides" title="ปกปิดข้อมูลในไฟล์ PPTX ออนไลน์" description="แอป Aspose.Slides Redaction ฟรีนี้สร้างด้วย [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/th/python-net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Redaction" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ค้นหาและแทนที่ข้อความอย่างไรก่อนเขียนโค้ด
- ค้นหาและแทนที่ข้อความในไฟล์ PPTX ของคุณ รวมถึงด้วยนิพจน์ทั่วไป
- ดาวน์โหลดไฟล์ที่ปกปิดข้อมูลแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการปกปิดข้อมูล" subTitle="ใช้ Python เพื่อปกปิดข้อความในรูปแบบงานนำเสนออื่นที่รองรับ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
