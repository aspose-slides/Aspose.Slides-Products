---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง JPG เป็น Image ใน Python
url: /th/python-net/conversion/jpg-to-image/
keywords: JPG เป็น Image, แปลง JPG เป็น Image, Python API, Python Library, JPG, Image
description: แปลง JPG เป็น Image ใน Python ใช้ Python library API เพื่อแปลงไฟล์ JPG เป็น Images
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง JPG เป็น Image ใน Python" h2="Python Library ความเร็วสูงและข้ามแพลตฟอร์มที่ช่วยในการพัฒนาแอปพลิเคชันด้วยความสามารถในการสร้าง รวม ตรวจสอบ หรือแปลงไฟล์งานนำเสนอ Microsoft PowerPoint และ OpenOffice โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Open Office, Adobe PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง JPG เป็น Image โดยใช้ Python" variant="code" %}}

หากต้องการแปลง JPG เป็น Image คุณจะต้องสร้างงานนำเสนอจากไฟล์ JPG และบันทึกเป็น Image

{{< blocks/products/pf/slides-design-update-10-2026/code title="รหัส Python สำหรับแปลง JPG เป็น Image" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง JPG เป็น Image ใน Python" %}}

[**Aspose.Slides สำหรับ Python ผ่าน .NET**](https://products.aspose.com/slides/th/python-net/) เป็นไลบรารี Python ที่มีประสิทธิภาพสำหรับการสร้างและจัดการไฟล์งานนำเสนอ นอกจากนี้ ยังมีวิธีที่ยืดหยุ่นในการแปลง JPG เป็น Image เมื่อใช้ **Aspose.Slides สำหรับ Python ผ่าน .NET** นักพัฒนาหรือแอปพลิเคชันใดๆ ก็สามารถแปลงไฟล์ JPG เป็น Image ด้วยโค้ด Python เพียงไม่กี่บรรทัด

ในฐานะ API การประมวลผลเอกสารสมัยใหม่ Aspose.Slides สำหรับ Python จะส่งออกไฟล์ JPG เป็นรูปแบบไฟล์ Image ได้อย่างรวดเร็ว ไลบรารี Aspose PowerPoint ช่วยให้คุณแปลง JPG เป็น Image และรูปแบบไฟล์อื่นๆ อีกมากมาย

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแปลง JPG เป็น Image โดยใช้ Aspose.Slides สำหรับ Python API" intro="นี่คือขั้นตอนในการแปลง JPG เป็น Image ใน Python" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง [**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/th/python-net/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ไปยังโครงการ Python ของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เปิดไฟล์ต้นฉบับ JPG ใน Python{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกผลลัพธ์เป็นไฟล์ Image{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="สร้างด้วย Aspose.Slides" title="แปลง JPG เป็น รูปภาพ ออนไลน์" description="แอป Aspose.Slides Conversion ฟรีนี้สร้างด้วย [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/th/python-net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ JPG ของคุณเอง" button="เปิด Aspose.Slides Conversion" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" upload="วางหรืออัปโหลดไฟล์ของคุณ" saveAs="บันทึกเป็น" convert="แปลง" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides แปลงไฟล์อย่างไรก่อนที่คุณจะเขียนโค้ด
- อัปโหลดไฟล์ JPG แล้วบันทึกเป็น รูปภาพ
- ดาวน์โหลดผลลัพธ์หรือแปลงไฟล์เพิ่มเติม
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="แปลง JPG เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง JPG และบันทึกเป็นรูปแบบไฟล์อื่นๆ ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
