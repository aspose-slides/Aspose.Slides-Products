---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: ลบคำอธิบายประกอบ ODP ด้วย .NET
url: /th/net/annotation/odp/ 
description: ลบความคิดเห็นและผู้เขียนความคิดเห็นออกจากงานนำเสนอ ODP ใน C#
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ลบความคิดเห็นและผู้เขียนความคิดเห็นออกจาก ODP ใน C#" h2="สร้างแอปพลิเคชัน .NET ที่จัดการความคิดเห็นและผู้เขียนในไฟล์งานนำเสนอด้วย API ฝั่งเซิร์ฟเวอร์" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ลบความคิดเห็นออกจาก ODP ผ่าน C#" variant="code" %}}

ใช้ [Aspose.Slides for .NET](/slides/th/net/) เพื่อลบความคิดเห็นและผู้เขียนความคิดเห็นออกจากไฟล์งานนำเสนอ ODP ตัวอย่างด้านล่างจะล้างคอลเลกชัน `Comments` ของผู้เขียนแต่ละคน แล้วล้างคอลเลกชัน `CommentAuthors` ของงานนำเสนอ

{{< blocks/products/pf/slides-design-update-10-2026/code title="ลบคำอธิบายประกอบออกจาก ODP – C#" >}}
```cs
using var presentation = new Presentation("example.odp");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีลบความคิดเห็นออกจาก ODP ผ่าน C#" intro="ทำตามขั้นตอนเหล่านี้เพื่อลบความคิดเห็นและผู้เขียนความคิดเห็นออกจากงานนำเสนอ ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง Aspose.Slides for .NET ดู [การติดตั้ง](https://docs.aspose.com/slides/net/installation/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ ODP ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนซ้ำคอลเลกชัน `CommentAuthors`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ล้างคอลเลกชัน `Comments` ของผู้เขียนความคิดเห็นแต่ละคน{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ล้างคอลเลกชัน `CommentAuthors`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกงานนำเสนอที่อัปเดตแล้วด้วย `SaveFormat.Odp`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="สร้างด้วย Aspose.Slides" title="ลบความคิดเห็น ODP ออนไลน์" description="แอป Aspose.Slides Annotation ฟรีนี้สร้างด้วย [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ ODP ของคุณเอง" button="เปิด Aspose.Slides Annotation" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ลบความคิดเห็นอย่างไรก่อนเขียนโค้ด
- ลบความคิดเห็นทั้งหมดออกจากไฟล์ ODP ของคุณ
- ดาวน์โหลดไฟล์ที่ล้างแล้ว
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับสำหรับคำอธิบายประกอบ" subTitle="ด้วย C# คุณยังลบคำอธิบายประกอบออกจากรูปแบบอื่นได้ด้วย" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
