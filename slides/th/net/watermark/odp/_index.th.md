---
title: เพิ่มลายน้ำให้กับไฟล์นำเสนอ ODP โดยใช้ .NET
url: /th/net/watermark/odp/
keywords: เพิ่มลายน้ำ ODP, เพิ่มลายน้ำข้อความ ODP, เพิ่มลายน้ำรูปภาพ ODP
description: ซอร์สโค้ด C# สำหรับเพิ่มลายน้ำในงานนำเสนอ ODP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="เพิ่มลายน้ำในงานนำเสนอ ODP โดยใช้ C#" h2="สร้างแอป .NET ของคุณเองเพื่อแทรกลายน้ำข้อความหรือรูปภาพลงในงานนำเสนอ PPT, PPTX หรือ ODP โดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="เพิ่มลายน้ำในงานนำเสนอ ODP ผ่าน C#" %}}
เมื่อใช้ Aspose.Slides for .NET คุณสามารถเพิ่มลายน้ำให้กับงานนำเสนอ ODP ลายน้ำเป็นส่วนสำคัญของงานนำเสนอ ใช้เพื่อป้องกันเนื้อหาของงานนำเสนอจากการคัดลอกหรือนำไปใช้โดยไม่ได้รับอนุญาต ลายน้ำคือรูปภาพหรือข้อความที่มองเห็นหรือมองไม่เห็นที่วางอยู่ด้านบนของงานนำเสนอ สามารถใช้เพื่อระบุเจ้าของงานนำเสนอและเพื่อป้องกันการใช้งานโดยไม่ได้รับอนุญาต ลายน้ำสามารถใช้เพื่อเพิ่มความเป็นมืออาชีพให้กับงานนำเสนอและทำให้ดูสวยงามยิ่งขึ้น 
{{% blocks/products/pf/agp/code-block title="เพิ่มลายน้ำข้อความใน ODP โดยใช้ C#" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);
    ITextFrame watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");

    presentation.Save("watermark.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="เพิ่มลายน้ำรูปภาพในงานนำเสนอ ODP โดยใช้ C#" offSpacer="true" %}}

```cs

using (var presentation = new Presentation())
{
    ISlide slide = presentation.Slides[0];
    IAutoShape watermarkShape = slide.Shapes.AddAutoShape(ShapeType.Triangle, 0, 0, 0, 0);

    IPPImage image = presentation.Images.AddImage(File.ReadAllBytes("watermark.png"));

    watermarkShape.FillFormat.FillType = FillType.Picture;
    watermarkShape.FillFormat.PictureFillFormat.Picture.Image = image;
    watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

    presentation.Save("watermark2.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีเพิ่มลายน้ำใน ODP ผ่าน C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการเพิ่มลายน้ำข้อความในไฟล์ ODP" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด ODP ด้วยอินสแตนซ์ของงานนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เลือกงานนำเสนอหลัก
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มประเภทรูปร่างโดยใช้วิธี AddAutoShape
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มข้อความลายน้ำโดยใช้วิธี AddTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์ในรูปแบบ ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ C# คุณยังสามารถเพิ่มลายน้ำในรูปแบบต่อไปนี้:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}