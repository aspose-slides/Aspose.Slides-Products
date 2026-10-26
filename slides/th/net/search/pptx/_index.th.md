---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ค้นหาข้อความในไฟล์งานนำเสนอ PPTX ด้วย .NET
url: /th/net/search/pptx/
description: ซอร์สโค้ด C# สำหรับค้นหาข้อความในงานนำเสนอ PPTX
keywords: ค้นหาข้อความใน PPTX, หาข้อความใน PPTX, ค้นหาข้อความในงานนำเสนอ PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ค้นหาข้อความในไฟล์ PPTX ด้วย C#" h2="สร้างแอป .NET ที่ค้นหาข้อความในงานนำเสนอด้วย API ฝั่งเซิร์ฟเวอร์" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ค้นหาข้อความในงานนำเสนอ PPTX ด้วย C#" variant="code" %}}

ด้วย [Aspose.Slides for .NET](/slides/th/net/) คุณสามารถค้นหาข้อความในงานนำเสนอ PPTX ได้ ดึงกรอบข้อความของสไลด์ด้วย `SlideUtil.GetAllTextBoxes` แล้วตรวจสอบค่า `Text` เพื่อหาวลีที่ต้องการ

{{< blocks/products/pf/slides-design-update-10-2026/code title="ค้นหาข้อความในงานนำเสนอ PPTX ด้วย C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var slideIndex = 0;
var slide = presentation.Slides[slideIndex];
var textFrames = Aspose.Slides.Util.SlideUtil.GetAllTextBoxes(slide);

foreach (var textFrame in textFrames)
{
    var text = textFrame.Text;
    if (text.Contains("PowerPoint", System.StringComparison.OrdinalIgnoreCase))
    {
        Console.WriteLine(text);
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีค้นหาข้อความในงานนำเสนอ PPTX ด้วย C#" intro="ทำตามขั้นตอนต่อไปนี้เพื่อค้นหาข้อความในงานนำเสนอ PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPTX ด้วย `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ดึงสไลด์ที่ต้องการจาก `Presentation.Slides` และกำหนดให้กับตัวแปร{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ดึงกรอบข้อความของสไลด์ด้วย [`SlideUtil.GetAllTextBoxes`](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/getalltextboxes/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ตรวจสอบว่าค่า `Text` ของแต่ละกรอบมีวลีที่ต้องการหรือไม่{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="สร้างด้วย Aspose.Slides" title="ค้นหาข้อความในไฟล์ PPTX ออนไลน์" description="แอป Aspose.Slides Search ฟรีนี้สร้างด้วย [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPTX ของคุณเอง" button="เปิด Aspose.Slides Search" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides ค้นหาข้อความอย่างไรก่อนเขียนโค้ด
- ค้นหาข้อความธรรมดาหรือนิพจน์ทั่วไปในไฟล์ PPTX ของคุณ
- ดาวน์โหลดผลการค้นหาเป็นไฟล์ข้อความ
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการค้นหา" subTitle="ด้วย C# คุณยังสามารถค้นหาข้อความในรูปแบบต่อไปนี้ได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
