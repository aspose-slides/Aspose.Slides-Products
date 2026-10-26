---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ปกปิดข้อมูลในงานนำเสนอ PPTX ด้วย C++
url: /th/cpp/redaction/pptx/
description: ปกปิดข้อมูลในงานนำเสนอ PPTX ด้วย C++ ใช้ Aspose.Slides for C++ เพื่อค้นหาและแทนที่ข้อความที่ละเอียดอ่อนในไฟล์งานนำเสนอ
keywords: ปกปิดข้อมูล PPTX, ค้นหาและแทนที่ข้อความใน PPTX, อัปเดตงานนำเสนอ PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ปกปิดข้อมูลใน PPTX ด้วย C++" h2="ใช้ Aspose.Slides for C++ เพื่อค้นหาและแทนที่ข้อความที่ละเอียดอ่อนในไฟล์งานนำเสนอโดยไม่ต้องใช้ Microsoft PowerPoint" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ปกปิดข้อมูลในงานนำเสนอ PPTX ผ่าน C++" variant="code" %}}

Aspose.Slides for C++ ช่วยให้คุณปกปิดข้อมูลในงานนำเสนอ PPTX ได้โดยแทนที่ข้อความที่ละเอียดอ่อนในสไลด์ ใช้ `SlideUtil::FindAndReplaceText` ร่วมกับออบเจ็กต์ `Presentation` เพื่อค้นหาในงานนำเสนอและแทนที่ข้อความที่ตรงกันก่อนบันทึกไฟล์ที่อัปเดตแล้ว

{{< blocks/products/pf/slides-design-update-10-2026/code title="ปกปิดข้อมูลในงานนำเสนอ PPTX โดยใช้ C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีปกปิดข้อมูลใน PPTX ผ่าน C++" intro="ทำตามขั้นตอนต่อไปนี้เพื่อปกปิดข้อมูลในงานนำเสนอ PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPTX ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ใช้เมธอด [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) เพื่อค้นหาและแทนที่ข้อความที่ละเอียดอ่อน{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ที่ปกปิดข้อมูลแล้วด้วย `SaveFormat::Pptx`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="สร้างด้วย Aspose.Slides" title="ปกปิดข้อมูลในไฟล์ PPTX ออนไลน์" description="แอป Aspose.Slides Redaction ฟรีนี้สร้างด้วย [Aspose.Slides for C++](https://products.aspose.com/slides/th/cpp/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Redaction" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ค้นหาและแทนที่ข้อความอย่างไรก่อนเขียนโค้ด
- ค้นหาและแทนที่ข้อความในไฟล์ PPTX ของคุณ รวมถึงด้วยนิพจน์ทั่วไป
- ดาวน์โหลดไฟล์ที่ปกปิดข้อมูลแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการปกปิดข้อมูล" subTitle="ด้วย C++ คุณยังสามารถปกปิดข้อมูลในรูปแบบต่อไปนี้ได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
