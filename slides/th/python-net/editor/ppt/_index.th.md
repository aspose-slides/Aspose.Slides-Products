---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แก้ไข PPT ใน Python
url: /th/python-net/editor/ppt/
keywords: แก้ไข PPT, แก้ไข PowerPoint, PPT, PowerPoint, Python API, Python Library
description: แก้ไข PPT ใน Python ใช้ Python library API เพื่อแก้ไขงานนำเสนอ PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แก้ไข PPT ใน Python" h2="ไลบรารี Python ความเร็วสูงและข้ามแพลตฟอร์มสำหรับแก้ไข PPT โดยใช้โค้ด Python" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แก้ไข PPT ใน Python" variant="code" %}}

เมื่อใช้ [**Aspose.Slides สำหรับ Python ผ่าน .NET**](https://products.aspose.com/slides/th/python-net/) คุณสามารถเพิ่มข้อความบรรทัดใหม่ลงในเอกสาร PPT ได้เพียงไม่กี่ขั้นตอน บรรทัดของรหัส

{{< blocks/products/pf/slides-design-update-10-2026/code title="รหัส Python สำหรับแก้ไข PPT" >}}
```python

import aspose.slides as slides

with slides.Presentation("pres.ppt") as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("pres.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แก้ไข PPT โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ Python ผ่าน .NET**](https://products.aspose.com/slides/th/python-net/) เป็นไลบรารี Python ที่มีประสิทธิภาพซึ่งใช้เพื่อจัดการและแก้ไขงานนำเสนอ คุณสามารถแก้ไขงานนำเสนอ PPT ได้โดยเพิ่มข้อความบรรทัดใหม่ลงไป

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแก้ไข PPT ใน Python" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างอินสแตนซ์ของคลาสการนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดงานนำเสนอ PPT ที่คุณต้องการแก้ไข{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มบรรทัดใหม่ของข้อความ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ PowerPoint ที่เปลี่ยนแปลง{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="สร้างด้วย Aspose.Slides" title="แก้ไขไฟล์ PPTX ออนไลน์" description="แอป Aspose.Slides Editor ฟรีนี้สร้างด้วย [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/th/python-net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Editor" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides จัดการไฟล์ของคุณอย่างไรก่อนเขียนโค้ด
- อัปโหลดไฟล์ PPTX แล้วแก้ไขได้ทันที
- บันทึกและดาวน์โหลดไฟล์ที่แก้ไขแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="แก้ไขไฟล์อื่นๆ" subTitle="คุณยังสามารถแก้ไขไฟล์ในรูปแบบอื่นๆ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
