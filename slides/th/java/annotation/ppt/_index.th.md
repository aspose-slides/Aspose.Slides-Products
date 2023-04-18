---
title: ลบคำอธิบายประกอบ PPT โดยใช้ Java
weight: 3630
url: /th/java/annotation/ppt/ 
description: โค้ดตัวอย่าง Java เพื่อลบคำอธิบายประกอบรูปแบบ PPT บน Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และเดสก์ท็อปแอปพลิเคชัน
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ลบความคิดเห็นและผู้เขียนความคิดเห็นจาก PPT ใน Java" h2="สร้างแอป Java ของคุณเองเพื่อจัดการความคิดเห็นและผู้เขียนในไฟล์เอกสารโดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="ลบความคิดเห็นจาก PPT ผ่าน Java" %}}
ในการลบคำอธิบายประกอบออกจากไฟล์ PPT เราจะใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/th/java/) API ซึ่งเป็น API ที่มีคุณลักษณะหลากหลาย ทรงพลัง และใช้งานง่าย API การจัดการเอกสารสำหรับแพลตฟอร์ม Java
{{% blocks/products/pf/agp/code-block title="ลบคำอธิบายประกอบจาก PPT - Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.ppt");
try {
    // Deletes all comments from the presentation
    for (ICommentAuthor author : presentation.getCommentAuthors())
    {
        author.getComments().clear();
    }

    // Deletes all authors
    presentation.getCommentAuthors().clear();

    presentation.save("example_out.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="วิธีลบความคิดเห็นจาก PPT ผ่าน Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง **Aposose.Slides สำหรับ Java** ดู [**การติดตั้ง**](https://docs.aspose.com/slides/java/installation/)
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

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบคำอธิบายประกอบอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ Java ผู้ใช้สามารถใส่คำอธิบายประกอบรูปแบบอื่นๆ ได้อย่างง่ายดาย รวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}