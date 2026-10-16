---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง PNG เป็น PPTX ใน Python
url: /th/python-net/conversion/png-to-pptx/
keywords: แปลง PNG เป็น PPTX, PNG เป็น PPTX, PowerPoint, PNG, PPTX, Python API, Python Library
description: แปลง PNG เป็น PPTX ใน Python ใช้ Python library API เพื่อแปลงภาพ PNG เป็น PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง PNG เป็น PPTX ใน Python" h2="Python API ข้ามแพลตฟอร์มที่มีประสิทธิภาพสำหรับการแปลง PNG เป็น PPTX โดยใช้โค้ด Python" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง PNG เป็น PPTX ใน Python" variant="code" %}}

การใช้ [**Aspose.Slides สำหรับ Python ผ่าน .NET**](https://products.aspose.com/slides/th/python-net/) คุณสามารถแปลงภาพ PNG เป็นงานนำเสนอ PowerPoint โดยใช้โค้ดเพียงไม่กี่บรรทัด:

{{< blocks/products/pf/slides-design-update-10-2026/code title="รหัส Python สำหรับแปลง PNG เป็น PPTX" >}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.png", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง PNG เป็น PPTX โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ Python ผ่าน .NET**](https://products.aspose.com/slides/th/python-net/) เป็นไลบรารี Python อันทรงพลังที่ใช้สร้าง แปลง และจัดการงานนำเสนอ PowerPoint, PDF, เอกสาร HTML และไฟล์อื่นๆ เมื่อคุณแปลง PNG เป็น PPTX คุณกำลังสร้างงานนำเสนอ PowerPoint ที่มีสไลด์ตามภาพ PNG

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแปลง PNG เป็น PPTX ใน Python" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างอินสแตนซ์ของคลาสการนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดภาพ PNG ที่คุณต้องการแปลงเป็น PPTX{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ผลลัพธ์เป็นงานนำเสนอ PPTX{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="ตัวแปลงออนไลน์ฟรี"
  description="[วิธีแปลง PPT เป็น HTML ใน Python](https://products.aspose.com/slides/th/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="การแปลง PowerPoint อื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลงไฟล์ในรูปแบบอื่นเป็น PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
