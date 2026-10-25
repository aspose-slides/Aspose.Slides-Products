---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: เพิ่มลายน้ำในงานนำเสนอ ODP ด้วย C++
url: /th/cpp/watermark/odp/
description: เพิ่มลายน้ำข้อความหรือรูปภาพในงานนำเสนอ ODP ใน C++ ใช้ Aspose.Slides for C++ เพื่อวางลายน้ำบนสไลด์
keywords: เพิ่มลายน้ำใน ODP, เพิ่มลายน้ำข้อความใน ODP, เพิ่มลายน้ำรูปภาพใน ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="เพิ่มลายน้ำในงานนำเสนอ ODP ด้วย C++" h2="ใช้ Aspose.Slides for C++ เพื่อเพิ่มลายน้ำข้อความหรือรูปภาพในไฟล์งานนำเสนอโดยไม่ต้องใช้ Microsoft PowerPoint" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="เพิ่มลายน้ำในงานนำเสนอ ODP ผ่าน C++" variant="code" %}}

Aspose.Slides for C++ ช่วยให้คุณเพิ่มลายน้ำข้อความหรือรูปภาพในงานนำเสนอ ODP ได้ เพิ่มรูปร่างลายน้ำลงในสไลด์ต้นแบบด้วย `AddAutoShape` เพิ่มข้อความด้วย `AddTextFrame` หรือเติมรูปร่างด้วยรูปภาพที่โหลดผ่าน `File::ReadAllBytes` และ `AddImage`

{{< blocks/products/pf/slides-design-update-10-2026/code title="เพิ่มลายน้ำข้อความใน ODP ด้วย C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="เพิ่มลายน้ำรูปภาพในงานนำเสนอ ODP ด้วย C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีเพิ่มลายน้ำใน ODP ด้วย C++" intro="ทำตามขั้นตอนเหล่านี้เพื่อเพิ่มลายน้ำข้อความหรือรูปภาพในไฟล์ ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ ODP ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เลือกสไลด์ต้นแบบจากคอลเลกชัน `Presentation::get_Masters`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มรูปร่างลายน้ำด้วยเมธอด `AddAutoShape`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มข้อความลายน้ำด้วยเมธอด `AddTextFrame` หรือตั้งค่าการเติมรูปภาพด้วย `AddImage`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ที่มีลายน้ำด้วย `SaveFormat::Odp`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="สร้างด้วย Aspose.Slides" title="เพิ่มลายน้ำในไฟล์ ODP ออนไลน์" description="แอป Aspose.Slides Watermark ฟรีนี้สร้างด้วย [Aspose.Slides for C++](https://products.aspose.com/slides/th/cpp/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ ODP ของคุณเอง" button="เปิด Aspose.Slides Watermark" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides เพิ่มลายน้ำอย่างไรก่อนเขียนโค้ด
- เพิ่มลายน้ำข้อความหรือรูปภาพในไฟล์ ODP ของคุณ
- ดาวน์โหลดไฟล์ที่มีลายน้ำ
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับลายน้ำ" subTitle="ด้วย C++ คุณยังสามารถเพิ่มลายน้ำในรูปแบบต่อไปนี้ได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
