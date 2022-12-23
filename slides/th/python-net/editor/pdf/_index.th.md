---
title: แก้ไข PDF ใน Python
url: /th/python-net/editor/pdf/
keywords: แก้ไข PDF, PDF, Python API, Python Library
description: แก้ไข PDF ใน Python ใช้ Python library API เพื่อแก้ไขเอกสาร PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แก้ไข PDF ใน Python" h2="ไลบรารี Python ความเร็วสูงและข้ามแพลตฟอร์มสำหรับแก้ไข PDF โดยใช้โค้ด Python" >}}

{{% blocks/products/pf/feature-page-section h2="แก้ไข PDF โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ Python ผ่าน .NET**](https://products.aspose.com/slides/th/python-net/) เป็นไลบรารี Python อันทรงพลังที่ใช้ในการจัดการและแก้ไขงานนำเสนอ เอกสาร PDF และไฟล์อื่นๆ . คุณสามารถแก้ไขเอกสาร PDF ได้โดยเพิ่มบรรทัดข้อความใหม่เข้าไป 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="แก้ไข PDF ใน Python" %}}
การใช้ [**Aspose.Slides สำหรับ Python ผ่าน .NET**](https://products.aspose.com/slides/th/python-net/) คุณสามารถเพิ่มข้อความบรรทัดใหม่ลงในเอกสาร PDF โดยใช้เวลาเพียงไม่กี่ขั้นตอน บรรทัดของรหัส

{{% blocks/products/pf/agp/code-block title="รหัส Python สำหรับแก้ไข PDF" offSpacer="true" %}}
```python

import aspose.slides as slides

with slides.Presentation() as pres:
    pres.slides.remove_at(0)
    pres.slides.add_from_pdf("document.pdf")

    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 10, 10, 100, 50)
    shape.text_frame.text = "New text"

    pres.save("document.pdf", slides.export.SaveFormat.PDF)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="วิธีแก้ไข PDF ใน Python" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
สร้างอินสแตนซ์ของคลาสการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดเอกสาร PDF ที่คุณต้องการแก้ไข
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มบรรทัดใหม่ของข้อความ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกไฟล์ PDF ที่เปลี่ยนแปลง
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="แก้ไขไฟล์อื่นๆ" subTitle="คุณยังสามารถแก้ไขไฟล์ในรูปแบบอื่นๆ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}