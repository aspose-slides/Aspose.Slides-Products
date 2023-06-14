---
title: เพิ่มลายน้ำให้กับไฟล์นำเสนอ PPTX โดยใช้ C++
url: /th/cpp/watermark/pptx/
keywords: เพิ่มลายน้ำ PPTX, เพิ่มลายน้ำข้อความ PPTX, เพิ่มลายน้ำรูปภาพ PPTX
description: ซอร์สโค้ด C++ สำหรับเพิ่มลายน้ำในงานนำเสนอ PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="เพิ่มลายน้ำในงานนำเสนอ PPTX โดยใช้ C++" h2="สร้างแอป C++ ของคุณเองเพื่อแทรกลายน้ำข้อความหรือรูปภาพลงในงานนำเสนอ PPT, PPTX หรือ ODP โดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="เพิ่มลายน้ำในงานนำเสนอ PPTX ผ่าน C++" %}}
เมื่อใช้ Aspose.Slides for C++ คุณสามารถเพิ่มลายน้ำให้กับงานนำเสนอ PPTX ลายน้ำเป็นส่วนสำคัญของงานนำเสนอ ใช้เพื่อป้องกันเนื้อหาของงานนำเสนอจากการคัดลอกหรือนำไปใช้โดยไม่ได้รับอนุญาต ลายน้ำคือรูปภาพหรือข้อความที่มองเห็นหรือมองไม่เห็นที่วางอยู่ด้านบนของงานนำเสนอ สามารถใช้เพื่อระบุเจ้าของงานนำเสนอและเพื่อป้องกันการใช้งานโดยไม่ได้รับอนุญาต ลายน้ำสามารถใช้เพื่อเพิ่มความเป็นมืออาชีพให้กับงานนำเสนอและทำให้ดูสวยงามยิ่งขึ้น 
{{% blocks/products/pf/agp/code-block title="เพิ่มลายน้ำข้อความใน PPTX โดยใช้ C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermark.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="เพิ่มลายน้ำรูปภาพในงานนำเสนอ PPTX โดยใช้ C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto image = presentation->get_Images()->AddImage(:File::ReadAllBytes(u"watermark.png"));

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(image);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"watermark2.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีเพิ่มลายน้ำใน PPTX ผ่าน C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการเพิ่มลายน้ำข้อความในไฟล์ PPTX" >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลด PPTX ด้วยอินสแตนซ์ของงานนำเสนอ
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
บันทึกผลลัพธ์ในรูปแบบ PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ C++ คุณยังสามารถเพิ่มลายน้ำในรูปแบบต่อไปนี้:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}