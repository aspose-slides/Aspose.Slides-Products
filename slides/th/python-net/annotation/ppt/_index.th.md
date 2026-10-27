---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: ลบความคิดเห็นออกจาก PPT ใน Python
url: /th/python-net/annotation/ppt/ 
description: ลบความคิดเห็นและผู้เขียนความคิดเห็นออกจากงานนำเสนอ PPT ใน Python ด้วย Aspose.Slides for Python via .NET
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ลบความคิดเห็นและผู้เขียนความคิดเห็นออกจาก PPT ใน Python" h2="ใช้ Aspose.Slides for Python via .NET เพื่อลบความคิดเห็นในงานนำเสนอพร้อมผู้เขียนที่เกี่ยวข้อง" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ลบความคิดเห็นออกจาก PPT ผ่าน Python" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/th/python-net/) ให้สิทธิ์เข้าถึงความคิดเห็นและผู้เขียนความคิดเห็นที่จัดเก็บในงานนำเสนอ PPT โหลดไฟล์ด้วย `Presentation` ล้างคอลเลกชัน `comments` ของผู้เขียนแต่ละคน ล้าง `comment_authors` แล้วบันทึกผลลัพธ์ในรูปแบบ PPT

{{< blocks/products/pf/slides-design-update-10-2026/code title="ลบความคิดเห็นออกจาก PPT ใน Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีลบความคิดเห็นออกจาก PPT ผ่าน Python" intro="ทำตามขั้นตอนเหล่านี้เพื่อลบความคิดเห็นและผู้เขียนความคิดเห็นทั้งหมดออกจากงานนำเสนอ PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง [Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เปิดไฟล์ PPT ด้วย `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนซ้ำ `comment_authors` และล้างคอลเลกชัน `comments` ของผู้เขียนแต่ละคน{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ล้างคอลเลกชัน `comment_authors`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียก `save` ด้วย `SaveFormat.PPT` เพื่อเขียนงานนำเสนอ PPT ที่อัปเดตแล้ว{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="สร้างด้วย Aspose.Slides" title="ลบความคิดเห็น PPT ออนไลน์" description="แอป Aspose.Slides Annotation ฟรีนี้สร้างด้วย [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/th/python-net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPT ของคุณเอง" button="เปิด Aspose.Slides Annotation" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ลบความคิดเห็นอย่างไรก่อนเขียนโค้ด
- ลบความคิดเห็นทั้งหมดออกจากไฟล์ PPT ของคุณ
- ดาวน์โหลดไฟล์ที่ล้างแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับสำหรับคำอธิบายประกอบ" subTitle="ด้วย Python คุณยังลบคำอธิบายประกอบออกจากรูปแบบอื่นได้ด้วย" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/python-net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
