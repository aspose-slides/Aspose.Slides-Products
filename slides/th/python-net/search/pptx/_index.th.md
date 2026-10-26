---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ค้นหาข้อความในงานนำเสนอ PPTX ด้วย Python
url: /th/python-net/search/pptx/
description: ค้นหาข้อความในงานนำเสนอ PPTX ด้วย Python และ Aspose.Slides
keywords: ค้นหาข้อความใน PPTX, หาคำใน PPTX, ค้นหางานนำเสนอ PPTX ด้วย Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ค้นหาข้อความในงานนำเสนอ PPTX ด้วย Python" h2="สร้างแอปพลิเคชัน Python ที่ค้นหาข้อความในงานนำเสนอ PowerPoint ด้วย Aspose.Slides" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ค้นหาข้อความในงานนำเสนอ PPTX โดยใช้ Python" variant="code" %}}

ด้วย [Aspose.Slides for Python via .NET](/slides/th/python-net/) คุณสามารถใช้ [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) เพื่อหากรอบข้อความในแต่ละสไลด์ที่มีสตริงที่ระบุ

{{< blocks/products/pf/slides-design-update-10-2026/code title="ค้นหาข้อความในงานนำเสนอ PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีค้นหาข้อความใน PPTX ด้วย Python" intro="ทำตามขั้นตอนต่อไปนี้เพื่อค้นหาข้อความในงานนำเสนอ PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เปิดไฟล์ PPTX ด้วย `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนผ่านสไลด์และเรียก [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) สำหรับแต่ละสไลด์{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}อ่านพร็อพเพอร์ตี `text` ของกรอบข้อความแต่ละกรอบที่ตรงกัน{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="สร้างด้วย Aspose.Slides" title="ค้นหาข้อความในไฟล์ PPTX ออนไลน์" description="แอป Aspose.Slides Search ฟรีนี้สร้างด้วย [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/th/python-net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Search" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ค้นหาข้อความอย่างไรก่อนเขียนโค้ด
- ค้นหาข้อความธรรมดาหรือนิพจน์ทั่วไปในไฟล์ PPTX ของคุณ
- ดาวน์โหลดผลการค้นหาเป็นไฟล์ข้อความ
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการค้นหา" subTitle="ใช้ Python เพื่อค้นหาข้อความในรูปแบบงานนำเสนออื่นที่รองรับ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
