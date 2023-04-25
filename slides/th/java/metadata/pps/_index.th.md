---
title: ดูหรือแก้ไขข้อมูลเมตาของไฟล์ PPS โดยใช้ Java
url: /th/java/metadata/pps/
keywords: แก้ไขข้อมูลเมตา PPS ดูข้อมูลเมตา PPS แก้ไขคุณสมบัติ PPS ดูคุณสมบัติ PPS
description: ซอร์สโค้ด Java เพื่อแก้ไขหรือดูข้อมูลเมตาของรูปแบบ PPS
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="แก้ไขคุณสมบัติ PPS โดยใช้ Java" h2="สร้างแอป Java ของคุณเองเพื่อแก้ไขคุณสมบัติในตัวและคุณสมบัติกำหนดเองในไฟล์งานนำเสนอโดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPS" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="แก้ไขคุณสมบัติ PPS ผ่าน Java" %}}
เมื่อใช้ Aspose.Slides for Java นักพัฒนาสามารถเข้าถึงและแก้ไขค่าของคุณสมบัติในตัวรวมถึงคุณสมบัติที่กำหนดเอง นักพัฒนาสามารถใช้คุณสมบัติ [DocumentProperties](https://reference.aspose.com/slides/java/com.aspose.slides/documentproperties/) ที่เปิดเผยโดยออบเจกต์การนำเสนอเพื่อเข้าถึงคุณสมบัติเอกสารของไฟล์การนำเสนอ
{{% blocks/products/pf/agp/code-block title="แก้ไข PPS คุณสมบัติในตัว - Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation("Presentation.pps");
try {
    // Create a reference to IDocumentProperties object associated with Presentation
    IDocumentProperties dp = pres.getDocumentProperties();
    
    // Set the built-in properties
    dp.setAuthor("Aspose.Slides for Java");
    dp.setTitle("Modifying Presentation Properties");
    dp.setSubject("Aspose Subject");
    dp.setComments("Aspose Description");
    dp.setManager("Aspose Manager");
    
    // Save your presentation to a file
    pres.save("DocProps.pps", SaveFormat.Pps);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="เพิ่มคุณสมบัติที่กำหนดเองใน PPS - Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    // Getting Document Properties
    IDocumentProperties dProps = pres.getDocumentProperties();
    
    // Adding Custom properties
    dProps.set_Item("New Custom", 12);
    dProps.set_Item("My Name", "Aspose Metadata Editor");
    dProps.set_Item("Custom", 124);
    
    // Getting property name at particular index
    String getPropertyName = dProps.getCustomPropertyName(2);
    
    // Removing selected property
    dProps.removeCustomProperty(getPropertyName);
    
    // Saving presentation
    pres.save("CustomDemo.pps", SaveFormat.Pps);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีดึงข้อมูลเมตาของ PPS ผ่าน Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการดึงข้อมูลเมตาจากไฟล์ PPS" >}}

{{< blocks/products/pf/agp/step-autogen >}}
สร้างอินสแตนซ์ของคลาสงานนำเสนอด้วยพาธไปยังไฟล์ PPS
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
รับวัตถุ DocumentProperties ที่เกี่ยวข้องกับการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
วนซ้ำรายการในวัตถุ DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เข้าถึงและแก้ไขคุณสมบัติแบบกำหนดเอง
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบ Metadata อื่นๆ ที่รองรับ" subTitle="เมื่อใช้ Java คุณยังสามารถจัดการข้อมูลเมตาของรูปแบบอื่นๆ ได้อีกมากมาย เช่น" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}