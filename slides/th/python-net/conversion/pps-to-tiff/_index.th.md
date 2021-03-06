---
title: แปลง PPS เป็น TIFF ใน Python
weight: 1750
url: /th/python-net/conversion/pps-to-tiff/ 
keywords: "Convert, PowerPoint, PPS, TIFF, Presentation, Python"
description: โค้ดตัวอย่างสำหรับการแปลง PPS เป็น TIFF Python ใช้ PowerPoint Python API สำหรับการแปลงไฟล์ PPS แบบแบตช์เป็นไฟล์ TIFF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง PPS เป็น TIFF ใน Python" h2="ไลบรารี PowerPoint Python อันทรงพลังสำหรับการแปลง PPS เป็น TIFF" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="แปลง PPS เป็น TIFF ใน Python" %}}

ต้องการแปลงไฟล์ PPS เป็น TIFF โดยทางโปรแกรม? การใช้ [*Aspose.Slides สำหรับ Python ผ่าน .NET*](https://products.aspose.com/slides/th/python-net/) นักพัฒนาซอฟต์แวร์ทุกคนสามารถแปลงรูปแบบ PPS เป็น TIFF ด้วยโค้ด Python เพียงไม่กี่บรรทัด

ในฐานะที่เป็น API การประมวลผลการนำเสนอที่ทันสมัย ​​Aspose.Slides สำหรับ Python จะสร้าง TIFF จาก PPS ได้อย่างรวดเร็ว ทดสอบคุณภาพของการแปลง PPS เป็น TIFF ใน [เบราว์เซอร์](https://products.aspose.app/slides/conversion) ของคุณ Aspose ไลบรารี PowerPoint PPTX ช่วยให้คุณสามารถแปลงไฟล์ PPS เป็นรูปแบบยอดนิยมได้มากมาย

คุณสามารถติดตั้งไลบรารีจาก [PyPI](https://pypi.org/project/Aspose.Slides/) โดยใช้คำสั่ง pip ต่อไปนี้:

{{% blocks/products/pf/agp/code-block title="คอนโซล/เทอร์มินัล" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="วิธีแปลง PPS เป็น TIFF ใน Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการแปลงไฟล์ PPS เป็น TIFF โดยใช้ Python" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดไฟล์ PPS ด้วยอินสแตนซ์ของคลาสการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เรียกใช้เมธอด `บันทึก' ขณะที่ระบุพาธไฟล์เอาต์พุต & SaveFormat.TIFF เป็นพารามิเตอร์
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ไฟล์ PPS จะถูกบันทึกที่เส้นทางที่ระบุ
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

{{% blocks/products/pf/agp/code-block title="โค้ดตัวอย่างนี้แสดงการแปลง PPS เป็น TIFF Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pps") as presentation:
    presentation.save("presentation.tiff", slides.export.SaveFormat.TIFF)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="บันทึก PPS เป็น TIFF ใน Python" %}}
ใช้แอปฟรีเพื่อดูการสาธิตกระบวนการแปลง PPS เป็น TIFF 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="แอปฟรีเพื่อแปลง PPS เป็น TIFF" 
        sectionDescription="[ลองใช้แอป Text To Gif ฟรีของเรา](https://products.aspose.app/slides/text-to-gif/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PPS เป็นรูปแบบไฟล์อื่นๆ ได้อีกด้วย ดูคอนเวอร์ชั่นอื่นที่รองรับด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-bmp/" name="PPS TO BMP" description="ภาพบิตแมป" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-emf/" name="PPS TO EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-fodp/" name="PPS TO FODP" description="การนำเสนอ OpenDocument Flat XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-gif/" name="PPS TO GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-html/" name="PPS TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-jpg/" name="PPS TO JPG" description="ภาพ JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-odp/" name="PPS TO ODP" description="รูปแบบการนำเสนอ OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-otp/" name="PPS TO OTP" description="รูปแบบมาตรฐานของ OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-pdf/" name="PPS TO PDF" description="รูปแบบเอกสารพกพา" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-png/" name="PPS TO PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-pot/" name="PPS TO POT" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-potm/" name="PPS TO POTM" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-potx/" name="PPS TO POTX" description="การนำเสนอเทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="สไลด์โชว์ที่เปิดใช้งานมาโคร" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="สไลด์โชว์ PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-ppt/" name="PPS TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-pptm/" name="PPS TO PPTM" description="ไฟล์นำเสนอที่เปิดใช้งานมาโคร" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-pptx/" name="PPS TO PPTX" description="เปิดรูปแบบการนำเสนอ XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-svg/" name="PPS TO SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-swf/" name="PPS TO SWF" description="รูปแบบ SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/conversion/pps-to-xps/" name="PPS TO XPS" description="ข้อมูลจำเพาะกระดาษ XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}