---
title: รวมรูปภาพเป็น BMP ใน Java
url: /th/java/merger/image-to-bmp/
keywords: รูปภาพเป็น BMP, รวมรูปภาพเป็น BMP, รวมรูปภาพเป็น BMP, รวมรูปภาพ, รูปภาพ, BMP, Java API, Java Library
description: รวมรูปภาพเป็น BMP ใน Java ใช้ Java library API เพื่อรวมรูปภาพ
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="รวมรูปภาพเป็น BMP ใน Java" h2="ไลบรารี Java ความเร็วสูงและข้ามแพลตฟอร์มสำหรับการผสานอิมเมจกับไฟล์ BMP โดยใช้โค้ด Java" >}}

{{% blocks/products/pf/feature-page-section h2="รวมรูปภาพเป็น BMP โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ Java**](https://products.aspose.com/slides/th/java/) คือไลบรารี Java อันทรงพลังที่ใช้สร้าง แปลง ผสาน และจัดการงานนำเสนอ PDF รูปภาพ และอื่นๆ ไฟล์. เมื่อคุณรวมรูปภาพเข้ากับ BMP คุณกำลังรวมรูปภาพอย่างมีประสิทธิภาพเพื่อให้ได้ไฟล์ BMP ไฟล์เดียว

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="รวมรูปภาพเป็น BMP ใน Java" %}}
เมื่อใช้ [**Aspose.Slides สำหรับ Java**](https://products.aspose.com/slides/th/java/) คุณสามารถผสานรูปภาพเข้ากับ BMP ได้อย่างรวดเร็วด้วยโค้ดเพียงไม่กี่บรรทัด

{{% blocks/products/pf/agp/code-block title="รหัส Java สำหรับการผสาน Image กับ BMP" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    IPPImage image1 = pres.getImages().addImage(Files.readAllBytes("image1.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image1);

    IPPImage image2 = pres.getImages().addImage(Files.readAllBytes("image2.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail();
        ImageIO.write(bufferedImage, "BMP", new File("image_java_" + index + ".bmp"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="วิธีผสาน Image เป็น BMP ใน Java" >}}


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
โหลดรูปภาพที่คุณต้องการรวมเข้าด้วยกันเป็นกรอบรูป
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกไฟล์ BMP ที่ได้
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="รวมไฟล์อื่น ๆ" subTitle="คุณยังสามารถรวมไฟล์ในรูปแบบอื่นเพื่อให้ได้ไฟล์เดียว" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}