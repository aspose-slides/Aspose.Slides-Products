---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: เพิ่มลายน้ำในงานนำเสนอ PPT ด้วย Python
url: /th/python-net/watermark/ppt/
description: เพิ่มลายน้ำข้อความและรูปภาพในงานนำเสนอ PPT ด้วย Python และ Aspose.Slides
keywords: เพิ่มลายน้ำใน PPT, เพิ่มลายน้ำข้อความใน PPT, เพิ่มลายน้ำรูปภาพใน PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="เพิ่มลายน้ำในงานนำเสนอ PPT ด้วย Python" h2="สร้างแอป Python ที่เพิ่มลายน้ำข้อความหรือรูปภาพในงานนำเสนอ PPT ด้วย Aspose.Slides" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="เพิ่มลายน้ำในงานนำเสนอ PPT ด้วย Python – ตัวอย่าง" variant="code" %}}

ด้วย [Aspose.Slides for Python via .NET](/slides/th/python-net/) คุณสามารถเพิ่มลายน้ำข้อความหรือรูปภาพในงานนำเสนอ PPT ได้โดยไม่ต้องใช้ Microsoft PowerPoint ลายน้ำช่วยระบุความเป็นเจ้าของ ทำเครื่องหมายว่างานนำเสนอเป็นความลับหรือฉบับร่าง หรือสร้างแบรนด์ที่สอดคล้องกัน ตัวอย่างด้านล่างวางลายน้ำบนสไลด์ต้นแบบแรก เพื่อให้ลายน้ำปรากฏบนสไลด์ที่ใช้ต้นแบบนั้น

{{< blocks/products/pf/slides-design-update-10-2026/code title="เพิ่มลายน้ำข้อความในงานนำเสนอ PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 100, 100, 400, 50)
    watermark_text_frame = watermark_shape.add_text_frame("CONFIDENTIAL")

    watermark_shape.fill_format.fill_type = slides.FillType.NO_FILL
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    watermark_portion = watermark_text_frame.paragraphs[0].portions[0]
    watermark_portion.portion_format.font_height = 32

    watermark_shape.auto_shape_lock.select_locked = True
    watermark_shape.auto_shape_lock.size_locked = True
    watermark_shape.auto_shape_lock.text_locked = True
    watermark_shape.auto_shape_lock.position_locked = True
    watermark_shape.auto_shape_lock.grouping_locked = True

    presentation.save("watermarked.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="เพิ่มลายน้ำรูปภาพในงานนำเสนอ PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    with open("watermark.png", "rb") as image_stream:
        watermark_image = presentation.images.add_image(image_stream.read())

    master_slide = presentation.masters[0]
    watermark_shape = master_slide.shapes.add_auto_shape(
        slides.ShapeType.RECTANGLE, 100, 100, watermark_image.width, watermark_image.height)

    watermark_shape.fill_format.fill_type = slides.FillType.PICTURE
    watermark_shape.fill_format.picture_fill_format.picture.image = watermark_image
    watermark_shape.fill_format.picture_fill_format.picture_fill_mode = slides.PictureFillMode.STRETCH
    watermark_shape.line_format.fill_format.fill_type = slides.FillType.NO_FILL

    presentation.save("watermarked.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีเพิ่มลายน้ำใน PPT ด้วย Python" intro="ทำตามขั้นตอนเหล่านี้เพื่อเพิ่มลายน้ำข้อความในงานนำเสนอ PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เปิดไฟล์ PPT ด้วย `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ดึงสไลด์ต้นแบบแรกจากคอลเลกชัน `masters`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียก `add_auto_shape` เพื่อเพิ่มสี่เหลี่ยมผืนผ้าลงในสไลด์ต้นแบบ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียก `add_text_frame` เพื่อเพิ่มข้อความลายน้ำ จากนั้นจัดรูปแบบและล็อกรูปร่าง{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียก `save` พร้อม `SaveFormat.PPT` เพื่อบันทึกงานนำเสนอที่มีลายน้ำ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="สร้างด้วย Aspose.Slides" title="เพิ่มลายน้ำในไฟล์ PPT ออนไลน์" description="แอป Aspose.Slides Watermark ฟรีนี้สร้างด้วย [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/th/python-net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPT ของคุณเอง" button="เปิด Aspose.Slides Watermark" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides เพิ่มลายน้ำอย่างไรก่อนเขียนโค้ด
- เพิ่มลายน้ำข้อความหรือรูปภาพในไฟล์ PPT ของคุณ
- ดาวน์โหลดไฟล์ที่มีลายน้ำ
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับลายน้ำ" subTitle="ด้วย Python คุณยังสามารถเพิ่มลายน้ำในรูปแบบงานนำเสนออื่นที่รองรับได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
