---
title: รวมไฟล์ PPTX เข้ากับ POTX โดยใช้ Python
url: /th/python-net/merge/pptx-to-potx/
keywords: รวม PPTX เป็น POTX เข้าร่วม PPTX ถึง POTX รวม PPTX เป็น POTX PowerPoint การนำเสนอ POTX Python Aspose
description: รวมไฟล์ PPTX หลายไฟล์ใน Python
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="รวมไฟล์ PPTX เข้ากับ POTX เข้าด้วยกันใน Python" h2="Python API ความเร็วสูงและข้ามแพลตฟอร์มที่ช่วยในการพัฒนาแอปพลิเคชันด้วยความสามารถในการสร้าง ผสาน ตรวจสอบ หรือแปลงไฟล์งานนำเสนอ Microsoft PowerPoint และ OpenOffice โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Open Office, Adobe PDF" >}}

{{% blocks/products/pf/feature-page-section h2="รวม PPTX เป็น POTX ใน Python" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/th/python-net/) เป็นไลบรารี Python อันทรงพลังสำหรับการสร้างและจัดการไฟล์การนำเสนอ นอกจากนี้ยังมีวิธีที่ยืดหยุ่นในการรวม PPTX การนำเสนอหลายรายการเข้าด้วยกัน เมื่อคุณรวมงานนำเสนอหนึ่งเข้ากับอีกงานนำเสนอหนึ่ง แสดงว่าคุณกำลังรวมสไลด์ของพวกเขาในงานนำเสนอเดียวอย่างมีประสิทธิภาพเพื่อรับไฟล์หนึ่ง Aspose.Slides ช่วยให้คุณสามารถรวมสองงานนำเสนอในรูปแบบต่างๆ ได้ คุณสามารถผสานงานนำเสนอกับรูปร่าง สไตล์ ข้อความ การจัดรูปแบบ ความคิดเห็น ภาพเคลื่อนไหว ฯลฯ โดยไม่ต้องกังวลว่าจะสูญเสียคุณภาพหรือข้อมูล

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="รวมไฟล์ PPTX เข้ากับ POTX โดยใช้ Python" %}}
ในการผสานงานนำเสนอ PowerPoint คุณจะต้องโคลนสไลด์จากงานนำเสนอหนึ่งไปยังอีกงานนำเสนอหนึ่ง

{{% blocks/products/pf/agp/code-block title="รหัสหลามสำหรับรวมหลาย ๆ PPTX เป็นไฟล์เดียว POTX" offSpacer="true" %}}

```python

import aspose.slides as slides


with slides.Presentation("presentation1.pptx") as pres1:
    with slides.Presentation("presentation2.pptx") as pres2:
        for slide in pres2.slides:
            pres1.slides.add_clone(slide)
    pres1.save("presentation.potx", slides.export.SaveFormat.POTX)
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีผสาน PPTX กับ POTX โดยใช้ Aspose.Slides สำหรับ Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการรวมไฟล์ PPTX สองไฟล์เข้าด้วยกัน และบันทึกผลลัพธ์เป็น POTX ใน Python" >}}

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
เปิดไฟล์ต้นฉบับ PPTX ใน Python
```
pres1 = slides.Presentation('pres1.pptx')
pres2 = slides.Presentation('pres2.pptx')
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
รวมไฟล์ PPTX โดยใช้วิธีการ [**add_clone**](https://reference.aspose.com/slides/python-net/aspose.slides/islidecollection/#methods)
```
for slide in pres2.slides:
    pres1.slides.add_clone(slide)
```
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกงานนำเสนอและรับผลลัพธ์เป็นไฟล์เดียว POTX
```
pres1.save("presentation.potx", slides.export.SaveFormat.POTX)
```

{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="ส่งออก PPTX เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถรวม PPTX และบันทึกเป็นรูปแบบไฟล์อื่นได้ ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-ppt/" name="PPTX TO PPT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-pdf/" name="PPTX TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-html/" name="PPTX TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-png/" name="PPTX TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-bmp/" name="PPTX TO BMP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-jpg/" name="PPTX TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-fodp/" name="PPTX TO FODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-gif/" name="PPTX TO GIF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-odp/" name="PPTX TO ODP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-otp/" name="PPTX TO OTP" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-pot/" name="PPTX TO POT" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-potm/" name="PPTX TO POTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-pps/" name="PPTX TO PPS" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-ppsm/" name="PPTX TO PPSM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-ppsx/" name="PPTX TO PPSX" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-pptm/" name="PPTX TO PPTM" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-svg/" name="PPTX TO SVG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-tiff/" name="PPTX TO TIFF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/merge/pptx-to-xps/" name="PPTX TO XPS" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}