---
title: แปลง PPT เป็น Word ใน C++
url: /th/cpp/conversion/ppt-to-word/
keywords: แปลง PPT เป็น Word, PPT เป็น Word, PPT เป็น DOC, PowerPoint เป็น Word, C++ API, C++ Library, CPP
description: แปลง PPT เป็น Word ใน C++ ใช้ API ของไลบรารี C++ เพื่อแปลง PowerPoint เป็น Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง PPT เป็น Word ใน C++" h2="C++ API ข้ามแพลตฟอร์มอันทรงพลังสำหรับการแปลง PowerPoint เป็น Word โดยใช้โค้ด C++ โดยไม่ต้องใช้ Microsoft PowerPoint หรือ Office" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง PowerPoint เป็น Word โดยใช้ Aspose.Slides และ Aspose.Words" %}}

[**Aspose.Slides สำหรับ C+++**](https://products.aspose.com/slides/th/cpp/) และ [**Aspose.Words สำหรับ C*****](https://products.aspose.com/ word/cpp/) เป็นไลบรารี C++ ที่มีประสิทธิภาพซึ่งใช้เพื่อจัดการและแปลงงานนำเสนอ PowerPoint เอกสาร Word และไฟล์อื่นๆ เมื่อคุณแปลง PowerPoint เป็น Word คุณจะย้ายเนื้อหาของสไลด์ของงานนำเสนอไปยังหน้าต่างๆ ในเอกสาร Word

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="แปลง PowerPoint เป็น Word ใน C++" %}}
คุณสามารถแปลง PPT เป็น Word ได้อย่างรวดเร็วด้วยโค้ดเพียงไม่กี่บรรทัด

{{% blocks/products/pf/agp/code-block title="โค้ด C++ สำหรับแปลง PowerPoint เป็น Word" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง PPT เป็น Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง **Aposose.Slides สำหรับ C+** และ **Aposose.Words สำหรับ C+** 
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


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}