---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 70
title: แยกข้อความจากไฟล์ PPT ด้วย .NET
url: /th/net/parser/ppt/ 
description: ซอร์สโค้ด C# สำหรับแยกข้อความจากไฟล์ PPT ด้วย .NET
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แยกวิเคราะห์ไฟล์ PPT ด้วย C#" h2="แยกข้อความและตรวจสอบการจัดรูปแบบข้อความในไฟล์ PPT ด้วย .NET API ฝั่งเซิร์ฟเวอร์"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แยกวิเคราะห์ไฟล์ PPT ด้วย C#" %}}

ใช้ [Aspose.Slides for .NET](/slides/th/net/) เพื่อแยกข้อความจากงานนำเสนอ PPT ติดตั้งแพ็กเกจจาก [NuGet](https://www.nuget.org/packages/aspose.slides.net) หรือเรียกใช้คำสั่งต่อไปนี้ใน Package Manager Console

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="คำสั่ง" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="แยกวิเคราะห์ไฟล์ PPT – C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแยกวิเคราะห์ไฟล์ PPT ใน C#" intro="การแยกวิเคราะห์เอกสารขั้นพื้นฐานด้วย API [Aspose.Slides for .NET](/slides/th/net/) ใช้โค้ดเพียงไม่กี่บรรทัด" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPT ด้วย `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ดึงกรอบข้อความด้วย `SlideUtil.GetAllTextFrames`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}วนผ่านกรอบข้อความ ย่อหน้า และส่วนข้อความ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}อ่านพร็อพเพอร์ตี `Text`, `FontHeight` และ `LatinFont.FontName` ตามต้องการ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="ความต้องการของระบบ" intro="ต้องมีรันไทม์ .NET ที่รองรับและการอ้างอิงแพ็กเกจ Aspose.Slides for .NET คุณสามารถใช้ Visual Studio หรือสภาพแวดล้อมการพัฒนา C# อื่นที่เข้ากันได้" %}}

- สภาพแวดล้อมที่เข้ากันได้กับ .NET Framework, .NET, Mono หรือ Xamarin
- สภาพแวดล้อมการพัฒนา C# เช่น Visual Studio
- Aspose.Slides for .NET ที่ติดตั้งจาก NuGet

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="สร้างด้วย Aspose.Slides" title="แยกข้อความและรูปภาพออนไลน์" description="แอป Aspose.Slides Parser ฟรีนี้สร้างด้วย [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPT ของคุณเอง" button="เปิด Aspose.Slides Parser" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides อ่านไฟล์ของคุณอย่างไรก่อนเขียนโค้ด
- อัปโหลดไฟล์ PPT แล้วรับข้อความและรูปภาพ
- ดาวน์โหลดทั้งหมดเป็นไฟล์ ZIP เดียว
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

ไฟล์ PPT คืองานนำเสนอ Microsoft PowerPoint 97-2003 ในรูปแบบไฟล์ไบนารี ประกอบด้วยสไลด์ที่มีข้อความ รายการสัญลักษณ์หัวข้อย่อย รูปภาพ มัลติมีเดีย และวัตถุ OLE ที่ฝังไว้ PowerPoint เวอร์ชันใหม่กว่าใช้รูปแบบ PPTX ซึ่งอิงตาม Office Open XML แอปพลิเคชันอย่าง OpenOffice Impress และ Apple Keynote ก็สร้างไฟล์ PPT ได้เช่นกัน

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับการแยกวิเคราะห์" subTitle="ด้วย C# คุณยังสามารถแยกวิเคราะห์รูปแบบต่อไปนี้ได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/parser/odp/" name="ODP" description="งานนำเสนอ OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/parser/pptx/" name="PPTX" description="งานนำเสนอ PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
