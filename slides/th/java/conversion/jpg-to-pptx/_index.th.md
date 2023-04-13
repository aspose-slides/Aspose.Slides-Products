---
title: แปลง JPG เป็น PPTX ใน Java
url: /th/java/conversion/jpg-to-pptx/
keywords: แปลง JPG เป็น PPTX, JPG เป็น PPTX, PowerPoint, JPG, PPTX, Java API, Java Library
description: แปลง JPG เป็น PPTX ใน Java ใช้ Java library API เพื่อแปลงรูปภาพ JPG เป็น PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง JPG เป็น PPTX ใน Java" h2="Java API ข้ามแพลตฟอร์มอันทรงพลังสำหรับการแปลง JPG เป็น PPTX โดยใช้โค้ด Java" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง JPG เป็น PPTX โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ Java**](https://products.aspose.com/slides/th/java/) เป็นไลบรารี Java อันทรงพลังที่ใช้สร้าง แปลง และจัดการงานนำเสนอ PowerPoint, PDF, เอกสาร HTML และอื่นๆ ไฟล์. เมื่อคุณแปลง JPG เป็น PPTX คุณกำลังสร้างงานนำเสนอ PowerPoint ที่มีสไลด์ตามรูปภาพ JPG

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="แปลง JPG เป็น PPTX ใน Java" %}}
การใช้ [**Aspose.Slides for Java**](https://products.aspose.com/slides/th/java/) คุณสามารถแปลงรูปภาพ JPG เป็นงานนำเสนอ PowerPoint โดยใช้โค้ดเพียงไม่กี่บรรทัด:

{{% blocks/products/pf/agp/code-block title="โค้ด Java สำหรับแปลง JPG เป็น PPTX" offSpacer="true" %}}
```java
Presentation pres = new Presentation();
try {
	ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);

	pres.save("pres.pptx", SaveFormat.Pptx);
} finally {
	if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง JPG เป็น PPTX ใน Java" >}}


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
โหลดภาพ JPG ที่คุณต้องการแปลงเป็น PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกไฟล์ผลลัพธ์เป็นงานนำเสนอ PPTX
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="ตัวแปลงออนไลน์ฟรี" sectionDescription="[วิธีแปลง PPT เป็น HTML ใน Python](https://products.aspose.com/slides/th/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="การแปลง PowerPoint อื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลงไฟล์ในรูปแบบอื่นเป็น PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}