---
title: แปลง JPG เป็น PNG ใน Python
url: /th/python-net/conversion/jpg-to-png/
keywords: JPG เป็น PNG, แปลง JPG เป็น PNG, Python API, Python Library, JPG, PNG
description: แปลง JPG เป็น PNG ใน Python ใช้ Python library API เพื่อแปลงไฟล์ JPG เป็น PNGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง JPG เป็น PNG ใน Python" h2="Python Library ความเร็วสูงและข้ามแพลตฟอร์มที่ช่วยในการพัฒนาแอปพลิเคชันด้วยความสามารถในการสร้าง รวม ตรวจสอบ หรือแปลงไฟล์งานนำเสนอ Microsoft PowerPoint และ OpenOffice โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Open Office, Adobe PDF" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง JPG เป็น PNG ใน Python" %}}

[**Aspose.Slides สำหรับ Python ผ่าน .NET**](https://products.aspose.com/slides/th/python-net/) เป็นไลบรารี Python ที่มีประสิทธิภาพสำหรับการสร้างและจัดการไฟล์งานนำเสนอ นอกจากนี้ ยังมีวิธีที่ยืดหยุ่นในการแปลง JPG เป็น PNG เมื่อใช้ **Aspose.Slides สำหรับ Python ผ่าน .NET** นักพัฒนาหรือแอปพลิเคชันใดๆ ก็สามารถแปลงไฟล์ JPG เป็น PNG ด้วยโค้ด Python เพียงไม่กี่บรรทัด

ในฐานะ API การประมวลผลเอกสารสมัยใหม่ Aspose.Slides สำหรับ Python จะส่งออกไฟล์ JPG เป็นรูปแบบไฟล์ PNG ได้อย่างรวดเร็ว ไลบรารี Aspose PowerPoint ช่วยให้คุณแปลง JPG เป็น PNG และรูปแบบไฟล์อื่นๆ อีกมากมาย

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลง JPG เป็น PNG โดยใช้ Python" %}}
หากต้องการแปลง JPG เป็น PNG คุณจะต้องสร้างงานนำเสนอจากไฟล์ JPG และบันทึกเป็น PNG

{{% blocks/products/pf/agp/code-block title="รหัส Python สำหรับแปลง JPG เป็น PNG" offSpacer="true" %}}

```python

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as pres:
    slide = pres.slides[0]
    image = pres.images.add_image(drawing.Bitmap(dataDir+ "image.jpg"))
	slide.shapes.add_picture_frame(slides.ShapeType.RECTANGLE, 10, 10, 100, 100, image)
    for sld in pres.slides:
        bmp = sld.get_thumbnail(1, 1)
        bmp.save("Slide_{num}.png".format(num=str(sld.slide_number)), drawing.imaging.ImageFormat.png)

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง JPG เป็น PNG โดยใช้ Aspose.Slides สำหรับ Python API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการแปลง JPG เป็น PNG ใน Python" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/th/python-net/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ไปยังโครงการ Python ของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เปิดไฟล์ต้นฉบับ JPG ใน Python
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์เป็นไฟล์ PNG
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="แปลง JPG เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง JPG และบันทึกเป็นรูปแบบไฟล์อื่นๆ ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}