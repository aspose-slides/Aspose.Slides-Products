---
title: ค้นหาข้อความในไฟล์การนำเสนอ PPTX โดยใช้ .NET
url: /th/net/search/pptx/
keywords: คำค้นหาใน PPTX ค้นหาและแทนที่ข้อความใน PPTX ข้อความค้นหา PPTX
description: ซอร์สโค้ด C# เพื่อค้นหาข้อความในงานนำเสนอ PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ค้นหาข้อความ PPTX โดยใช้ C#" h2="สร้างแอป .NET ของคุณเองเพื่อค้นหาและแทนที่ข้อความในไฟล์งานนำเสนอโดยใช้ API ฝั่งเซิร์ฟเวอร์ เรียนรู้วิธีค้นหาทางเข้าทั้งหมดของคำหรือวลีในเอกสารนำเสนอ ค้นหาข้อความด้วยการจับคู่ข้อมูลที่ตรงทั้งหมดและการจับคู่นิพจน์ทั่วไป" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="ค้นหาและแทนที่ข้อความ PPTX งานนำเสนอผ่าน C#" %}}
การค้นหาเอกสารพื้นฐานและแทนที่ข้อความในเนื้อหา ความคิดเห็น บันทึกสไลด์ หรือข้อมูลเมตาด้วย API ของ Aspose.Slides for .NET สามารถทำได้ด้วยโค้ดเพียงไม่กี่บรรทัด ใช้การจับคู่นิพจน์ทั่วไป จับคู่ตัวพิมพ์เล็กและตัวพิมพ์เพื่อค้นหาข้อความในงานนำเสนอ ค้นหาข้อความในชื่อเรื่อง เนื้อหา ส่วนท้ายหรือส่วนหัว
{{% blocks/products/pf/agp/code-block title="ค้นหาข้อความ PPTX งานนำเสนอโดยใช้ C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.pptx"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีค้นหาข้อความใน PPTX ผ่าน C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการค้นหาไฟล์ข้อความ PPTX" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด PPTX ด้วยอินสแตนซ์ของงานนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ใช้เมธอด [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) เพื่อค้นหาและแทนที่ข้อความ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์ในรูปแบบ PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="ออนไลน์ PPTX ค้นหาการสาธิตสด" sectionDescription="ค้นหาและแทนที่ข้อความในเนื้อหา ความคิดเห็น หรือข้อมูลเมตาในเอกสาร PPTX ทันที" >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการค้นหาอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ C# คุณยังสามารถค้นหาข้อความในรูปแบบต่อไปนี้:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}