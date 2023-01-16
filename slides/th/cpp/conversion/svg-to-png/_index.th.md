---
title: แปลง SVG เป็น PNG ใน C++
url: /th/cpp/conversion/svg-to-png/
keywords: SVG เป็น PNG, แปลง SVG เป็น PNG, C++ API, C++ Library, SVG, PNG
description: แปลง SVG เป็น PNG ใน C++ ใช้ C++ library API เพื่อแปลงไฟล์ SVG เป็น PNGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง SVG เป็น PNG ใน C++" h2="ไลบรารี C++ ความเร็วสูงและข้ามแพลตฟอร์มที่ช่วยในการพัฒนาแอปพลิเคชันด้วยความสามารถในการสร้าง รวม ตรวจสอบ หรือแปลงไฟล์งานนำเสนอ Microsoft PowerPoint และ OpenOffice โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Open Office, Adobe PDF" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง SVG เป็น PNG ใน C++" %}}

[**Aspose.Slides สำหรับ C++++](https://products.aspose.com/slides/th/cpp/) เป็นไลบรารี C++ ที่ทรงพลังสำหรับการสร้างและจัดการไฟล์งานนำเสนอ นอกจากนี้ ยังมีวิธีที่ยืดหยุ่นในการแปลง SVG เป็น PNG เมื่อใช้ **Aspose.Slides สำหรับ C+++** นักพัฒนาหรือแอปพลิเคชันใดๆ ก็สามารถแปลงไฟล์ SVG เป็น PNG ด้วยโค้ด C++ เพียงไม่กี่บรรทัด

ในฐานะ API การประมวลผลเอกสารสมัยใหม่ Aspose.Slides สำหรับ C++ จะส่งออกไฟล์ SVG เป็นรูปแบบไฟล์ PNG ได้อย่างรวดเร็ว ไลบรารี Aspose PowerPoint ช่วยให้คุณแปลง SVG เป็น PNG และรูปแบบไฟล์อื่นๆ อีกมากมาย

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลง SVG เป็น PNG โดยใช้ C++" %}}
หากต้องการแปลง SVG เป็น PNG คุณจะต้องสร้างงานนำเสนอจากไฟล์ SVG และบันทึกเป็น PNG

{{% blocks/products/pf/agp/code-block title="โค้ด C++ สำหรับแปลง SVG เป็น PNG" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
System::String svgContent = System::IO::File::ReadAllText(svgPath);
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(svgContent);
System::SharedPtr<IPPImage> ppImage = pres->get_Images()->AddImage(svgImage);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(Aspose::Slides::ShapeType::Rectangle, 0.0f, 0.0f, 
    static_cast<float>(ppImage->get_Width()), 
    static_cast<float>(ppImage->get_Height()), ppImage);
for (int32_t i = 0; i < pres->get_Slides()->get_Count(); i++)
{
    // Control hidden slides (do not render hidden slides)
    if (pres->get_Slides()->idx_get(i)->get_Hidden())
    {
        continue;
    }
    
    // Convert slide to a Bitmap object
    System::SharedPtr<Bitmap> bmp = pres->get_Slides()->idx_get(i)->GetThumbnail(2.f, 2.f);

    // Create file name for an image
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".png");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Png());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง SVG เป็น PNG โดยใช้ Aspose.Slides สำหรับ C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการแปลง SVG เป็น PNG ใน C++" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง [**Aposose.Slides สำหรับ C+**](https://products.aspose.com/slides/th/cpp/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ไปยังโปรเจ็กต์ C++ ของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เปิดซอร์สไฟล์ SVG ใน C++
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์เป็นไฟล์ PNG
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="แปลง SVG เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง SVG และบันทึกเป็นรูปแบบไฟล์อื่นๆ ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}