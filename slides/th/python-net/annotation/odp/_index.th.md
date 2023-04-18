---
title: ลบคำอธิบายประกอบ ODP โดยใช้ Python
weight: 4380
url: /th/python-net/annotation/odp/ 
description: ซอร์สโค้ด Python เพื่อลบความคิดเห็นการนำเสนอ ODP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ลบความคิดเห็นและผู้เขียนความคิดเห็นจาก ODP ใน Python" h2="สร้างสคริปต์ Python ของคุณเองเพื่อจัดการความคิดเห็นและผู้เขียนในไฟล์เอกสารโดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="ลบความคิดเห็นจาก ODP ผ่าน Python" %}}
ในการลบคำอธิบายประกอบออกจากไฟล์ ODP เราจะใช้ [Aspose.Slides สำหรับ Python ผ่าน .NET](https://products.aspose.com/slides/th/python-net/) API ซึ่งมีคุณลักษณะหลากหลาย API การจัดการเอกสารที่มีประสิทธิภาพและใช้งานง่ายสำหรับแพลตฟอร์ม Python
{{% blocks/products/pf/agp/code-block title="ลบคำอธิบายประกอบจาก ODP - Python" offSpacer="true" %}}

```python

import aspose.slides as slides

with slides.Presentation("example.odp") as presentation:
    # Deletes all comments from the presentation
    for author in presentation.comment_authors:
        author.comments.clear()

    # Deletes all authors
    presentation.comment_authors.clear()

    presentation.save("example_out.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="วิธีลบความคิดเห็นจาก ODP ผ่าน Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET**. See [**Installation**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด ODP ด้วยอินสแตนซ์ของคลาสการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
วนซ้ำผู้เขียนทั้งหมดของ ODP ที่โหลด
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ลบความคิดเห็นทั้งหมดของผู้เขียน
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ลบผู้เขียนทั้งหมดในตอนท้าย
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบคำอธิบายประกอบอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ Python ผู้ใช้สามารถใส่คำอธิบายประกอบในรูปแบบอื่นได้อย่างง่ายดาย รวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}