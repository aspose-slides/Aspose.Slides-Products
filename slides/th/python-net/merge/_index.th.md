---
title: รวม PDF, PPT, PPTX และรูปแบบไฟล์อื่น ๆ อีกมากมายโดยใช้ Python
url: /th/python-net/merge/
keywords: ผสาน เข้าร่วม PowerPoint การนำเสนอ Python Aspose
description: รวมหลายไฟล์ใน Python PPT, PPTX, ODP, PDF, PNG, JPG และอีกมากมาย
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="รวม Powerpoint, PDF, PPT หรือเอกสารอื่นๆ เข้าด้วยกันใน Python" h2="ไลบรารี Python ความเร็วสูงเพื่อรวม PPT, PPTX, PDF, PNG, JPEG และรูปแบบอื่น ๆ" >}}

{{% blocks/products/pf/feature-page-section h2="ผสาน PPT, PPTX, PDF โดยใช้ Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/th/python-net/) เป็นไลบรารี Python อันทรงพลังสำหรับการสร้างและจัดการไฟล์การนำเสนอ นอกจากนี้ยังมีวิธีที่ยืดหยุ่นในการรวมการนำเสนอ PPT/PPTX หลายรายการ เมื่อคุณรวมงานนำเสนอหนึ่งเข้ากับอีกงานนำเสนอหนึ่ง แสดงว่าคุณกำลังรวมสไลด์ของพวกเขาในงานนำเสนอเดียวอย่างมีประสิทธิภาพเพื่อรับไฟล์หนึ่ง Aspose.Slides ช่วยให้คุณสามารถรวมสองงานนำเสนอในรูปแบบต่างๆ ได้ คุณสามารถผสานงานนำเสนอกับรูปร่าง สไตล์ ข้อความ การจัดรูปแบบ ความคิดเห็น ภาพเคลื่อนไหว ฯลฯ โดยไม่ต้องกังวลว่าจะสูญเสียคุณภาพหรือข้อมูล

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="รวมงานนำเสนอ PowerPoint ใน Python" %}}
ในการผสานงานนำเสนอ PowerPoint คุณจะต้องโคลนสไลด์จากงานนำเสนอหนึ่งไปยังอีกงานนำเสนอหนึ่ง

{{% blocks/products/pf/agp/code-block title="รวมไฟล์ PPTX โดยใช้ Python" offSpacer="true" %}}

```python

import aspose.slides as slides

# open first presentation
with slides.Presentation("presentation1.pptx") as pres1:
    # open second presentation
    with slides.Presentation("presentation2.pptx") as pres2:
        # loop through slides
        for slide in pres2.slides:
            # clone slide
            pres1.slides.add_clone(slide)
        # save merged presentation
        pres1.save("combined.pptx", slides.export.SaveFormat.PPTX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ผสานการนำเสนอด้วย Slide Master โดยใช้ Python" %}}
โค้ดหลามนี้สาธิตวิธีการผสานงานนำเสนอหลายรายการเป็นหนึ่งเดียวและนำสไตล์จากเทมเพลตการนำเสนอต้นแบบสไลด์ไปใช้ ดังนั้น การนำเสนอผลลัพธ์จะคงรูปแบบต้นฉบับไว้และจะมีการจัดรูปแบบจากสไลด์ต้นแบบของงานนำเสนออื่น

{{% blocks/products/pf/agp/code-block title="รวม PPT หลายรายการเป็นไฟล์เดียวใน Python" offSpacer="true" %}}

```python

import aspose.slides as slides

files = ['pres1.pptx', 'pres2.pptx', 'pres3.pptx']

with slides.Presentation('master.pptx') as master:
    masterSlide = master.masters[0]

    for file in files:
        with slides.Presentation(file) as source:
            for slide in source.slides:
                clone = master.slides.add_clone(slide)

                for shape in masterSlide.shapes:
                    clone.shapes.add_clone(shape)
    
    master.save("combined.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีผสานการนำเสนอโดยใช้ Aspose.Slides สำหรับ Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการรวมไฟล์ PPTX สองไฟล์และบันทึกผลลัพธ์เป็น PDF ใน Python" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/th/python-net/)
```
pip install aspose.slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ไปยังโครงการ Python ของคุณ
```
import aspose.slides as slides
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เปิดไฟล์ PPTX ต้นทางใน Python
```
pres1 = slides.Presentation('pres1.pptx')
pres2 = slides.Presentation('pres2.pptx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
รวมไฟล์ PPTX โดยใช้วิธีการ **add_clone**
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกงานนำเสนอและรับผลลัพธ์เป็นไฟล์ PDF ไฟล์เดียว
```
pres1.save("document.pdf", slides.export.SaveFormat.PDF)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบอื่นที่รองรับในการผสาน" subTitle="คุณยังสามารถรวมรูปแบบไฟล์อื่นๆ ดูรูปแบบอื่นๆ ที่รองรับด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/ppt/" name="PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx/" name="PPTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pdf/" name="PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/odp/" name="ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/otp/" name="OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pot/" name="POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/potm/" name="POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/potx/" name="POTX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pps/" name="PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/ppsm/" name="PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/ppsx/" name="PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptm/" name="PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/fodp/" name="FODP" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}