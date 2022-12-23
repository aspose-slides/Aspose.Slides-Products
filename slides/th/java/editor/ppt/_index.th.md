---
title: แก้ไข PPT ใน Java
url: /th/java/editor/ppt/
keywords: แก้ไข PPT, แก้ไข PowerPoint, PPT, PowerPoint, Java API, Java Library
description: แก้ไข PPT ใน Java ใช้ Java library API เพื่อแก้ไขงานนำเสนอ PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แก้ไข PPT ใน Java" h2="ไลบรารี Java ความเร็วสูงและข้ามแพลตฟอร์มสำหรับแก้ไข PPT โดยใช้โค้ด Java" >}}

{{% blocks/products/pf/feature-page-section h2="แก้ไข PPT โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ Java**](https://products.aspose.com/slides/th/java/) เป็นไลบรารี Java อันทรงพลังที่ใช้ในการจัดการและแก้ไขงานนำเสนอ คุณสามารถแก้ไขงานนำเสนอ PPT ได้โดยเพิ่มข้อความบรรทัดใหม่ลงไป 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="แก้ไข PPT ใน Java" %}}
เมื่อใช้ [**Aspose.Slides สำหรับ Java**](https://products.aspose.com/slides/th/java/) คุณสามารถเพิ่มข้อความบรรทัดใหม่ลงในเอกสาร PPT โดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% blocks/products/pf/agp/code-block title="รหัส Java สำหรับแก้ไข PPT" offSpacer="true" %}}
```java

Presentation pres = new Presentation("pres.ppt");
try {
    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="วิธีแก้ไข PPT ใน Java" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง **Aposose.Slides สำหรับ Java** ดู [**การติดตั้ง**](https://docs.aspose.com/slides/java/installation/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
สร้างอินสแตนซ์ของคลาสการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดงานนำเสนอ PPT ที่คุณต้องการแก้ไข
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มบรรทัดใหม่ของข้อความ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกไฟล์ PowerPoint ที่เปลี่ยนแปลง
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="แก้ไขไฟล์อื่นๆ" subTitle="คุณยังสามารถแก้ไขไฟล์ในรูปแบบอื่นๆ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}