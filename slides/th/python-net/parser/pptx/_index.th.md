---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แยกข้อความจากไฟล์ PPTX ด้วย Python
url: /th/python-net/parser/pptx/
description: แยกข้อความและรายละเอียดการจัดรูปแบบข้อความจากงานนำเสนอ PPTX ด้วย Python
keywords: แยกวิเคราะห์ PPTX ด้วย Python, ตัวแยกวิเคราะห์ PPTX Python, แยกข้อมูลจาก PPTX ใน Python, แยกข้อความจาก PPTX ด้วย Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แยกข้อความจากงานนำเสนอ PPTX ด้วย Python" h2="สร้างแอปพลิเคชัน Python ที่แยกข้อความและรายละเอียดการจัดรูปแบบจากงานนำเสนอ PowerPoint ด้วย Aspose.Slides" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แยกข้อความจากงานนำเสนอ PPTX ด้วย Python – ตัวอย่าง" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/th/python-net/) มีเมธอดแบบสแตติก [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) ใน `SlideUtil` ซึ่งส่งคืนออบเจ็กต์ `TextFrame` จากทั้งงานนำเสนอ และสามารถรวมข้อความจากสไลด์ต้นแบบได้ ตัวอย่างต่อไปนี้แยกข้อความและรายละเอียดฟอนต์ที่เกี่ยวข้องจากงานนำเสนอ PPTX

{{< blocks/products/pf/slides-design-update-10-2026/code title="แยกข้อความจากงานนำเสนอ PPTX – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.pptx") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแยกข้อความจาก PPTX ด้วย Python" intro="ทำตามขั้นตอนเหล่านี้เพื่อแยกข้อความจากไฟล์ PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เปิดไฟล์ PPTX ด้วย `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียก `SlideUtil.get_all_text_frames` และระบุว่าจะรวมสไลด์ต้นแบบหรือไม่{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนผ่านออบเจ็กต์ `TextFrame` ที่ส่งคืน{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนผ่านคอลเลกชัน `paragraphs` ของแต่ละกรอบข้อความ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนผ่านคอลเลกชัน `portions` ของแต่ละย่อหน้า{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}อ่าน `text` และพร็อพเพอร์ตีการจัดรูปแบบของส่วนข้อความปัจจุบัน{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="สร้างด้วย Aspose.Slides" title="แยกข้อความและรูปภาพออนไลน์" description="แอป Aspose.Slides Parser ฟรีนี้สร้างด้วย [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/th/python-net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Parser" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides อ่านไฟล์ของคุณอย่างไรก่อนเขียนโค้ด
- อัปโหลดไฟล์ PPTX แล้วรับข้อความและรูปภาพ
- ดาวน์โหลดทั้งหมดเป็นไฟล์ ZIP เดียว
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการแยกวิเคราะห์" subTitle="ด้วย Python คุณยังสามารถแยกข้อความจากรูปแบบงานนำเสนออื่นที่รองรับได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/parser/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
