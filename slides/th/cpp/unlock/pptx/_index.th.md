---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ปลดล็อกงานนำเสนอ PPTX โดยใช้ C++
url: /th/cpp/unlock/pptx/
description: ปลดล็อกงานนำเสนอ PPTX ใน C++ ใช้ Aspose.Slides for C++ เพื่อลบการเข้ารหัสและการป้องกันการเขียนออกจากไฟล์งานนำเสนอ
keywords: ลบการป้องกันการเขียน PPTX, ถอดรหัส PPTX, ปลดล็อกงานนำเสนอ PPTX, ยกเลิกการป้องกัน PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ปลดล็อก PPTX โดยใช้ C++" h2="ใช้ Aspose.Slides for C++ เพื่อลบการเข้ารหัสและการป้องกันการเขียนออกจากไฟล์งานนำเสนอโดยไม่ต้องใช้ Microsoft PowerPoint" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ลบการป้องกันออกจากงานนำเสนอ PPTX ผ่าน C++" variant="code" %}}

Aspose.Slides for C++ ช่วยให้คุณลบการเข้ารหัสหรือการป้องกันการเขียนออกจากงานนำเสนอ PPTX ได้ ใช้ `LoadOptions` เพื่อเปิดไฟล์ที่เข้ารหัส จากนั้นใช้ออบเจ็กต์ `ProtectionManager` จากคลาส `Presentation` เพื่อเรียก `RemoveEncryption` หรือ `RemoveWriteProtection`

{{< blocks/products/pf/slides-design-update-10-2026/code title="ลบการป้องกันด้วยรหัสผ่านออกจาก PPTX โดยใช้ C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.pptx", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="ลบการป้องกันการเขียนออกจากงานนำเสนอ PPTX โดยใช้ C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.pptx");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีลบรหัสผ่านออกจาก PPTX ผ่าน C++" intro="ทำตามขั้นตอนต่อไปนี้เพื่อลบการป้องกันออกจากงานนำเสนอ PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPTX ด้วยคลาส `Presentation` และ `LoadOptions` เมื่อต้องใช้รหัสผ่าน{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ใช้ออบเจ็กต์ `ProtectionManager` เพื่อลบการป้องกัน{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียก `RemoveEncryption` สำหรับไฟล์ที่เข้ารหัส หรือ `RemoveWriteProtection` สำหรับไฟล์ที่ป้องกันการเขียน{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ที่ปลดล็อกแล้วด้วย `SaveFormat::Pptx`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="สร้างด้วย Aspose.Slides" title="ปลดล็อกไฟล์ PPTX ทางออนไลน์" description="แอป Aspose.Slides Unlock ฟรีนี้สร้างด้วย [Aspose.Slides for C++](https://products.aspose.com/slides/th/cpp/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Unlock" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ลบการป้องกันอย่างไรก่อนเขียนโค้ด
- ลบรหัสผ่านหรือการป้องกันการเขียนออกจากไฟล์ PPTX ของคุณ
- ดาวน์โหลดไฟล์ที่ปลดล็อกแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการปลดล็อก" subTitle="เมื่อใช้ C++ คุณยังลบการป้องกันออกจากรูปแบบต่อไปนี้ได้ด้วย" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
