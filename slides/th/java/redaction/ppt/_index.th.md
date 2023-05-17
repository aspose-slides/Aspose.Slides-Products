---
title: แก้ไขไฟล์การนำเสนอ PPT โดยใช้ Java
url: /th/java/redaction/ppt/
keywords: แก้ไข PPT ค้นหาและแทนที่ข้อความใน PPT อัปเดตงานนำเสนอ PPT
description: ซอร์สโค้ด Java เพื่อค้นหาและแทนที่ข้อความในงานนำเสนอ PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="แก้ไข PPT โดยใช้ Java" h2="สร้างแอป Java ของคุณเองเพื่อค้นหาและแทนที่ข้อความในไฟล์งานนำเสนอโดยใช้ API ฝั่งเซิร์ฟเวอร์ เรียนรู้วิธีค้นหาและแทนที่ข้อความในเนื้อหา ความคิดเห็น หรือข้อมูลเมตาของงานนำเสนอ PPT" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="แก้ไขการนำเสนอ PPT ผ่าน Java" %}}
การค้นหาเอกสารพื้นฐานและแทนที่ข้อความในเนื้อหา ความคิดเห็น บันทึกสไลด์ หรือข้อมูลเมตาด้วย API ของ Aspose.Slides for Java สามารถทำได้ด้วยโค้ดเพียงไม่กี่บรรทัด ค้นหาและแทนที่ข้อความใน PowerPoint และ OpenOffice แก้ไขข้อความ ความคิดเห็น ข้อมูลเมตาในงานนำเสนอผ่านการจับคู่ข้อมูล regexp
{{% blocks/products/pf/agp/code-block title="แก้ไขการนำเสนอ PPT โดยใช้ Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีแก้ไข PPT ผ่าน Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการแก้ไขไฟล์ PPT" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด PPT ด้วยอินสแตนซ์ของงานนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ใช้เมธอด [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) เพื่อค้นหาและแทนที่ข้อความ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์ในรูปแบบ PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="ออนไลน์ PPT Redaction การสาธิตสด" sectionDescription="ค้นหาและแทนที่ข้อความในเนื้อหา ความคิดเห็น หรือข้อมูลเมตาในเอกสาร PPT ทันที" >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบ Redact อื่น ๆ ที่รองรับ" subTitle="เมื่อใช้ Java คุณยังสามารถแก้ไขรูปแบบต่อไปนี้ได้ด้วย:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}