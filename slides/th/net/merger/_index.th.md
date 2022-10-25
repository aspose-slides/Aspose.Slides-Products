---
title: รวม PDF, PPT, PPTX และรูปแบบไฟล์อื่น ๆ อีกมากมายโดยใช้ C #
url: /th/net/merger/
keywords: ผสาน เข้าร่วม PowerPoint การนำเสนอ C# .NET Aspose
description: รวมหลายไฟล์ใน C# PPT, PPTX, ODP, PDF, PNG, JPG และอีกมากมาย
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="รวม Powerpoint, PDF, PPT หรือเอกสารอื่นๆ เข้าด้วยกันใน C#" h2="ไลบรารี C# ความเร็วสูงเพื่อรวม PPT, PPTX, PDF, PNG, JPEG และรูปแบบอื่น ๆ" >}}

{{% blocks/products/pf/feature-page-section h2="รวม PPT, PPTX, PDF โดยใช้ C #" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/th/net/) เป็นไลบรารี C# อันทรงพลังสำหรับการสร้างและจัดการไฟล์นำเสนอ นอกจากนี้ยังมีวิธีที่ยืดหยุ่นในการรวมการนำเสนอ PPT/PPTX หลายรายการ เมื่อคุณรวมงานนำเสนอหนึ่งเข้ากับอีกงานนำเสนอหนึ่ง แสดงว่าคุณกำลังรวมสไลด์ของพวกเขาในงานนำเสนอเดียวอย่างมีประสิทธิภาพเพื่อรับไฟล์หนึ่ง Aspose.Slides ช่วยให้คุณสามารถรวมสองงานนำเสนอในรูปแบบต่างๆ ได้ คุณสามารถผสานงานนำเสนอกับรูปร่าง สไตล์ ข้อความ การจัดรูปแบบ ความคิดเห็น ภาพเคลื่อนไหว ฯลฯ โดยไม่ต้องกังวลว่าจะสูญเสียคุณภาพหรือข้อมูล

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="รวมงานนำเสนอ PowerPoint ใน C #" %}}
ในการผสานงานนำเสนอ PowerPoint คุณจะต้องโคลนสไลด์จากงานนำเสนอหนึ่งไปยังอีกงานนำเสนอหนึ่ง

{{% blocks/products/pf/agp/code-block title="รวมไฟล์ PPTX โดยใช้ C #" offSpacer="true" %}}

```csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        foreach (ISlide slide in presentation2.Slides)
        {
            // Merge slides from source to target 
            presentation1.Slides.AddClone(slide);
        }
    }
    // Save the presentation
    presentation1.Save("merged-presentation.pptx", Export.SaveFormat.Pptx);
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ผสานการนำเสนอด้วย Slide Master โดยใช้ C#" %}}
โค้ด C# นี้สาธิตวิธีผสานงานนำเสนอหลายรายการเป็นหนึ่งเดียวและนำสไตล์จากเทมเพลตการนำเสนอต้นแบบสไลด์ไปใช้ ดังนั้น การนำเสนอผลลัพธ์จะคงรูปแบบต้นฉบับไว้และจะมีการจัดรูปแบบจากสไลด์ต้นแบบของงานนำเสนออื่น

{{% blocks/products/pf/agp/code-block title="รวม PPT หลายรายการเป็นไฟล์เดียวใน C #" offSpacer="true" %}}

``` csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        // Merge first two slides only using slide master
        presentation1.Slides.AddClone(presentation2.Slides[0], presentation1.Masters[0], true);
        presentation1.Slides.AddClone(presentation2.Slides[1], presentation1.Masters[0], true);
    }
    presentation1.Save("merged-presentation-master.pptx", Export.SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีผสานการนำเสนอโดยใช้ Aspose.Slides สำหรับ .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการรวมไฟล์ PPTX สองไฟล์และบันทึกผลลัพธ์เป็น PDF ใน .NET" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง [**Aspose.Slides for .NET**](https://docs.aspose.com/slides/net/installation/) 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ไปยังโปรเจ็กต์ C# ของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เปิดไฟล์ PPTX ต้นทางใน C #
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
รวมไฟล์ PPTX โดยใช้วิธีการ **AddClone**
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกงานนำเสนอและรับผลลัพธ์เป็นไฟล์ PDF ไฟล์เดียว
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบอื่นที่รองรับในการผสาน" subTitle="คุณยังสามารถรวมรูปแบบไฟล์อื่นๆ ดูรูปแบบอื่นๆ ที่รองรับด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}