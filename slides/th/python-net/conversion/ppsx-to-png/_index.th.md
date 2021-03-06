---
title: แปลง PPSX เป็น PNG ใน Python
weight: 2080
url: /th/python-net/conversion/ppsx-to-png/ 
keywords: "Convert, PowerPoint, PPSX, PNG, Presentation, Python"
description: โค้ดตัวอย่างสำหรับการแปลง PPSX เป็น PNG Python ใช้ PowerPoint Python API สำหรับการแปลงไฟล์ PPSX เป็นไฟล์ PNG เป็นชุด
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง PPSX เป็น PNG ใน Python" h2="ไลบรารี PowerPoint Python อันทรงพลังสำหรับการแปลง PPSX เป็น PNG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="แปลง PPSX เป็น PNG ใน Python" %}}

ต้องการแปลงไฟล์ PPSX เป็น PNG โดยทางโปรแกรมหรือไม่ การใช้ [*Aspose.Slides สำหรับ Python ผ่าน .NET*](https://products.aspose.com/slides/th/python-net/) นักพัฒนาซอฟต์แวร์ทุกคนสามารถแปลงรูปแบบ PPSX เป็น PNG ด้วยโค้ด Python เพียงไม่กี่บรรทัด

ในฐานะที่เป็น API การประมวลผลการนำเสนอที่ทันสมัย ​​Aspose.Slides สำหรับ Python จะสร้าง PNG จาก PPSX ได้อย่างรวดเร็ว ทดสอบคุณภาพของการแปลง PPSX เป็น PNG ใน [เบราว์เซอร์](https://products.aspose.app/slides/conversion/ppt-to-png) ของคุณ Aspose ไลบรารี PowerPoint PPTX ช่วยให้คุณสามารถแปลงไฟล์ PPSX เป็นรูปแบบยอดนิยมได้มากมาย

คุณสามารถติดตั้งไลบรารีจาก [PyPI](https://pypi.org/project/Aspose.Slides/) โดยใช้คำสั่ง pip ต่อไปนี้:

{{% blocks/products/pf/agp/code-block title="คอนโซล/เทอร์มินัล" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="วิธีแปลง PPSX เป็น PNG ใน Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการแปลงไฟล์ PPSX เป็น PNG โดยใช้ Python" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดไฟล์ PPSX ด้วยตัวอย่างของ Presentation class
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เรียกใช้เมธอด `save` ขณะที่ระบุพาธไฟล์เอาต์พุต & SaveFormat.PNG เป็นพารามิเตอร์
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ไฟล์ PPSX จะถูกบันทึกที่เส้นทางที่ระบุ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนรันซอร์สโค้ดตัวอย่างการแปลง Python ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux (ดู [เพิ่มเติม](https://docs.aspose.com/slides/python-net/system-requirements/))
- Python 3.5 หรือใหม่กว่า
- Aspose.Slides สำหรับ Python ที่อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="โค้ดตัวอย่างนี้แสดงการแปลง PPSX เป็น PNG Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsx") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="บันทึก PPSX เป็น PNG ใน Python" %}}
ใช้แอปฟรีเพื่อดูการสาธิตกระบวนการแปลง PPSX เป็น PNG 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="แอปฟรีเพื่อแปลง PPSX เป็น PNG" 
        sectionDescription="[ลองใช้แอปฟรีของเราเพื่อแปลง PPT เพื่อ PNG](https://products.aspose.app/slides/conversion/ppt-to-png)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PPSX เป็นรูปแบบไฟล์อื่นๆ ได้อีกด้วย ดูคอนเวอร์ชั่นอื่นที่รองรับด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="ภาพบิตแมป" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-fodp/" name="PPSX TO FODP" description="การนำเสนอ OpenDocument Flat XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-html/" name="PPSX TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-jpg/" name="PPSX TO JPG" description="ภาพ JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="รูปแบบการนำเสนอ OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="รูปแบบมาตรฐานของ OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="รูปแบบเอกสารพกพา" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-pot/" name="PPSX TO POT" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="การนำเสนอเทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="สไลด์โชว์ PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="สไลด์โชว์ที่เปิดใช้งานมาโคร" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="ไฟล์นำเสนอที่เปิดใช้งานมาโคร" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="เปิดรูปแบบการนำเสนอ XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="รูปแบบ SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="ข้อมูลจำเพาะกระดาษ XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}