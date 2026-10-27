---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: ลบคำอธิบายประกอบ ODP ด้วย C++
url: /th/cpp/annotation/odp/ 
description: ซอร์สโค้ด C++ สำหรับลบคำอธิบายประกอบออกจากงานนำเสนอ ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ลบความคิดเห็นและผู้เขียนความคิดเห็นออกจาก ODP ใน C++" h2="สร้างแอป C++ ที่จัดการความคิดเห็นและผู้เขียนในไฟล์งานนำเสนอด้วย API ฝั่งเซิร์ฟเวอร์" related="PPTX,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ลบความคิดเห็นออกจาก ODP ผ่าน C++" variant="code" %}}

ใช้ [Aspose.Slides for C++](/slides/th/cpp/) เพื่อลบความคิดเห็นและผู้เขียนความคิดเห็นออกจากงานนำเสนอ ODP ตัวอย่างด้านล่างจะล้างความคิดเห็นของผู้เขียนแต่ละคนจาก `get_CommentAuthors` แล้วล้างคอลเลกชันผู้เขียนความคิดเห็น

{{< blocks/products/pf/slides-design-update-10-2026/code title="ลบคำอธิบายประกอบออกจาก ODP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.odp");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีลบความคิดเห็นออกจาก ODP ผ่าน C++" intro="ทำตามขั้นตอนเหล่านี้เพื่อลบความคิดเห็นและผู้เขียนความคิดเห็นออกจากงานนำเสนอ ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง Aspose.Slides for C++ ดู [การติดตั้ง](https://docs.aspose.com/slides/cpp/installation/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ ODP ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนซ้ำผู้เขียนความคิดเห็นจาก `get_CommentAuthors`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ล้างความคิดเห็นของผู้เขียนแต่ละคนด้วย `get_Comments()->Clear()`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ล้างคอลเลกชันผู้เขียนความคิดเห็น{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกงานนำเสนอที่อัปเดตแล้วด้วย `SaveFormat::Odp`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="สร้างด้วย Aspose.Slides" title="ลบความคิดเห็น ODP ออนไลน์" description="แอป Aspose.Slides Annotation ฟรีนี้สร้างด้วย [Aspose.Slides for C++](https://products.aspose.com/slides/th/cpp/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ ODP ของคุณเอง" button="เปิด Aspose.Slides Annotation" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ลบความคิดเห็นอย่างไรก่อนเขียนโค้ด
- ลบความคิดเห็นทั้งหมดออกจากไฟล์ ODP ของคุณ
- ดาวน์โหลดไฟล์ที่ล้างแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับสำหรับคำอธิบายประกอบ" subTitle="ด้วย C++ คุณยังลบคำอธิบายประกอบออกจากรูปแบบอื่นได้ด้วย" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/cpp/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
