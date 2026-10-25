---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: เพิ่มลายน้ำในงานนำเสนอ PPT ด้วย C#
url: /th/net/watermark/ppt/
description: เพิ่มลายน้ำข้อความและรูปภาพในงานนำเสนอ PPT ด้วย C# โดยใช้ Aspose.Slides for .NET
keywords: เพิ่มลายน้ำใน PPT, เพิ่มลายน้ำข้อความใน PPT, เพิ่มลายน้ำรูปภาพใน PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="เพิ่มลายน้ำในงานนำเสนอ PPT ด้วย C#" h2="สร้างแอป .NET ที่แทรกลายน้ำข้อความหรือรูปภาพลงในไฟล์งานนำเสนอ" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="เพิ่มลายน้ำในงานนำเสนอ PPT ผ่าน C#" variant="code" %}}

ด้วย [Aspose.Slides for .NET](/slides/th/net/) คุณสามารถเพิ่มลายน้ำข้อความและรูปภาพในงานนำเสนอ PPT ได้ เพิ่มรูปร่างลายน้ำลงในสไลด์ต้นแบบเพื่อให้ลายน้ำปรากฏบนสไลด์ที่ใช้ต้นแบบนั้น

{{< blocks/products/pf/slides-design-update-10-2026/code title="เพิ่มลายน้ำข้อความใน PPT ด้วย C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="เพิ่มลายน้ำรูปภาพในงานนำเสนอ PPT ด้วย C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีเพิ่มลายน้ำใน PPT ด้วย C#" intro="ทำตามขั้นตอนเหล่านี้เพื่อเพิ่มลายน้ำข้อความหรือรูปภาพในไฟล์ PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดไฟล์ `PPT` ด้วยคลาส `Presentation`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เลือกสไลด์ต้นแบบจากคอลเลกชัน `Presentation.Masters`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกเมธอด `AddAutoShape` เพื่อเพิ่มรูปร่างลายน้ำ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เรียกเมธอด `AddTextFrame` เพื่อเพิ่มข้อความลายน้ำ หรือใช้ `AddImage` สำหรับลายน้ำรูปภาพ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ที่มีลายน้ำด้วย `SaveFormat.Ppt`{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="สร้างด้วย Aspose.Slides" title="เพิ่มลายน้ำในไฟล์ PPT ออนไลน์" description="แอป Aspose.Slides Watermark ฟรีนี้สร้างด้วย [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ PPT ของคุณเอง" button="เปิด Aspose.Slides Watermark" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides เพิ่มลายน้ำอย่างไรก่อนเขียนโค้ด
- เพิ่มลายน้ำข้อความหรือรูปภาพในไฟล์ PPT ของคุณ
- ดาวน์โหลดไฟล์ที่มีลายน้ำ
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รูปแบบอื่นที่รองรับลายน้ำ" subTitle="ด้วย C# คุณยังสามารถเพิ่มลายน้ำในรูปแบบต่อไปนี้ได้" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/th/net/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
