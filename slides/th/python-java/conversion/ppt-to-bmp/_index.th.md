---
title: แปลง PPT เป็น BMP ใน Python
url: /th/python-java/conversion/ppt-to-bmp/
keywords: การแปลงการนำเสนอ Python, แปลงการนำเสนอเป็น Python, Python สำหรับการนำเสนอ, Aspose.Slides Python, การแปลง PPT เป็น BMP, ไลบรารีการนำเสนอ Python
description: แปลง PPT เป็น BMP ใน Python ใช้ Python Library API เพื่อแปลงไฟล์ PPT เป็น BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง PPT เป็น BMP ได้อย่างง่ายดายด้วย Python: Aspose.Slides to the Rescue!" h2="เติมชีวิตชีวาให้กับงานนำเสนอของคุณด้วย Python คำแนะนำของเราจะอธิบายขั้นตอนการแปลงสไลด์ PowerPoint ที่มีอยู่ให้เป็นงานนำเสนอ Python ที่น่าสนใจ" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง PPT เป็น BMP ใน Python" %}}

เบื่อกับการต่อสู้กับซอฟต์แวร์การนำเสนอที่ซับซ้อนแล้วหรือยัง? ไม่ต้องมองไปไกลกว่า [**Aspose.Slides สำหรับ Python ผ่าน Java**](https://products.aspose.com/slides/th/python-java/)! ไลบรารีอันทรงพลังนี้ช่วยให้คุณสามารถสร้าง แก้ไข และแปลงงานนำเสนอระหว่างรูปแบบต่างๆ ได้อย่างง่ายดาย ต้องการเปลี่ยนจาก PPT เป็น BMP หรือไม่ Aspose.Slides ทำให้เป็นเรื่องง่าย โดยต้องใช้โค้ด Python เพียงไม่กี่บรรทัด

ในฐานะ API การประมวลผลเอกสารที่ล้ำสมัย **Aspose.Slides สำหรับ Python ผ่าน Java** มีความเร็วในการแปลงที่รวดเร็วปานสายฟ้า ช่วยให้มั่นใจได้ถึงการเปลี่ยนแปลงงานนำเสนอ PPT เป็นรูปแบบ BMP อย่างรวดเร็ว ทิ้งข้อจำกัดของเครื่องมือแบบเดิมๆ - Aspose.Slides ให้ความยืดหยุ่นแก่คุณในการแปลงงานนำเสนอจาก PPT เป็นไม่เพียงแต่ BMP เท่านั้น แต่ยังรวมถึงรูปแบบอื่นๆ ที่หลากหลาย ทำให้คุณสามารถปรับเปลี่ยนงานนำเสนอของคุณให้เข้ากับทุกสถานการณ์ได้อย่างไร้ที่ติ

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลง PPT เป็น BMP โดยใช้ Python" %}}
หากต้องการแปลง PPT เป็น BMP คุณจะต้องสร้างงานนำเสนอจากไฟล์ PPT และบันทึกเป็น BMP

{{% blocks/products/pf/agp/code-block title="บทช่วยสอน Python สำหรับการแปลง PPT เป็น BMP" offSpacer="true" %}}

```python

import jpype
import asposeslides

jpype.startJVM()

from asposeslides.api import Presentation, SaveFormat
from javax.imageio import ImageIO
from java.io import File

pres = Presentation("PowerPoint.ppt");

for i in range(pres.getSlides().size()):
    buffImage = pres.getSlides().get_Item(i).getThumbnail(2, 2)
    ImageIO.write(buffImage, "BMP", File("slide" + str(i) + ".bmp"))

jpype.shutdownJVM()
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="หลามกวดวิชา วิธีแปลง PPT เป็น BMP โดยใช้ Aspose.Slides สำหรับ Python ผ่าน Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="หากต้องการแปลง PPT เป็น BMP โดยใช้ Aspose.Slides สำหรับ Python ผ่าน Java คุณจะต้องนำเข้าแพ็กเกจลงในสคริปต์ Python และสร้างอินสแตนซ์ของคลาส Presentation คลาสการนำเสนอแสดงถึงเอกสาร PowerPoint และจัดเตรียมวิธีการเข้าถึงและจัดการองค์ประกอบต่างๆ" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง [**Aspose.Slides สำหรับ Python ผ่าน Java**](https://products.aspose.com/slides/th/python-java/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ให้กับโปรเจ็กต์ Python ของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เปิดไฟล์ต้นฉบับ PPT ใน Python
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์เป็นไฟล์ BMP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="แปลง PPT เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง PPT และบันทึกเป็นรูปแบบไฟล์อื่นๆ ได้ด้วย ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-pptx/" name="PPT TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-pdf/" name="PPT TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-jpg/" name="PPT TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-fodp/" name="PPT TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-odp/" name="PPT TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-otp/" name="PPT TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-pot/" name="PPT TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-potm/" name="PPT TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-potx/" name="PPT TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-pps/" name="PPT TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-pptm/" name="PPT TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-java/conversion/ppt-to-tiff/" name="PPT TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}