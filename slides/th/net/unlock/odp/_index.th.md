---
title: ปลดล็อกไฟล์การนำเสนอ ODP โดยใช้ .NET
url: /th/net/unlock/odp/
keywords: ลบการป้องกันการเขียน ODP, ถอดรหัส ODP, ปลดล็อกการนำเสนอ ODP, เลิกป้องกัน ODP
description: ซอร์สโค้ด C# เพื่อลบการป้องกันจากการนำเสนอ ODP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ปลดล็อก ODP โดยใช้ C#" h2="สร้างแอป .NET ของคุณเองเพื่อลบรหัสผ่านออกจาก PowerPoint และถอดรหัสไฟล์งานนำเสนอโดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="การลบการเข้ารหัสออกจากงานนำเสนอ ODP ผ่าน C#" %}}
เมื่อใช้ Aspose.Slides for .NET คุณสามารถลบการเข้ารหัสหรือการป้องกันด้วยรหัสผ่านในการนำเสนอ ODP ด้วยวิธีนี้ ผู้ใช้จะสามารถเข้าถึงหรือแก้ไขงานนำเสนอ ODP โดยไม่มีข้อจำกัด
{{% blocks/products/pf/agp/code-block title="ปิดใช้งานการป้องกันด้วยรหัสผ่านจาก ODP โดยใช้ C#" offSpacer="true" %}}

```cs

LoadOptions loadOptions = new LoadOptions {Password = "123123"};
using (Presentation presentation = new Presentation("pres.odp", loadOptions))
{
    presentation.ProtectionManager.RemoveEncryption();
    presentation.Save("encryption-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="การนำการป้องกันการเขียนออกจากงานนำเสนอ ODP โดยใช้ C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีลบรหัสผ่านจาก ODP ผ่าน C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการนำการป้องกันออกจากไฟล์ ODP" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด ODP ด้วยอินสแตนซ์ของงานนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ลบการป้องกันการเขียนโดยใช้คลาส ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์ในรูปแบบ ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ C# คุณยังสามารถลบการป้องกันจากรูปแบบต่อไปนี้:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}