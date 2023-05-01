---
title: แยกข้อความและรูปภาพจากไฟล์ PPTX โดยใช้ Python
url: /th/python-net/parser/pptx/
keywords: แยก PPTX โดยใช้ Python, PPTX แยกวิเคราะห์ Python, แยกข้อมูลจาก PPTX ใน Python, แยกข้อความจาก PPTX โดยใช้ Python, แยกรูปภาพจาก PPTX โดยใช้ Python
description: ซอร์สโค้ด Python เพื่อแยกวิเคราะห์การนำเสนอ PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="แยกข้อความและรูปภาพจากงานนำเสนอ PPTX โดยใช้ Python" h2="สร้างแอป Python ของคุณเองเพื่อแยกข้อความ รูปภาพ วิดีโอ และไฟล์เสียงจาก PowerPoint โดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="แยกข้อความจากการนำเสนอ PPTX ผ่าน Python" %}}
หากต้องการสแกนข้อความจากงานนำเสนอทั้งหมด ให้ใช้เมธอดแบบสแตติก [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) ที่เปิดเผยโดยคลาส SlideUtil โค้ดด้านล่างจะสแกนข้อความและข้อมูลการจัดรูปแบบจากงานนำเสนอ รวมถึงสไลด์ต้นแบบ
{{% blocks/products/pf/agp/code-block title="แยกข้อความจากงานนำเสนอ PPTX โดยใช้ Python" offSpacer="true" %}}

```py

import aspose.slides as slides

#Instatiate Presentation class that represents a PPTX file
with slides.Presentation("pres.pptx") as pptxPresentation:
    # Get an Array of ITextFrame objects from all slides in the PPTX
    textFramesPPTX = slides.util.SlideUtil.get_all_text_frames(pptxPresentation, True)
    
    # Loop through the Array of TextFrames
    for i in range(len(textFramesPPTX)):
	    # Loop through paragraphs in current ITextFrame
        for para in textFramesPPTX[i].paragraphs:
            # Loop through portions in the current IParagraph
            for port in para.portions:
			    # Display text in the current portion
                print(port.text)

    			# Display font height of the text
                print(port.portion_format.font_height)

			    # Display font name of the text
                if port.portion_format.latin_font != None:
                    print(port.portion_format.latin_font.font_name)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีแยกข้อความจาก PPTX ผ่าน Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการแยกวิเคราะห์ไฟล์ PPTX" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด PPTX ด้วยอินสแตนซ์ของงานนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
รับวัตถุ Array of TextFrame จากสไลด์ทั้งหมดใน PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
วนซ้ำ Array ของ TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
วนซ้ำย่อหน้าใน TextFrame ปัจจุบัน
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
วนซ้ำส่วนต่างๆ ในย่อหน้าปัจจุบัน
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
รับข้อความในส่วนปัจจุบัน
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการแยกวิเคราะห์อื่น ๆ ที่รองรับ" subTitle="เมื่อใช้ Python คุณยังสามารถสแกนรูปแบบต่อไปนี้:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/parser/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}