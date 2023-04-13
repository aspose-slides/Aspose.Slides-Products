---
title: แปลง PPTX เป็น Word ใน Java
url: /th/java/conversion/pptx-to-word/
keywords: แปลง PPTX เป็น Word, PPTX เป็น Word, PPTX เป็น DOC, PowerPoint เป็น Word, Java API, Java Library
description: แปลง PPTX เป็น Word ใน Java ใช้ Java library API เพื่อแปลง PowerPoint เป็น Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง PPTX เป็น Word ใน Java" h2="Java API ข้ามแพลตฟอร์มอันทรงพลังสำหรับการแปลง PowerPoint เป็น Word โดยใช้โค้ด Java โดยไม่ต้องใช้ Microsoft PowerPoint หรือ Office" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง PowerPoint เป็น Word โดยใช้ Aspose.Slides และ Aspose.Words" %}}

[**Aspose.Slides สำหรับ Java**](https://products.aspose.com/slides/th/java/) และ [**Aspose.Words สำหรับ Java**](https://products.aspose.com/ word/java/) เป็นไลบรารี Java ที่มีประสิทธิภาพที่ใช้ในการจัดการและแปลงงานนำเสนอ PowerPoint เอกสาร Word และไฟล์อื่นๆ เมื่อคุณแปลง PowerPoint เป็น Word คุณจะย้ายเนื้อหาของสไลด์ของงานนำเสนอไปยังหน้าต่างๆ ในเอกสาร Word

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="แปลง PowerPoint เป็น Word ใน Java" %}}
คุณสามารถแปลง PPTX เป็น Word ได้อย่างรวดเร็วด้วยโค้ดเพียงไม่กี่บรรทัด

{{% blocks/products/pf/agp/code-block title="โค้ด Java สำหรับแปลง PowerPoint เป็น Word" offSpacer="true" %}}
```java
Presentation pres = new Presentation(inputPres);
try {
    Document doc = new Document();
    DocumentBuilder builder = new DocumentBuilder(doc);
    for (ISlide slide : pres.getSlides())
    {
        // generates and inserts slide image
        BufferedImage bitmap = slide.getThumbnail(1, 1);

        builder.insertImage(bitmap);

        // inserts slide's texts
        for (IShape shape : slide.getShapes())
        {
            if (shape instanceof AutoShape)
            {
                builder.writeln(((AutoShape)shape).getTextFrame().getText());
            }
        }

        builder.insertBreak(BreakType.PAGE_BREAK);
    }
    doc.save(outputDoc);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง PPTX เป็น Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง **Aposose.Slides สำหรับ Java** และ **Aspose.Words สำหรับ Java** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
สร้างอินสแตนซ์ของคลาสงานนำเสนอและคลาสเอกสาร
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดงานนำเสนอ PPTX ที่คุณต้องการแปลงเป็น Word
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
สร้างรูปภาพและข้อความตามเนื้อหาของสไลด์
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกเอกสาร Word ที่ได้
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="ตัวแปลงออนไลน์ฟรี" sectionDescription="[วิธีแปลง PPT เป็น HTML ใน Python](https://products.aspose.com/slides/th/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PowerPoint เป็นไฟล์ในรูปแบบอื่นๆ" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}