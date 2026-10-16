---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง PDF เป็น FODP ใน Python
weight: 690
url: /th/python-net/conversion/pdf-to-fodp/ 
keywords: "Convert, PowerPoint, PDF, FODP, Presentation, Python"
description: โค้ดตัวอย่างสำหรับการแปลง PDF เป็น FODP Python ใช้ PowerPoint Python API สำหรับการแปลงไฟล์ PDF เป็นชุดเป็นไฟล์ FODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง PDF เป็น FODP ใน Python" h2="ไลบรารี PowerPoint Python อันทรงพลังสำหรับการแปลง PDF เป็น FODP"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง PDF เป็น FODP ใน Python" %}}

ต้องการแปลงไฟล์ PDF เป็น FODP โดยทางโปรแกรมหรือไม่ การใช้ [*Aspose.Slides สำหรับ Python ผ่าน .NET*](https://products.aspose.com/slides/th/python-net/) นักพัฒนาซอฟต์แวร์ทุกคนสามารถแปลง PDF เป็นรูปแบบ FODP ด้วยโค้ด Python เพียงไม่กี่บรรทัด

ในฐานะที่เป็น API การประมวลผลการนำเสนอที่ทันสมัย ​​Aspose.Slides สำหรับ Python จะสร้าง FODP จาก PDF ได้อย่างรวดเร็ว ทดสอบคุณภาพของการแปลง PDF เป็น FODP ใน [เบราว์เซอร์](https://products.aspose.app/slides/conversion) ของคุณ Aspose ไลบรารี PowerPoint PPTX ช่วยให้คุณสามารถแปลงไฟล์ PDF เป็นรูปแบบยอดนิยมได้มากมาย

คุณสามารถติดตั้งไลบรารีจาก [PyPI](https://pypi.org/project/Aspose.Slides/) โดยใช้คำสั่ง pip ต่อไปนี้:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="คอนโซล/เทอร์มินัล" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="บันทึก PDF เป็น FODP ใน Python" %}}

ใช้แอพฟรีเพื่อดูการสาธิตกระบวนการแปลง PDF เป็น FODP

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="โค้ดตัวอย่างนี้แสดงการแปลงไฟล์ PDF เป็น FODP Python" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("presentation.fodp", slides.export.SaveFormat.FODP)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแปลง PDF เป็น FODP ใน Python" intro="นี่คือขั้นตอนในการแปลงไฟล์ PDF เป็น FODP โดยใช้ Python" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PDF ด้วยตัวอย่างของ Presentation class{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกใช้เมธอด `บันทึก' ขณะที่ระบุพาธไฟล์เอาต์พุต & SaveFormat.FODP เป็นพารามิเตอร์{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ไฟล์ PDF จะถูกบันทึกตามเส้นทางที่ระบุ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="ความต้องการของระบบ" intro="ก่อนรันซอร์สโค้ดตัวอย่างการแปลง Python ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นต่อไปนี้" %}}

- ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux (ดู [เพิ่มเติม](https://docs.aspose.com/slides/python-net/system-requirements/))
- Python 3.5 หรือใหม่กว่า
- Aspose.Slides สำหรับ Python ที่อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="แอปฟรีเพื่อแปลง PDF เป็น FODP"
  description="[ลองใช้แอปฟรีของเราเพื่อแปลง PDF เพื่อ FODP](https://products.aspose.app/slides/import/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PDF เป็นรูปแบบไฟล์อื่นๆ ได้อีกด้วย ดูคอนเวอร์ชั่นอื่นที่รองรับด้านล่าง" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-bmp/" name="PDF TO BMP" description="ภาพบิตแมป" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-emf/" name="PDF TO EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-gif/" name="PDF TO GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-html/" name="PDF TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-jpg/" name="PDF TO JPG" description="ภาพ JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-odp/" name="PDF TO ODP" description="รูปแบบการนำเสนอ OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-otp/" name="PDF TO OTP" description="รูปแบบมาตรฐานของ OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-png/" name="PDF TO PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-pot/" name="PDF TO POT" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-potm/" name="PDF TO POTM" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-potx/" name="PDF TO POTX" description="การนำเสนอเทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-pps/" name="PDF TO PPS" description="สไลด์โชว์ PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" description="สไลด์โชว์ที่เปิดใช้งานมาโคร" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="สไลด์โชว์ PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="ไฟล์นำเสนอที่เปิดใช้งานมาโคร" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="เปิดรูปแบบการนำเสนอ XML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-svg/" name="PDF TO SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-swf/" name="PDF TO SWF" description="รูปแบบ SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/python-net/conversion/pdf-to-xps/" name="PDF TO XPS" description="ข้อมูลจำเพาะกระดาษ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
