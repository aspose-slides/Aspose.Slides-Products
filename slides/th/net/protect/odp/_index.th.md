---
title: ป้องกันไฟล์นำเสนอ ODP โดยใช้ .NET
url: /th/net/protect/odp/
keywords: การป้องกันการเขียน ODP, การเข้ารหัส ODP, ล็อคการนำเสนอ ODP, ป้องกัน ODP
description: ซอร์สโค้ด C# เพื่อป้องกันการนำเสนอ ODP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ล็อคหรือป้องกันรหัสผ่าน ODP โดยใช้ C#" h2="สร้างแอป .NET ของคุณเองเพื่อปกป้องไฟล์งานนำเสนอโดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="การป้องกันการนำเสนอ ODP ผ่าน C#" %}}
เมื่อใช้ Aspose.Slides for .NET คุณสามารถป้องกันงานนำเสนอ ODP จากการเปิดหรือแก้ไขโดยตั้งรหัสผ่าน จากนั้น ในการเปิดหรือแก้ไขงานนำเสนอที่ถูกล็อค ผู้ใช้จะต้องระบุรหัสผ่าน
{{% blocks/products/pf/agp/code-block title="การเข้ารหัสงานนำเสนอ ODP โดยใช้ C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="การตั้งค่าการป้องกันการเขียนให้กับงานนำเสนอ ODP โดยใช้ C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีป้องกันรหัสผ่าน ODP ผ่าน C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการป้องกันไฟล์ ODP" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด ODP ด้วยอินสแตนซ์ของงานนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ป้องกันงานนำเสนอโดยใช้คลาส ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์ในรูปแบบ ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการป้องกันอื่น ๆ ที่รองรับ" subTitle="เมื่อใช้ C# คุณยังสามารถป้องกันรูปแบบต่อไปนี้:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}