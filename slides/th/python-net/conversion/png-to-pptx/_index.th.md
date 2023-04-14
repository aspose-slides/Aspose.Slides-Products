---
title: แปลง PNG เป็น PPTX ใน Python
url: /th/python-net/conversion/png-to-pptx/
keywords: แปลง PNG เป็น PPTX, PNG เป็น PPTX, PowerPoint, PNG, PPTX, Python API, Python Library
description: แปลง PNG เป็น PPTX ใน Python ใช้ Python library API เพื่อแปลงภาพ PNG เป็น PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง PNG เป็น PPTX ใน Python" h2="Python API ข้ามแพลตฟอร์มที่มีประสิทธิภาพสำหรับการแปลง PNG เป็น PPTX โดยใช้โค้ด Python" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง PNG เป็น PPTX โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ Python ผ่าน .NET**](https://products.aspose.com/slides/th/python-net/) เป็นไลบรารี Python อันทรงพลังที่ใช้สร้าง แปลง และจัดการงานนำเสนอ PowerPoint, PDF, เอกสาร HTML และไฟล์อื่นๆ เมื่อคุณแปลง PNG เป็น PPTX คุณกำลังสร้างงานนำเสนอ PowerPoint ที่มีสไลด์ตามภาพ PNG

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="แปลง PNG เป็น PPTX ใน Python" %}}
การใช้ [**Aspose.Slides สำหรับ Python ผ่าน .NET**](https://products.aspose.com/slides/th/python-net/) คุณสามารถแปลงภาพ PNG เป็นงานนำเสนอ PowerPoint โดยใช้โค้ดเพียงไม่กี่บรรทัด:

{{% blocks/products/pf/agp/code-block title="รหัส Python สำหรับแปลง PNG เป็น PPTX" offSpacer="true" %}}
```py
import aspose.slides as slides

with slides.Presentation() as pres:
    slide = pres.slides[0]
    with open("img.png", "rb") as in_file:
        image = pres.images.add_image(in_file)
        slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 0, 0, 720, 540, image)
    
    pres.save("pres_with_image.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง PNG เป็น PPTX ใน Python" >}}


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
โหลดภาพ PNG ที่คุณต้องการแปลงเป็น PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกไฟล์ผลลัพธ์เป็นงานนำเสนอ PPTX
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="ตัวแปลงออนไลน์ฟรี" sectionDescription="[วิธีแปลง PPT เป็น HTML ใน Python](https://products.aspose.com/slides/th/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="การแปลง PowerPoint อื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลงไฟล์ในรูปแบบอื่นเป็น PowerPoint" >}} 

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}