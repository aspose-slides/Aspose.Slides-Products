---
title: ผสาน SVG เป็น PNG ใน C#
url: /th/net/merger/svg-to-png/
keywords: รวม SVG เป็น PNG, SVG เป็น PNG, เข้าร่วม SVG เป็น PNG, รวม SVG เป็น PNG, C# API, .NET Library
description: รวม SVG เป็น PNG ใน C# ใช้ .NET library API เพื่อรวมไฟล์ SVG และ PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="ผสาน SVG เป็น PNG ใน C#" h2=".NET API ข้ามแพลตฟอร์มที่มีประสิทธิภาพสำหรับการรวมภาพ SVG กับ PNG โดยใช้รหัส C# บน NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms" >}}

{{% blocks/products/pf/feature-page-section h2="รวม SVG เป็น PNG โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ .NET**](https://products.aspose.com/slides/th/net/) เป็นไลบรารี .NET ที่มีประสิทธิภาพซึ่งใช้ในการรวมและจัดการงานนำเสนอ รูปภาพ และไฟล์อื่นๆ เมื่อคุณผสาน SVG กับ PNG คุณกำลังรวมรูปภาพ SVG เข้าด้วยกันอย่างมีประสิทธิภาพเพื่อให้ได้รูปภาพ PNG

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="ผสาน SVG เป็น PNG ใน C#" %}}
การใช้ [**Aspose.Slides สำหรับ .NET**](https://products.aspose.com/slides/th/net/) คุณสามารถผสานไฟล์ SVG กับ PNG ได้อย่างรวดเร็วด้วยโค้ดเพียงไม่กี่บรรทัด

{{% blocks/products/pf/agp/code-block title="รหัส C# สำหรับการรวม SVG กับ PNG" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    ISvgImage svgImage = new SvgImage("doc.svg");
    IPPImage image = pres.Images.AddImage(svgImage);
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 360, 540, image);

    ISvgImage svgImage2 = new SvgImage("doc.svg");
    IPPImage image2 = pres.Images.AddImage(svgImage);
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 360, 0, 360, 540, image2);

    pres.Slides[0].GetThumbnail(new Size(960, 720)).Save("MergedFile.png", ImageFormat.Png);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="วิธีผสาน SVG เป็น PNG ใน C#" >}}


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
โหลดไฟล์ SVG ที่คุณต้องการรวมเข้าด้วยกัน
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกภาพ PNG ที่ได้
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="รวมไฟล์ PDF ออนไลน์" sectionDescription="[วิธีผสาน PDF ใน Python](https://products.aspose.com/slides/th/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="รวมไฟล์อื่น ๆ" subTitle="คุณยังสามารถรวมไฟล์ในรูปแบบอื่นเพื่อให้ได้ไฟล์เดียว" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}