---
title: ลบคำอธิบายประกอบ PPTX โดยใช้ C++
weight: 4380
url: /th/cpp/annotation/pptx/ 
description: ซอร์สโค้ด C++ เพื่อลบคำอธิบายประกอบจาก PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ลบความคิดเห็นและผู้เขียนความคิดเห็นจาก PPTX ใน C++" h2="สร้างแอป C++ ของคุณเองเพื่อจัดการความคิดเห็นและผู้เขียนในไฟล์เอกสารโดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="ลบความคิดเห็นจาก PPTX ผ่าน C++" %}}
ในการลบคำอธิบายประกอบออกจากไฟล์ PPTX เราจะใช้ [Aspose.Slides สำหรับ C++](https://products.aspose.com/slides/th/cpp/) API ซึ่งมีคุณลักษณะหลากหลาย ทรงพลัง และใช้งานง่าย API การจัดการเอกสารสำหรับแพลตฟอร์ม C++
{{% blocks/products/pf/agp/code-block title="ลบคำอธิบายประกอบจาก PPTX - C++" offSpacer="true" %}}

```cpp

using namespace Aspose::Slides;
using namespace Aspose::Slides::Export;
using namespace System::Drawing;

auto presentation = System::MakeObject<Presentation>(u"example.pptx");

// Deletes all comments from the presentation
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}
        
// Deletes all authors
presentation->get_CommentAuthors()->Clear();
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="วิธีลบความคิดเห็นจาก PPTX ผ่าน C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง ** Aspose.Slides สำหรับ C++++ ดู [**การติดตั้ง**](https://docs.aspose.com/slides/cpp/installation/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด PPTX ด้วยอินสแตนซ์ของคลาสการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
วนซ้ำผู้เขียนทั้งหมดของ PPTX ที่โหลด
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

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบคำอธิบายประกอบอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ C++ เราสามารถใส่คำอธิบายประกอบในรูปแบบอื่นๆ ได้อย่างง่ายดาย" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}