---
title: ป้องกันไฟล์นำเสนอ PPT โดยใช้ C++
url: /th/cpp/protect/ppt/
keywords: การป้องกันการเขียน PPT, การเข้ารหัส PPT, ล็อคการนำเสนอ PPT, ป้องกัน PPT
description: ซอร์สโค้ด C++ เพื่อป้องกันการนำเสนอ PPT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ล็อคหรือป้องกันรหัสผ่าน PPT โดยใช้ C++" h2="สร้างแอป C++ ของคุณเองเพื่อปกป้องไฟล์งานนำเสนอโดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="การป้องกันการนำเสนอ PPT ผ่าน C++" %}}
เมื่อใช้ Aspose.Slides for C++ คุณสามารถป้องกันงานนำเสนอ PPT จากการเปิดหรือแก้ไขโดยตั้งรหัสผ่าน จากนั้น ในการเปิดหรือแก้ไขงานนำเสนอที่ถูกล็อค ผู้ใช้จะต้องระบุรหัสผ่าน
{{% blocks/products/pf/agp/code-block title="การเข้ารหัสงานนำเสนอ PPT โดยใช้ C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.ppt");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="การตั้งค่าการป้องกันการเขียนให้กับงานนำเสนอ PPT โดยใช้ C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.ppt");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีป้องกันรหัสผ่าน PPT ผ่าน C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการป้องกันไฟล์ PPT" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด PPT ด้วยอินสแตนซ์ของงานนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ป้องกันงานนำเสนอโดยใช้คลาส ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์ในรูปแบบ PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการป้องกันอื่น ๆ ที่รองรับ" subTitle="เมื่อใช้ C++ คุณยังสามารถป้องกันรูปแบบต่อไปนี้:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}