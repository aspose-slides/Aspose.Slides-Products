---
title: ปลดล็อกไฟล์การนำเสนอ PPT โดยใช้ Java
url: /th/java/unlock/ppt/
keywords: ลบการป้องกันการเขียน PPT, ถอดรหัส PPT, ปลดล็อกการนำเสนอ PPT, เลิกป้องกัน PPT
description: ซอร์สโค้ด Java เพื่อลบการป้องกันจากการนำเสนอ PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ปลดล็อก PPT โดยใช้ Java" h2="สร้างแอป Java ของคุณเองเพื่อลบรหัสผ่านออกจาก PowerPoint และถอดรหัสไฟล์งานนำเสนอโดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="การลบการเข้ารหัสออกจากงานนำเสนอ PPT ผ่าน Java" %}}
เมื่อใช้ Aspose.Slides for Java คุณสามารถลบการเข้ารหัสหรือการป้องกันด้วยรหัสผ่านในการนำเสนอ PPT ด้วยวิธีนี้ ผู้ใช้จะสามารถเข้าถึงหรือแก้ไขงานนำเสนอ PPT โดยไม่มีข้อจำกัด
{{% blocks/products/pf/agp/code-block title="ปิดใช้งานการป้องกันด้วยรหัสผ่านจาก PPT โดยใช้ Java" offSpacer="true" %}}

```java

LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");
Presentation presentation = new Presentation("pres.ppt", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="การนำการป้องกันการเขียนออกจากงานนำเสนอ PPT โดยใช้ Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.ppt");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีลบรหัสผ่านจาก PPT ผ่าน Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการนำการป้องกันออกจากไฟล์ PPT" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด PPT ด้วยอินสแตนซ์ของงานนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ลบการป้องกันการเขียนโดยใช้คลาส ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์ในรูปแบบ PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ Java คุณยังสามารถลบการป้องกันจากรูปแบบต่อไปนี้:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}