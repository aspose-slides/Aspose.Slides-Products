---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลงรูปภาพเป็น PPTX ใน C#
url: /th/net/conversion/image-to-pptx/
keywords: แปลงรูปภาพเป็น PPTX, รูปภาพเป็น PPTX, PowerPoint, รูปภาพ, PPTX, C# API, .NET Library
description: แปลงรูปภาพเป็น PPTX ใน C# ใช้ .NET library API เพื่อแปลงรูปภาพเป็น PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลงรูปภาพเป็น PPTX ใน C#" h2=".NET API ข้ามแพลตฟอร์มอันทรงพลังสำหรับการแปลงอิมเมจเป็น PPTX โดยใช้โค้ด C# บน NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลงรูปภาพเป็น PPTX ใน C#" variant="code" %}}

เมื่อใช้ [**Aspose.Slides สำหรับ .NET**](https://products.aspose.com/slides/th/net/) คุณสามารถแปลงรูปภาพเป็นงานนำเสนอ PowerPoint โดยใช้โค้ดเพียงไม่กี่บรรทัด:

{{< blocks/products/pf/slides-design-update-10-2026/code title="รหัส C# สำหรับแปลงรูปภาพเป็น PPTX" >}}
```cs

using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.pptx", SaveFormat.Pptx);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลงรูปภาพเป็น PPTX โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ .NET**](https://products.aspose.com/slides/th/net/) เป็นไลบรารี .NET ที่มีประสิทธิภาพซึ่งใช้ในการสร้าง แปลง และจัดการงานนำเสนอ PowerPoint, PDF, เอกสาร HTML และไฟล์อื่นๆ เมื่อคุณแปลงรูปภาพเป็น PPTX คุณกำลังสร้างงานนำเสนอ PowerPoint ที่มีสไลด์ตามรูปภาพเหล่านั้น

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแปลงรูปภาพเป็น PPTX ใน C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง **Aposose.Slides สำหรับ .NET** ดู [**การติดตั้ง**](https://docs.aspose.com/slides/net/installation/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างอินสแตนซ์ของคลาสการนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดภาพที่คุณต้องการแปลงเป็น PPTX{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ผลลัพธ์เป็นงานนำเสนอ PPTX{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="ตัวแปลงออนไลน์ฟรี"
  description="[วิธีแปลง PPT เป็น HTML ใน Python](https://products.aspose.com/slides/th/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="การแปลง PowerPoint อื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลงไฟล์ในรูปแบบอื่นเป็น PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
