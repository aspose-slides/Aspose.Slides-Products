---
title: ลบคำอธิบายประกอบ PPT โดยใช้ .NET
weight: 4380
url: /th/net/annotation/ppt/ 
description: ซอร์สโค้ด C# เพื่อลบคำอธิบายประกอบรูปแบบ PPT บนแพลตฟอร์ม .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ลบความคิดเห็นและผู้เขียนความคิดเห็นจาก PPT ใน C#" h2="สร้างแอป .NET ของคุณเองเพื่อจัดการความคิดเห็นและผู้เขียนในไฟล์เอกสารโดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="ลบความคิดเห็นจาก PPT ผ่าน C#" %}}
ในการลบคำอธิบายประกอบออกจากไฟล์ PPT เราจะใช้ [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net) API ซึ่งเป็น API ที่มีคุณลักษณะหลากหลาย ทรงพลัง และใช้งานง่าย API การจัดการเอกสารสำหรับแพลตฟอร์ม C#
{{% blocks/products/pf/agp/code-block title="ลบคำอธิบายประกอบจาก PPT - C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.ppt"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="วิธีลบความคิดเห็นจาก PPT ผ่าน C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง **Aposose.Slides สำหรับ .NET** ดู [**การติดตั้ง**](https://docs.aspose.com/slides/net/installation/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด PPT ด้วยอินสแตนซ์ของคลาสการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
วนซ้ำผู้เขียนทั้งหมดของ PPT ที่โหลด
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

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบคำอธิบายประกอบอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ C# ผู้ใช้สามารถใส่คำอธิบายประกอบรูปแบบอื่นได้อย่างง่ายดาย รวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}