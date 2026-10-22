---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แก้ไข PPT ใน C++
url: /th/cpp/editor/ppt/
keywords: แก้ไข PPT, แก้ไข PowerPoint, PPT, PowerPoint, C++ API, C++ Library
description: แก้ไข PPT ใน C++ ใช้ API ของไลบรารี C++ เพื่อแก้ไขงานนำเสนอ PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แก้ไข PPT ใน C++" h2="ไลบรารี C++ ความเร็วสูงและข้ามแพลตฟอร์มสำหรับการแก้ไข PPT โดยใช้โค้ด C++" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แก้ไข PPT ใน C++" variant="code" %}}

เมื่อใช้ [**Aspose.Slides สำหรับ C+**](https://products.aspose.com/slides/th/cpp/) คุณสามารถเพิ่มข้อความบรรทัดใหม่ลงในเอกสาร PPT โดยใช้โค้ดเพียงไม่กี่บรรทัด

{{< blocks/products/pf/slides-design-update-10-2026/code title="รหัส C++ สำหรับแก้ไข PPT" >}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แก้ไข PPT โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ C++++](https://products.aspose.com/slides/th/cpp/) เป็นไลบรารี C++ ที่มีประสิทธิภาพซึ่งใช้เพื่อจัดการและแก้ไขงานนำเสนอ คุณสามารถแก้ไขงานนำเสนอ PPT ได้โดยเพิ่มข้อความบรรทัดใหม่ลงไป

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแก้ไข PPT ใน C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง ** Aspose.Slides สำหรับ C++++ ดู [**การติดตั้ง**](https://docs.aspose.com/slides/cpp/installation/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างอินสแตนซ์ของคลาสการนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดงานนำเสนอ PPT ที่คุณต้องการแก้ไข{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มบรรทัดใหม่ของข้อความ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ PowerPoint ที่เปลี่ยนแปลง{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="แก้ไขไฟล์อื่นๆ" subTitle="คุณยังสามารถแก้ไขไฟล์ในรูปแบบอื่นๆ" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
