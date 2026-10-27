---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง PPSM เป็น PNG ผ่าน C#
weight: 6640
url: /th/net/conversion/ppsm-to-png/ 
description: โค้ดตัวอย่างสำหรับการแปลง PPSM เป็น PNG C# ใช้โค้ดตัวอย่าง API สำหรับไฟล์แบตช์ PPSM เป็นการแปลง PNG ภายใน VB.NET, Asp.NET หรือแอปพลิเคชันที่ใช้ .NET
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง PPSM เป็น PNG ผ่าน C#" h2="ส่งออกไฟล์ PowerPoint® PPSM เป็น PNG บน .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="วิธีแปลง PPSM เป็น PNG โดยใช้ C#" %}}

ในการแปลง PPSM เป็น PNG เราจะใช้
 [Aspose.Slides สำหรับ .NET](https://products.aspose.com/slides/th/net)
 API ซึ่งเป็น API ที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่ายสำหรับการจัดการเอกสารและการแปลง API สำหรับแพลตฟอร์ม C# เปิด
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 package manager ค้นหา
 Aspose.สไลด์
 และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="คำสั่งคอนโซลตัวจัดการแพ็คเกจ" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="โค้ดตัวอย่างนี้แสดงการแปลง PPSM เป็น PNG C#" >}}
```cs
using (var presentation = new Presentation("template.ppsm"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in PNG format
        bitmap.Save(string.Format("Slide_{0}.png", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Png);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="ขั้นตอนในการแปลง PPSM เป็น PNG ผ่าน C#" intro="นักพัฒนา .NET สามารถโหลดและแปลงไฟล์ PPSM เป็น PNG ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ PPSM ด้วยอินสแตนซ์ของคลาสการนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ทำซ้ำผ่านแต่ละสไลด์ในการนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างภาพขนาดเต็มเป็นบิตแมปด้วยการวนซ้ำแต่ละครั้ง{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกวิธี Bitmap.Save ด้วยนามสกุลไฟล์ PNG และ ImageFormat.Png เป็นพารามิเตอร์{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="ความต้องการของระบบ" intro="ก่อนเรียกใช้ซอร์สโค้ดตัวอย่างการแปลง .NET ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นต่อไปนี้" %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms
- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio
- Aspose.Slides สำหรับ .NET DLL ที่อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="สร้างด้วย Aspose.Slides" title="แปลง PPSM เป็น PNG ออนไลน์" description="แอป Aspose.Slides Conversion ฟรีนี้สร้างด้วย [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPSM ของคุณเอง" button="เปิด Aspose.Slides Conversion" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" upload="วางหรืออัปโหลดไฟล์ของคุณ" saveAs="บันทึกเป็น" convert="แปลง" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides แปลงไฟล์อย่างไรก่อนที่คุณจะเขียนโค้ด
- อัปโหลดไฟล์ PPSM แล้วบันทึกเป็น PNG
- ดาวน์โหลดผลลัพธ์หรือแปลงไฟล์เพิ่มเติม
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PPSM เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="ภาพบิตแมป" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-html/" name="PPSM TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-jpeg/" name="PPSM TO JPEG" description="ภาพ JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="รูปแบบการนำเสนอ OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="รูปแบบมาตรฐานของ OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="รูปแบบเอกสารพกพา" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-pot/" name="PPSM TO POT" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="ไฟล์เทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="การนำเสนอเทมเพลต Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="สไลด์โชว์ PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="สไลด์โชว์ PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="ไฟล์นำเสนอที่เปิดใช้งานมาโคร" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="เปิดรูปแบบการนำเสนอ XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="รูปแบบ SWF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="ข้อมูลจำเพาะกระดาษ XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
