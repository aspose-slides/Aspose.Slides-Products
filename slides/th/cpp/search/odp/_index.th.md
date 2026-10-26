---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ค้นหาข้อความในงานนำเสนอ ODP ด้วย C++
url: /th/cpp/search/odp/
description: ค้นหาข้อความในงานนำเสนอ ODP ด้วย C++ ใช้ Aspose.Slides for C++ เพื่อหาข้อความในไฟล์งานนำเสนอ
keywords: ค้นหาคำใน ODP, หาข้อความใน ODP, ค้นหาข้อความในงานนำเสนอ ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ค้นหาข้อความใน ODP ด้วย C++" h2="ใช้ Aspose.Slides for C++ เพื่อหาข้อความในไฟล์งานนำเสนอโดยไม่ต้องใช้ Microsoft PowerPoint" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ค้นหาข้อความในงานนำเสนอ ODP ผ่าน C++" variant="code" %}}

Aspose.Slides for C++ ช่วยให้คุณค้นหาข้อความในงานนำเสนอ ODP ได้ ใช้ `SlideUtil::GetAllTextBoxes` เพื่อรวบรวมกรอบข้อความของสไลด์ แล้วตรวจสอบว่าข้อความมีวลีที่ต้องการหรือไม่

{{< blocks/products/pf/slides-design-update-10-2026/code title="ค้นหาข้อความในงานนำเสนอ ODP โดยใช้ C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีค้นหาข้อความใน ODP ผ่าน C++" intro="ทำตามขั้นตอนต่อไปนี้เพื่อค้นหาข้อความในงานนำเสนอ ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ ODP ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ดึงสไลด์ที่ต้องการด้วย `Presentation::get_Slides` และดึงกรอบข้อความของสไลด์ด้วย [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ตรวจสอบว่าข้อความของแต่ละกรอบมีวลีที่ต้องการหรือไม่{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="สร้างด้วย Aspose.Slides" title="ค้นหาข้อความในไฟล์ ODP ออนไลน์" description="แอป Aspose.Slides Search ฟรีนี้สร้างด้วย [Aspose.Slides for C++](https://products.aspose.com/slides/th/cpp/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ ODP ของคุณเอง" button="เปิด Aspose.Slides Search" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ค้นหาข้อความอย่างไรก่อนเขียนโค้ด
- ค้นหาข้อความธรรมดาหรือนิพจน์ทั่วไปในไฟล์ ODP ของคุณ
- ดาวน์โหลดผลการค้นหาเป็นไฟล์ข้อความ
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการค้นหา" subTitle="ด้วย C++ คุณยังสามารถค้นหาข้อความในรูปแบบต่อไปนี้ได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
