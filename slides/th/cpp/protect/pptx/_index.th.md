---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ป้องกันงานนำเสนอ PPTX โดยใช้ C++
url: /th/cpp/protect/pptx/
description: ป้องกันงานนำเสนอ PPTX ใน C++ ใช้ Aspose.Slides for C++ เพื่อเข้ารหัสไฟล์และตั้งค่าการป้องกันการเขียน
keywords: การป้องกันการเขียน PPTX, เข้ารหัส PPTX, ล็อกงานนำเสนอ PPTX, ป้องกัน PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ล็อกหรือป้องกัน PPTX ด้วยรหัสผ่านโดยใช้ C++" h2="ใช้ Aspose.Slides for C++ เพื่อเข้ารหัสงานนำเสนอและตั้งค่าการป้องกันการเขียนโดยไม่ต้องใช้ Microsoft PowerPoint" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ป้องกันงานนำเสนอ PPTX ผ่าน C++" variant="code" %}}

Aspose.Slides for C++ ช่วยให้คุณป้องกันไม่ให้งานนำเสนอ PPTX ถูกเปิดหรือแก้ไข ใช้ออบเจ็กต์ `ProtectionManager` จากคลาส `Presentation` เพื่อเข้ารหัสไฟล์ด้วย `Encrypt` หรือจำกัดการแก้ไขด้วย `SetWriteProtection`

{{< blocks/products/pf/slides-design-update-10-2026/code title="เข้ารหัสงานนำเสนอ PPTX โดยใช้ C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="ตั้งค่าการป้องกันการเขียนให้งานนำเสนอ PPTX โดยใช้ C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีป้องกัน PPTX ด้วยรหัสผ่านผ่าน C++" intro="ทำตามขั้นตอนต่อไปนี้เพื่อป้องกันงานนำเสนอ PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPTX ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ป้องกันงานนำเสนอด้วยออบเจ็กต์ `ProtectionManager`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ใช้ `Encrypt` สำหรับการป้องกันด้วยรหัสผ่าน หรือ `SetWriteProtection` สำหรับการป้องกันการเขียน{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ที่ป้องกันแล้วด้วย `SaveFormat::Pptx`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="สร้างด้วย Aspose.Slides" title="ป้องกันไฟล์ PPTX ด้วยรหัสผ่านทางออนไลน์" description="แอป Aspose.Slides Lock ฟรีนี้สร้างด้วย [Aspose.Slides for C++](https://products.aspose.com/slides/th/cpp/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Lock" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ป้องกันงานนำเสนออย่างไรก่อนเขียนโค้ด
- ตั้งรหัสผ่านสำหรับเปิดหรือแก้ไขไฟล์ PPTX ของคุณ
- ดาวน์โหลดไฟล์ที่ป้องกันแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการป้องกัน" subTitle="เมื่อใช้ C++ คุณยังป้องกันรูปแบบต่อไปนี้ได้ด้วย" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
