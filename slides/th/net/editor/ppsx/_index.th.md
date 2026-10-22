---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แก้ไขไฟล์ PPSX ผ่าน .NET
url: /th/net/editor/ppsx/ 
description: ซอร์สโค้ด C# เพื่อแก้ไขเอกสาร PPSX บน .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แก้ไขรูปแบบ PPSX ใน C#" h2="การแก้ไขเอกสาร PPSX ดั้งเดิมและประสิทธิภาพสูงโดยใช้ Aspose.Slides ฝั่งเซิร์ฟเวอร์สำหรับ .NET API โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Adobe PDF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="วิธีแก้ไขไฟล์ PPSX โดยใช้ C#" %}}

ในการแก้ไขไฟล์ PPSX เราจะใช้ <a href="https://products.aspose.com/slides/th/net">Aspose.Slides for .NET</a> API ซึ่งเป็นคุณลักษณะที่มีประสิทธิภาพและทรงพลัง และ API ที่ใช้งานง่ายสำหรับแพลตฟอร์ม C# สำหรับตัวแก้ไขใดๆ เปิด <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a> package manager ค้นหา <b>Aspose.Slides</b> และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="สั่งการ" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="แก้ไขไฟล์ PPSX - C#" >}}
```cs
using var presentation = new Presentation("document.ppsx");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.ppsx", SaveFormat.Ppsx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="ขั้นตอนในการแก้ไขไฟล์ PPSX ใน C#" intro="การแก้ไขเอกสารเบื้องต้นด้วย [Aspose.Slides สำหรับ .NET](https://products.aspose.com/slides/th/net) API สามารถทำได้โดยใช้โค้ดเพียงไม่กี่บรรทัด" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPSX ด้วยออบเจ็กต์ `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เข้าถึงสไลด์และรูปร่างเป้าหมายผ่านตัวแปร{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}อัปเดตข้อความผ่าน `TextFrame`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกงานนำเสนอที่แก้ไขแล้วด้วย `SaveFormat.Ppsx`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="ความต้องการของระบบ" intro="API ของเราได้รับการสนับสนุนบนแพลตฟอร์มหลักและระบบปฏิบัติการทั้งหมด ก่อนดำเนินการโค้ดด้านล่าง โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นต่อไปนี้ในระบบของคุณ" %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms
- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio
- Aspose.Slides สำหรับ .NET DLL ที่อ้างอิงในโครงการของคุณ - ติดตั้งจาก NuGet โดยใช้ปุ่มดาวน์โหลดด้านบน

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" %}}

PPSX, Power Point Slide Show, file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. It is an update to the PPS file format that was supported by Microsoft PowerPoint 97-2003 versions. When a PPSX file is shared with another user and opened, it starts as PowerPoint show unlike PPTX file that opens in editable mode. The sequence of slide show is the same as in the original presentation. All the slides accompany the images, sounds and other embedded media accompany the presentation slides to the PPSX during the slideshow.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
