---
title: รวม PDF, PPT, PPTX และรูปแบบไฟล์อื่น ๆ อีกมากมายโดยใช้ C++
url: /th/cpp/merger/
keywords: ผสาน เข้าร่วม PowerPoint การนำเสนอ C++ Aspose
description: รวมหลายไฟล์ใน C++ PPT, PPTX, ODP, PDF, PNG, JPG และอีกมากมาย
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="รวม Powerpoint, PDF, PPT หรือเอกสารอื่นๆ เข้าด้วยกันใน C++" h2="ไลบรารี C++ ความเร็วสูงเพื่อรวม PPT, PPTX, PDF, PNG, JPEG และรูปแบบอื่น ๆ" >}}

{{% blocks/products/pf/feature-page-section h2="ผสาน PPT, PPTX, PDF โดยใช้ C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/th/cpp/) เป็นไลบรารี C++ อันทรงพลังสำหรับการสร้างและจัดการไฟล์การนำเสนอ นอกจากนี้ยังมีวิธีที่ยืดหยุ่นในการรวมการนำเสนอ PPT/PPTX หลายรายการ เมื่อคุณรวมงานนำเสนอหนึ่งเข้ากับอีกงานนำเสนอหนึ่ง แสดงว่าคุณกำลังรวมสไลด์ของพวกเขาในงานนำเสนอเดียวอย่างมีประสิทธิภาพเพื่อรับไฟล์หนึ่ง Aspose.Slides ช่วยให้คุณสามารถรวมสองงานนำเสนอในรูปแบบต่างๆ ได้ คุณสามารถผสานงานนำเสนอกับรูปร่าง สไตล์ ข้อความ การจัดรูปแบบ ความคิดเห็น ภาพเคลื่อนไหว ฯลฯ โดยไม่ต้องกังวลว่าจะสูญเสียคุณภาพหรือข้อมูล

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="รวมงานนำเสนอ PowerPoint ใน C++" %}}
ในการผสานงานนำเสนอ PowerPoint คุณจะต้องโคลนสไลด์จากงานนำเสนอหนึ่งไปยังอีกงานนำเสนอหนึ่ง

{{% blocks/products/pf/agp/code-block title="รวมไฟล์ PPTX โดยใช้ C++" offSpacer="true" %}}

```cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation2.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides())
{
	// Merge slides from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="รวมการนำเสนอด้วย Slide Master โดยใช้ C++" %}}
โค้ด C++ นี้สาธิตวิธีการผสานงานนำเสนอหลายรายการเป็นหนึ่งเดียวและนำสไตล์จากเทมเพลตการนำเสนอต้นแบบสไลด์ไปใช้ ดังนั้น การนำเสนอผลลัพธ์จะคงรูปแบบต้นฉบับไว้และจะมีการจัดรูปแบบจากสไลด์ต้นแบบของงานนำเสนออื่น

{{% blocks/products/pf/agp/code-block title="รวม PPT หลายรายการเป็นไฟล์เดียวใน C++" offSpacer="true" %}}

``` cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Load the presentation files
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

// Merge the first slide using slide master
presentation1->get_Slides()->AddClone(presentation2->get_Slides()->idx_get(0), presentation1->get_Masters()->idx_get(0), true);

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีผสานการนำเสนอโดยใช้ Aspose.Slides สำหรับ C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการรวมไฟล์ PPTX สองไฟล์และบันทึกผลลัพธ์เป็น PDF ใน C++" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง [**Aspose.Slides สำหรับ C++**](https://docs.aspose.com/slides/cpp/installation/) 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ไปยังโปรเจ็กต์ C++ ของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เปิดไฟล์ PPTX ต้นทางใน C ++
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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}