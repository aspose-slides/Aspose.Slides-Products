---
title: แปลง PPSM เป็น SVG ใน Python
weight: 1950
url: /th/python-net/conversion/ppsm-to-svg/ 
keywords: "Convert, PowerPoint, PPSM, SVG, Presentation, Python"
description: โค้ดตัวอย่างสำหรับการแปลง PPSM เป็น SVG Python ใช้ PowerPoint Python API สำหรับการแปลงไฟล์ PPSM แบบกลุ่มเป็นไฟล์ SVG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง PPSM เป็น SVG ใน Python" h2="ไลบรารี PowerPoint Python อันทรงพลังสำหรับการแปลง PPSM เป็น SVG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="แปลง PPSM เป็น SVG ใน Python" %}}

ต้องการแปลงไฟล์ PPSM เป็น SVG โดยทางโปรแกรมหรือไม่ การใช้ [*Aspose.Slides สำหรับ Python ผ่าน .NET*](https://products.aspose.com/slides/python-net/) นักพัฒนาซอฟต์แวร์ทุกคนสามารถแปลงรูปแบบ PPSM เป็น SVG ด้วยโค้ด Python เพียงไม่กี่บรรทัด

ในฐานะที่เป็น API การประมวลผลการนำเสนอที่ทันสมัย ​​Aspose.Slides สำหรับ Python จะสร้าง SVG จาก PPSM ได้อย่างรวดเร็ว ทดสอบคุณภาพของการแปลง PPSM เป็น SVG ใน [เบราว์เซอร์](https://products.aspose.app/slides/conversion) ของคุณ Aspose ไลบรารี PowerPoint PPTX ช่วยให้คุณสามารถแปลงไฟล์ PPSM เป็นรูปแบบยอดนิยมได้มากมาย

คุณสามารถติดตั้งไลบรารีจาก [PyPI](https://pypi.org/project/Aspose.Slides/) โดยใช้คำสั่ง pip ต่อไปนี้:

{{% blocks/products/pf/agp/code-block title="คอนโซล/เทอร์มินัล" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="วิธีแปลง PPSM เป็น SVG ใน Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการแปลงไฟล์ PPSM เป็น SVG โดยใช้ Python" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดไฟล์ PPSM ด้วยอินสแตนซ์ของคลาสการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เรียกใช้เมธอด `บันทึก' ขณะที่ระบุพาธไฟล์เอาต์พุต & SaveFormat.SVG เป็นพารามิเตอร์
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ไฟล์ PPSM จะถูกบันทึกที่เส้นทางที่ระบุ
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

{{% blocks/products/pf/agp/code-block title="โค้ดตัวอย่างนี้แสดงการแปลง PPSM เป็น SVG Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsm") as presentation:
    for slide in presentation.slides:
        with open("presentation_slide_{0}.svg".format(str(slide.slide_number)), "wb") as file:
            slide.write_as_svg(file)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="บันทึก PPSM เป็น SVG ใน Python" %}}
ใช้แอปฟรีเพื่อดูการสาธิตกระบวนการแปลง PPSM เป็น SVG 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert PPSM to SVG" sectionDescription="Check our live demos for [PPSM to SVG conversion](https://products.aspose.app/slides/conversion/) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPSM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant SVG file." >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PPSM เป็นรูปแบบไฟล์อื่นๆ ได้อีกด้วย ดูคอนเวอร์ชั่นอื่นที่รองรับด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="ภาพบิตแมป" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-fodp/" name="PPSM TO FODP" description="การนำเสนอ OpenDocument Flat XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-html/" name="PPSM TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-jpg/" name="PPSM TO JPG" description="ภาพ JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="รูปแบบการนำเสนอ OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="รูปแบบมาตรฐานของ OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="รูปแบบเอกสารพกพา" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-png/" name="PPSM TO PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-pot/" name="PPSM TO POT" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="การนำเสนอเทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="สไลด์โชว์ PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="สไลด์โชว์ PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="ไฟล์นำเสนอที่เปิดใช้งานมาโคร" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="เปิดรูปแบบการนำเสนอ XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="รูปแบบ SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="ข้อมูลจำเพาะกระดาษ XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}