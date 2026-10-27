---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: รวมรูปภาพเป็น PDF ใน C#
url: /th/net/merger/image-to-pdf/
keywords: รูปภาพเป็น PDF, รวมรูปภาพเป็น PDF, รวมรูปภาพเป็น PDF, PDF, รูปภาพ, C# API, .NET Library
description: รวมรูปภาพเป็น PDF ใน C# ใช้ .NET library API เพื่อรวม Image และ PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="รวมรูปภาพเป็น PDF ใน C#" h2=".NET API ข้ามแพลตฟอร์มอันทรงพลังสำหรับการรวมไฟล์ Image กับ PDF โดยใช้โค้ด C# บน NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms" related="JPG,PNG,HTML,IMAGE,PDF" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="รวมรูปภาพเป็น PDF ใน C#" variant="code" %}}

เมื่อใช้ [**Aspose.Slides สำหรับ .NET**](https://products.aspose.com/slides/th/net/) คุณสามารถผสานรูปภาพเป็น PDF ได้อย่างรวดเร็วด้วยโค้ดเพียงไม่กี่บรรทัด

{{< blocks/products/pf/slides-design-update-10-2026/code title="รหัส C# สำหรับการรวมรูปภาพเป็น PDF" >}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image1.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image);

    IPPImage image2 = pres.Images.AddImage(File.ReadAllBytes("image2.png"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    pres.Save("MergedFile.pdf", SaveFormat.Pdf);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="รวมรูปภาพเป็น PDF โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ .NET**](https://products.aspose.com/slides/th/net/) เป็นไลบรารี่ .NET อันทรงพลังที่ใช้สร้าง แปลง ผสาน และจัดการงานนำเสนอ PDF รูปภาพ และไฟล์อื่นๆ เมื่อคุณรวมรูปภาพเป็น PDF คุณกำลังรวมรูปภาพอย่างมีประสิทธิภาพเพื่อให้ได้ไฟล์ PDF ไฟล์เดียว

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีรวมรูปภาพเป็น PDF ใน C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง **Aposose.Slides สำหรับ .NET** ดู [**การติดตั้ง**](https://docs.aspose.com/slides/net/installation/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างอินสแตนซ์ของคลาสการนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดรูปภาพที่คุณต้องการรวมเข้าด้วยกันเป็นกรอบรูป{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึก PDF ที่เป็นผลลัพธ์{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="สร้างด้วย Aspose.Slides" title="รวม รูปภาพ เป็น PDF ออนไลน์" description="แอป Aspose.Slides Merger ฟรีนี้สร้างด้วย [Aspose.Slides for .NET](https://products.aspose.com/slides/th/net/) ซึ่งเป็น API เดียวกับโค้ดด้านบน เปิดแอปแล้วดูว่า API ทำอะไรได้บ้างกับไฟล์ รูปภาพ ของคุณเอง" button="เปิด Aspose.Slides Merger" note="[แอปฟรีทั้งหมด](https://products.aspose.app/slides/family)" >}}
- ทำงานในเบราว์เซอร์ ไม่ต้องติดตั้งสิ่งใด
- ดูว่า Aspose.Slides รวมไฟล์อย่างไรก่อนที่คุณจะเขียนโค้ด
- อัปโหลดไฟล์ รูปภาพ หลายไฟล์แล้วรวมเป็นไฟล์ PDF ไฟล์เดียว
- ดาวน์โหลดผลลัพธ์ที่รวมแล้วเป็นไฟล์เดียว
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="รวมไฟล์อื่น ๆ" subTitle="คุณยังสามารถรวมไฟล์ในรูปแบบอื่นเพื่อให้ได้ไฟล์เดียว" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/merger/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
