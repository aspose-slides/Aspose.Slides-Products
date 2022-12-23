---
title: แก้ไข PPT ใน C++
url: /th/cpp/editor/ppt/
keywords: แก้ไข PPT, แก้ไข PowerPoint, PPT, PowerPoint, C++ API, C++ Library
description: แก้ไข PPT ใน C++ ใช้ API ของไลบรารี C++ เพื่อแก้ไขงานนำเสนอ PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แก้ไข PPT ใน C++" h2="ไลบรารี C++ ความเร็วสูงและข้ามแพลตฟอร์มสำหรับการแก้ไข PPT โดยใช้โค้ด C++" >}}

{{% blocks/products/pf/feature-page-section h2="แก้ไข PPT โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ C++++](https://products.aspose.com/slides/th/cpp/) เป็นไลบรารี C++ ที่มีประสิทธิภาพซึ่งใช้เพื่อจัดการและแก้ไขงานนำเสนอ คุณสามารถแก้ไขงานนำเสนอ PPT ได้โดยเพิ่มข้อความบรรทัดใหม่ลงไป 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="แก้ไข PPT ใน C++" %}}
เมื่อใช้ [**Aspose.Slides สำหรับ C+**](https://products.aspose.com/slides/th/cpp/) คุณสามารถเพิ่มข้อความบรรทัดใหม่ลงในเอกสาร PPT โดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% blocks/products/pf/agp/code-block title="รหัส C++ สำหรับแก้ไข PPT" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="วิธีแก้ไข PPT ใน C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง ** Aspose.Slides สำหรับ C++++ ดู [**การติดตั้ง**](https://docs.aspose.com/slides/cpp/installation/)
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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}