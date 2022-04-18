---
title: แปลง ODP เป็น PPT ใน Python
weight: 380
url: /th/python-net/conversion/odp-to-ppt/ 
keywords: "Convert, PowerPoint, ODP, PPT, Presentation, Python"
description: โค้ดตัวอย่างสำหรับการแปลง ODP เป็น PPT Python ใช้ PowerPoint Python API สำหรับการแปลงไฟล์ ODP เป็นแบตช์เป็นไฟล์ PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง ODP เป็น PPT ใน Python" h2="ไลบรารี PowerPoint Python อันทรงพลังสำหรับการแปลง ODP เป็น PPT" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="แปลง ODP เป็น PPT ใน Python" %}}

ต้องการแปลงไฟล์ ODP เป็น PPT โดยทางโปรแกรม? การใช้ [*Aspose.Slides สำหรับ Python ผ่าน .NET*](https://products.aspose.com/slides/python-net/) นักพัฒนาซอฟต์แวร์ทุกคนสามารถแปลง ODP เป็นรูปแบบ PPT ด้วยโค้ด Python เพียงไม่กี่บรรทัด

ในฐานะที่เป็น API การประมวลผลการนำเสนอที่ทันสมัย ​​Aspose.Slides สำหรับ Python จะสร้าง PPT จาก ODP ได้อย่างรวดเร็ว ทดสอบคุณภาพของการแปลง ODP เป็น PPT ใน [เบราว์เซอร์](https://products.aspose.app/slides/conversion) ของคุณ Aspose ไลบรารี PowerPoint PPTX ช่วยให้คุณสามารถแปลงไฟล์ ODP เป็นรูปแบบยอดนิยมได้มากมาย

คุณสามารถติดตั้งไลบรารีจาก [PyPI](https://pypi.org/project/Aspose.Slides/) โดยใช้คำสั่ง pip ต่อไปนี้:

{{% blocks/products/pf/agp/code-block title="คอนโซล/เทอร์มินัล" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="วิธีแปลง ODP เป็น PPT ใน Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการแปลงไฟล์ ODP เป็น PPT โดยใช้ Python" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดไฟล์ ODP ด้วยอินสแตนซ์ของคลาสการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เรียกใช้เมธอด `บันทึก' ขณะที่ระบุพาธไฟล์เอาต์พุต & SaveFormat.PPT เป็นพารามิเตอร์
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ไฟล์ ODP จะถูกบันทึกที่เส้นทางที่ระบุ
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

{{% blocks/products/pf/agp/code-block title="โค้ดตัวอย่างนี้แสดงการแปลง ODP เป็น PPT Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.odp") as presentation:
    presentation.save("presentation.ppt", slides.export.SaveFormat.PPT)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="บันทึก ODP เป็น PPT ใน Python" %}}
ใช้แอปฟรีเพื่อดูการสาธิตกระบวนการแปลง ODP เป็น PPT 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert ODP to PPT" sectionDescription="Check our live demos for [ODP to PPT conversion](https://products.aspose.app/slides/conversion/) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your ODP file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPT file." >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง ODP เป็นรูปแบบไฟล์อื่นๆ ได้อีกมากมาย ดูคอนเวอร์ชั่นอื่นที่รองรับด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-bmp/" name="ODP TO BMP" description="ภาพบิตแมป" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-emf/" name="ODP TO EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-fodp/" name="ODP TO FODP" description="การนำเสนอ OpenDocument Flat XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-gif/" name="ODP TO GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-html/" name="ODP TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-jpg/" name="ODP TO JPG" description="ภาพ JPEG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-otp/" name="ODP TO OTP" description="รูปแบบมาตรฐานของ OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pdf/" name="ODP TO PDF" description="รูปแบบเอกสารพกพา" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-png/" name="ODP TO PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pot/" name="ODP TO POT" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-potm/" name="ODP TO POTM" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-potx/" name="ODP TO POTX" description="การนำเสนอเทมเพลต Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pps/" name="ODP TO PPS" description="สไลด์โชว์ PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="สไลด์โชว์ที่เปิดใช้งานมาโคร" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="สไลด์โชว์ PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pptm/" name="ODP TO PPTM" description="ไฟล์นำเสนอที่เปิดใช้งานมาโคร" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-pptx/" name="ODP TO PPTX" description="เปิดรูปแบบการนำเสนอ XML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-svg/" name="ODP TO SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-swf/" name="ODP TO SWF" description="รูปแบบ SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-tiff/" name="ODP TO TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/odp-to-xps/" name="ODP TO XPS" description="ข้อมูลจำเพาะกระดาษ XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}