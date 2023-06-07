---
title: ปลดล็อกไฟล์การนำเสนอ PPTX โดยใช้ Python
url: /th/python-net/unlock/pptx/
keywords: ลบการป้องกันการเขียน PPTX, ถอดรหัส PPTX, ปลดล็อกการนำเสนอ PPTX, เลิกป้องกัน PPTX
description: ซอร์สโค้ด Python เพื่อลบการป้องกันจากการนำเสนอ PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ปลดล็อก PPTX โดยใช้ Python" h2="สร้างแอป Python ของคุณเองเพื่อลบรหัสผ่านออกจาก PowerPoint และถอดรหัสไฟล์งานนำเสนอโดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="การลบการเข้ารหัสออกจากงานนำเสนอ PPTX ผ่าน Python" %}}
เมื่อใช้ Aspose.Slides for Python via .NET คุณสามารถลบการเข้ารหัสหรือการป้องกันด้วยรหัสผ่านในการนำเสนอ PPTX ด้วยวิธีนี้ ผู้ใช้จะสามารถเข้าถึงหรือแก้ไขงานนำเสนอ PPTX โดยไม่มีข้อจำกัด
{{% blocks/products/pf/agp/code-block title="ปิดใช้งานการป้องกันด้วยรหัสผ่านจาก PPTX โดยใช้ Python" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.pptx", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="การนำการป้องกันการเขียนออกจากงานนำเสนอ PPTX โดยใช้ Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.pptx") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.pptx", slides.export.SaveFormat.PPTX)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีลบรหัสผ่านจาก PPTX ผ่าน Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการนำการป้องกันออกจากไฟล์ PPTX" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด PPTX ด้วยอินสแตนซ์ของงานนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ลบการป้องกันการเขียนโดยใช้คลาส ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์ในรูปแบบ PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ Python คุณยังสามารถลบการป้องกันจากรูปแบบต่อไปนี้:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/python-net/unlock/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}