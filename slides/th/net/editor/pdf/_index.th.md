---
title: แก้ไข PDF ใน C#
url: /th/net/editor/pdf/
keywords: แก้ไข PDF, PDF, C# API, .NET Library
description: แก้ไข PDF ใน C# ใช้ .NET library API เพื่อแก้ไขเอกสาร PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แก้ไข PDF ใน C#" h2=".NET API ข้ามแพลตฟอร์มที่มีประสิทธิภาพสำหรับการแก้ไข PDF โดยใช้รหัส C# บน NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms" >}}

{{% blocks/products/pf/feature-page-section h2="แก้ไข PDF โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ .NET**](https://products.aspose.com/slides/th/net/) เป็นไลบรารี .NET ที่มีประสิทธิภาพซึ่งใช้เพื่อจัดการและแก้ไขงานนำเสนอ เอกสาร PDF และไฟล์อื่นๆ คุณสามารถแก้ไขเอกสาร PDF ได้โดยเพิ่มบรรทัดข้อความใหม่เข้าไป 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="แก้ไข PDF ใน C#" %}}
เมื่อใช้ [**Aspose.Slides สำหรับ .NET**](https://products.aspose.com/slides/th/net/) คุณจะเพิ่มข้อความบรรทัดใหม่ลงในเอกสาร PDF โดยใช้โค้ดเพียงไม่กี่บรรทัดได้

{{% blocks/products/pf/agp/code-block title="รหัส C# สำหรับแก้ไข PDF" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // remove default empty slide
    pres.Slides.AddFromPdf("doc.pdf");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("doc.pdf", SaveFormat.Pdf);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="วิธีแก้ไข PDF ใน C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง **Aposose.Slides สำหรับ .NET** ดู [**การติดตั้ง**](https://docs.aspose.com/slides/net/installation/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
สร้างอินสแตนซ์ของคลาสการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดเอกสาร PDF ที่คุณต้องการแก้ไข
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มบรรทัดใหม่ของข้อความ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกไฟล์ PDF ที่เปลี่ยนแปลง
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="แก้ไขไฟล์อื่นๆ" subTitle="คุณยังสามารถแก้ไขไฟล์ในรูปแบบอื่นๆ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}