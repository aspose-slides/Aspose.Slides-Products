---
title: รวมรูปภาพเป็น BMP ใน C++
url: /th/cpp/merger/image-to-bmp/
keywords: รูปภาพเป็น BMP, รวมรูปภาพเป็น BMP, รวมรูปภาพเป็น BMP, รวมรูปภาพ, รูปภาพ, BMP, C++ API, ไลบรารี C++
description: รวมรูปภาพเป็น BMP ใน C++ ใช้ API ของไลบรารี C++ เพื่อรวมรูปภาพ
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="รวมรูปภาพเป็น BMP ใน C++" h2="ไลบรารี C++ ความเร็วสูงและข้ามแพลตฟอร์มสำหรับการผสานอิมเมจกับไฟล์ BMP โดยใช้โค้ด C++" >}}

{{% blocks/products/pf/feature-page-section h2="รวมรูปภาพเป็น BMP โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ C++++](https://products.aspose.com/slides/th/cpp/) เป็นไลบรารี C++ อันทรงพลังที่ใช้สร้าง แปลง ผสาน และจัดการงานนำเสนอ PDF รูปภาพ และอื่นๆ ไฟล์. เมื่อคุณรวมรูปภาพเข้ากับ BMP คุณกำลังรวมรูปภาพอย่างมีประสิทธิภาพเพื่อให้ได้ไฟล์ BMP ไฟล์เดียว

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="รวมรูปภาพเป็น BMP ใน C++" %}}
เมื่อใช้ [**Aspose.Slides สำหรับ C+**](https://products.aspose.com/slides/th/cpp/) คุณสามารถผสานรูปภาพเข้ากับ BMP ได้อย่างรวดเร็วด้วยโค้ดเพียงไม่กี่บรรทัด

{{% blocks/products/pf/agp/code-block title="รหัส C++ สำหรับการรวมรูปภาพเป็น BMP" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();
        
auto image1 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image1.png"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 100.0f, 100.0f, image1);
auto image2 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image2.png"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 200.0f, 100.0f, 100.0f, image2);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.bmp", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Bmp());
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="วิธีรวมรูปภาพเป็น BMP ใน C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง ** Aspose.Slides สำหรับ C++++ ดู [**การติดตั้ง**](https://docs.aspose.com/slides/cpp/installation/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
สร้างอินสแตนซ์ของคลาสการนำเสนอ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
โหลดรูปภาพที่คุณต้องการรวมเข้าด้วยกันเป็นกรอบรูป
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกไฟล์ BMP ที่ได้
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="รวมไฟล์ PDF ออนไลน์" sectionDescription="[วิธีผสาน PDF ใน Python](https://products.aspose.com/slides/th/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="รวมไฟล์อื่น ๆ" subTitle="คุณยังสามารถรวมไฟล์ในรูปแบบอื่นเพื่อให้ได้ไฟล์เดียว" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}