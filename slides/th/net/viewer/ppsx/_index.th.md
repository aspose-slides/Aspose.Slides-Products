---
lastmod: 2026-10-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: ดู PPSX ใน C#
keywords: ดู PPSX, เปิด PPSX, โปรแกรมดู PPSX, PPSX, PowerPoint, C# API, ไลบรารี .NET
weight: 2370
url: /th/net/viewer/ppsx/ 
description: ดูไฟล์ PPSX ใน C# ใช้ Aspose.Slides for .NET เพื่อเปิดไฟล์งานนำเสนอและบันทึกเป็น HTML
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="ดู PPSX ใน C#" h2="C# API สำหรับเปิดไฟล์ PPSX และบันทึกเป็น HTML แบบเรสปอนซีฟ"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="ดู PPSX ด้วย Aspose.Slides" %}}

หากต้องการดูไฟล์ PPSX ให้ใช้ [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net/) ซึ่งเป็น API สำหรับ C# ที่ทรงพลัง มีฟีเจอร์ครบ และใช้งานง่าย เปิดตัวจัดการแพ็กเกจ [NuGet](https://www.nuget.org/packages/aspose.slides.net) ค้นหา **Aspose.Slides** แล้วติดตั้ง หรือเรียกใช้คำสั่งต่อไปนี้ใน Package Manager Console

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="คำสั่ง Package Manager Console" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

ด้วย [**Aspose.Slides for .NET**](/slides/th/net/) คุณสามารถโหลดไฟล์ PPSX และบันทึกเป็น HTML แบบเรสปอนซีฟได้ด้วยโค้ดเพียงไม่กี่บรรทัด

{{< blocks/products/pf/slides-design-update-10-2026/code title="โค้ด C# สำหรับดู PPSX" >}}
```cs
using var presentation = new Presentation("presentation.ppsx");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีดู PPSX ใน C#" intro="Aspose.Slides ช่วยให้นักพัฒนาดูไฟล์ PPSX ได้ด้วยโค้ดเพียงไม่กี่บรรทัด" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง **Aspose.Slides for .NET** ดู [**การติดตั้ง**](https://docs.aspose.com/slides/net/installation/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มไลบรารีเป็นการอ้างอิงในโปรเจกต์ของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ `PPSX` ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างออบเจ็กต์ `ResponsiveHtmlController` สำหรับเอาต์พุต HTML แบบเรสปอนซีฟ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างออบเจ็กต์ `HtmlOptions` และตั้งค่าพร็อพเพอร์ตี `HtmlFormatter`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ PPSX เป็น HTML ด้วย `SaveFormat.Html`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="ความต้องการของระบบ" intro="Aspose.Slides for .NET รองรับระบบปฏิบัติการหลักทั้งหมด ตรวจสอบให้แน่ใจว่าคุณมีสิ่งที่จำเป็นต่อไปนี้" %}}

- Microsoft Windows หรือระบบปฏิบัติการที่รองรับ .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin
- สภาพแวดล้อมการพัฒนา เช่น Microsoft Visual Studio
- การอ้างอิง Aspose.Slides for .NET ในโปรเจกต์ของคุณ

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="สร้างด้วย Aspose.Slides" title="ดูไฟล์ PPSX ออนไลน์" description="แอป Aspose.Slides Viewer ฟรีนี้สร้างด้วย [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPSX ของคุณเอง" button="เปิด Aspose.Slides Viewer" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides แสดงผลไฟล์ของคุณอย่างไรก่อนเขียนโค้ด
- อัปโหลดไฟล์ PPSX แล้วดูสไลด์ได้ทันที
- ใช้งานได้ทั้งบนเดสก์ท็อปและมือถือ โดยไม่ต้องใช้ PowerPoint
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" %}}

PPSX, Power Point Slide Show, file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. It is an update to the PPS file format that was supported by Microsoft PowerPoint 97-2003 versions. When a PPSX file is shared with another user and opened, it starts as PowerPoint show unlike PPTX file that opens in editable mode. The sequence of slide show is the same as in the original presentation. All the slides accompany the images, sounds and other embedded media accompany the presentation slides to the PPSX during the slideshow.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="ดูไฟล์อื่น" subTitle="คุณยังสามารถเปิดและดูงานนำเสนอในรูปแบบอื่นได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/viewer/odp/" name="ODP" description="งานนำเสนอ OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/viewer/otp/" name="OTP" description="เทมเพลตงานนำเสนอ OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/viewer/pot/" name="POT" description="เทมเพลต PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/viewer/potm/" name="POTM" description="เทมเพลต PowerPoint ที่เปิดใช้งานแมโคร" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/viewer/potx/" name="POTX" description="เทมเพลต PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/viewer/pps/" name="PPS" description="สไลด์โชว์ PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/viewer/ppsm/" name="PPSM" description="สไลด์โชว์ PowerPoint ที่เปิดใช้งานแมโคร" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/viewer/ppt/" name="PPT" description="งานนำเสนอ PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/viewer/pptm/" name="PPTM" description="งานนำเสนอ PowerPoint ที่เปิดใช้งานแมโคร" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/viewer/pptx/" name="PPTX" description="งานนำเสนอ PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
