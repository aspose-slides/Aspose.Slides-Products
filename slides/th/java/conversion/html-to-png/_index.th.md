---
title: แปลง HTML เป็น PNG ใน Java
url: /th/java/conversion/html-to-png/
keywords: HTML เป็น PNG, แปลง HTML เป็น PNG, Java API, Java Library, HTML, PNG
description: แปลง HTML เป็น PNG ใน Java ใช้ Java library API เพื่อแปลงไฟล์ HTML เป็น PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง HTML เป็น PNG ใน Java" h2="Java Library ความเร็วสูงและข้ามแพลตฟอร์มที่ช่วยในการพัฒนาแอปพลิเคชันด้วยความสามารถในการสร้าง รวม ตรวจสอบ หรือแปลงไฟล์งานนำเสนอ Microsoft PowerPoint และ OpenOffice โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Open Office, Adobe PDF" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง HTML เป็น PNG ใน Java" %}}

[**Aspose.Slides สำหรับ Java**](https://products.aspose.com/slides/th/java/) เป็นไลบรารี Java ที่ทรงพลังสำหรับการสร้างและจัดการไฟล์งานนำเสนอ นอกจากนี้ ยังมีวิธีที่ยืดหยุ่นในการแปลง HTML เป็น PNG เมื่อใช้ **Aspose.Slides สำหรับ Java** นักพัฒนาหรือแอปพลิเคชันใดๆ ก็สามารถแปลงไฟล์ HTML เป็น PNG ด้วยโค้ด Java เพียงไม่กี่บรรทัด

ในฐานะ API การประมวลผลเอกสารสมัยใหม่ Aspose.Slides สำหรับ Java จะส่งออกไฟล์ HTML เป็นรูปแบบไฟล์ PNG ได้อย่างรวดเร็ว ไลบรารี Aspose PowerPoint ช่วยให้คุณแปลง HTML เป็น PNG และรูปแบบไฟล์อื่นๆ อีกมากมาย

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลง HTML เป็น PNG โดยใช้ Java" %}}
หากต้องการแปลง HTML เป็น PNG คุณจะต้องสร้างงานนำเสนอจากไฟล์ HTML และบันทึกเป็น PNG

{{% blocks/products/pf/agp/code-block title="โค้ด Java สำหรับแปลง HTML เป็น PNG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    TextReader tr = new StreamReader("file.html");
    pres.getSlides().addFromHtml(tr);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง HTML เป็น PNG โดยใช้ Aspose.Slides สำหรับ Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการแปลง HTML เป็น PNG ใน Java" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง [**Aspose.Slides สำหรับ Java**](https://products.aspose.com/slides/th/java/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ไปยังโปรเจ็กต์ Java ของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เปิดซอร์สไฟล์ HTML ใน Java
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์เป็นไฟล์ PNG
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="แปลง HTML เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง HTML และบันทึกเป็นรูปแบบไฟล์อื่นๆ ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}