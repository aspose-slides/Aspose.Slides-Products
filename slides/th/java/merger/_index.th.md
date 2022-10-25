---
title: รวม PDF, PPT, PPTX และรูปแบบไฟล์อื่น ๆ อีกมากมายโดยใช้ Java
url: /th/java/merger/
keywords: ผสาน เข้าร่วม PowerPoint การนำเสนอ Java Aspose
description: รวมหลายไฟล์ใน Java PPT, PPTX, ODP, PDF, PNG, JPG และอีกมากมาย
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="รวม Powerpoint, PDF, PPT หรือเอกสารอื่นๆ เข้าด้วยกันใน Java" h2="ไลบรารี Java ความเร็วสูงเพื่อรวม PPT, PPTX, PDF, PNG, JPEG และรูปแบบอื่น ๆ" >}}

{{% blocks/products/pf/feature-page-section h2="ผสาน PPT, PPTX, PDF โดยใช้ Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/th/java/) เป็นไลบรารี Java อันทรงพลังสำหรับการสร้างและจัดการไฟล์นำเสนอ นอกจากนี้ยังมีวิธีที่ยืดหยุ่นในการรวมการนำเสนอ PPT/PPTX หลายรายการ เมื่อคุณรวมงานนำเสนอหนึ่งเข้ากับอีกงานนำเสนอหนึ่ง แสดงว่าคุณกำลังรวมสไลด์ของพวกเขาในงานนำเสนอเดียวอย่างมีประสิทธิภาพเพื่อรับไฟล์หนึ่ง Aspose.Slides ช่วยให้คุณสามารถรวมสองงานนำเสนอในรูปแบบต่างๆ ได้ คุณสามารถผสานงานนำเสนอกับรูปร่าง สไตล์ ข้อความ การจัดรูปแบบ ความคิดเห็น ภาพเคลื่อนไหว ฯลฯ โดยไม่ต้องกังวลว่าจะสูญเสียคุณภาพหรือข้อมูล

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="รวมงานนำเสนอ PowerPoint ใน Java" %}}
ในการผสานงานนำเสนอ PowerPoint คุณจะต้องโคลนสไลด์จากงานนำเสนอหนึ่งไปยังอีกงานนำเสนอหนึ่ง

{{% blocks/products/pf/agp/code-block title="รวมไฟล์ PPTX โดยใช้ Java" offSpacer="true" %}}

```java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge slides
for (ISlide slide : presentation2.getSlides()) {
	// Merge slides from source to target
	presentation1.getSlides().addClone(slide);
}

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="รวมการนำเสนอด้วย Slide Master โดยใช้ Java" %}}
โค้ด Java นี้สาธิตวิธีผสานการนำเสนอหลายรายการเป็นหนึ่งเดียว และใช้สไตล์จากเทมเพลตการนำเสนอต้นแบบสไลด์ ดังนั้น การนำเสนอผลลัพธ์จะคงรูปแบบต้นฉบับไว้และจะมีการจัดรูปแบบจากสไลด์ต้นแบบของงานนำเสนออื่น

{{% blocks/products/pf/agp/code-block title="รวม PPT หลายรายการเป็นไฟล์เดียวใน Java" offSpacer="true" %}}

``` java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge first two slides only using slide master
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(0), presentation1.getMasters().get_Item(0), true);
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(1), presentation1.getMasters().get_Item(0), true);

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีผสานการนำเสนอโดยใช้ Aspose.Slides สำหรับ Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการรวมไฟล์ PPTX สองไฟล์และบันทึกผลลัพธ์เป็น PDF ใน Java" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง [**Aspose.Slides for Java**](https://docs.aspose.com/slides/java/installation/) 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ไปยังโปรเจ็กต์ Java ของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เปิดไฟล์ PPTX ต้นทางใน Java
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
รวมไฟล์ PPTX โดยใช้วิธีการ **addClone**
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกงานนำเสนอและรับผลลัพธ์เป็นไฟล์ PDF ไฟล์เดียว
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบอื่นที่รองรับในการผสาน" subTitle="คุณยังสามารถรวมรูปแบบไฟล์อื่นๆ ดูรูปแบบอื่นๆ ที่รองรับด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/java/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}