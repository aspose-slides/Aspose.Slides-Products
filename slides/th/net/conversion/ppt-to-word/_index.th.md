---
title: แปลง PPT เป็น Word ใน C#
url: /th/net/conversion/ppt-to-word/
keywords: แปลง PPT เป็น Word, PPT เป็น Word, PPT เป็น DOC, PowerPoint เป็น Word, C# API, .NET Library
description: แปลง PPT เป็น Word ใน C# ใช้ .NET library API เพื่อแปลง PowerPoint เป็น Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง PPT เป็น Word ใน C#" h2=".NET API ข้ามแพลตฟอร์มที่มีประสิทธิภาพสำหรับการแปลง PowerPoint เป็น Word โดยใช้โค้ด C# บน NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง PowerPoint เป็น Word โดยใช้ Aspose.Slides และ Aspose.Words" %}}

[**Aspose.Slides สำหรับ .NET**](https://products.aspose.com/slides/th/net/) และ [**Aspose.Words สำหรับ .NET**](https://products.aspose com/words/net/) เป็นไลบรารี .NET ที่มีประสิทธิภาพซึ่งใช้เพื่อจัดการและแปลงงานนำเสนอ PowerPoint เอกสาร Word และไฟล์อื่นๆ เมื่อคุณแปลง PowerPoint เป็น Word คุณจะย้ายเนื้อหาของสไลด์ของงานนำเสนอไปยังหน้าต่างๆ ในเอกสาร Word

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="แปลง PowerPoint เป็น Word ใน C#" %}}
คุณสามารถแปลง PPT เป็น Word ได้อย่างรวดเร็วด้วยโค้ดเพียงไม่กี่บรรทัด

{{% blocks/products/pf/agp/code-block title="รหัส C# สำหรับแปลง PowerPoint เป็น Word" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
var doc = new Document();
var builder = new DocumentBuilder(doc);
foreach (var slide in presentation.Slides)
{
    // generates and inserts slide image
    using var bitmap = slide.GetThumbnail(1, 1);
    using var stream = new MemoryStream();
    bitmap.Save(stream, ImageFormat.Png);
    stream.Seek(0, SeekOrigin.Begin);
    using var skBitmap = SKBitmap.Decode(stream);
    builder.InsertImage(skBitmap);

    // inserts slide texts
    foreach (var shape in slide.Shapes)
    {
        if (shape is AutoShape autoShape)
        {
            builder.Writeln(autoShape.TextFrame.Text);
        }
    }

    builder.InsertBreak(BreakType.PageBreak);
}
doc.Save("document.docx");
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง PPT เป็น Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง **Aposose.Slides สำหรับ .NET** และ **Aspose.Words สำหรับ .NET** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มสองไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
สร้างอินสแตนซ์ของคลาสงานนำเสนอและคลาสเอกสาร
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดงานนำเสนอ PPT ที่คุณต้องการแปลงเป็น Word
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
สร้างรูปภาพและข้อความตามเนื้อหาของสไลด์
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกเอกสาร Word ที่ได้
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="ตัวแปลงออนไลน์ฟรี" sectionDescription="[วิธีแปลง PPT เป็น HTML ใน Python](https://products.aspose.com/slides/th/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง PowerPoint เป็นไฟล์ในรูปแบบอื่นๆ" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}