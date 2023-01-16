---
title: แปลง Image เป็น PDF ใน C++
url: /th/cpp/conversion/image-to-pdf/
keywords: Image เป็น PDF, แปลง Image เป็น PDF, C++ API, C++ Library, Image, PDF
description: แปลง Image เป็น PDF ใน C++ ใช้ C++ library API เพื่อแปลงไฟล์ Image เป็น PDFs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="แปลง Image เป็น PDF ใน C++" h2="ไลบรารี C++ ความเร็วสูงและข้ามแพลตฟอร์มที่ช่วยในการพัฒนาแอปพลิเคชันด้วยความสามารถในการสร้าง รวม ตรวจสอบ หรือแปลงไฟล์งานนำเสนอ Microsoft PowerPoint และ OpenOffice โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Open Office, Adobe PDF" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง Image เป็น PDF ใน C++" %}}

[**Aspose.Slides สำหรับ C++++](https://products.aspose.com/slides/th/cpp/) เป็นไลบรารี C++ ที่ทรงพลังสำหรับการสร้างและจัดการไฟล์งานนำเสนอ นอกจากนี้ ยังมีวิธีที่ยืดหยุ่นในการแปลง Image เป็น PDF เมื่อใช้ **Aspose.Slides สำหรับ C+++** นักพัฒนาหรือแอปพลิเคชันใดๆ ก็สามารถแปลงไฟล์ Image เป็น PDF ด้วยโค้ด C++ เพียงไม่กี่บรรทัด

ในฐานะ API การประมวลผลเอกสารสมัยใหม่ Aspose.Slides สำหรับ C++ จะส่งออกไฟล์ Image เป็นรูปแบบไฟล์ PDF ได้อย่างรวดเร็ว ไลบรารี Aspose PowerPoint ช่วยให้คุณแปลง Image เป็น PDF และรูปแบบไฟล์อื่นๆ อีกมากมาย

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลง Image เป็น PDF โดยใช้ C++" %}}
หากต้องการแปลง Image เป็น PDF คุณจะต้องสร้างงานนำเสนอจากไฟล์ Image และบันทึกเป็น PDF

{{% blocks/products/pf/agp/code-block title="โค้ด C++ สำหรับแปลง Image เป็น PDF" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="วิธีแปลง Image เป็น PDF โดยใช้ Aspose.Slides สำหรับ C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="นี่คือขั้นตอนในการแปลง Image เป็น PDF ใน C++" >}}

{{< blocks/products/pf/agp/step-autogen >}}
ติดตั้ง [**Aposose.Slides สำหรับ C+**](https://products.aspose.com/slides/th/cpp/)
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เพิ่มการอ้างอิงไลบรารี (นำเข้าไลบรารี) ไปยังโปรเจ็กต์ C++ ของคุณ
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
เปิดซอร์สไฟล์ Image ใน C++
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
บันทึกผลลัพธ์เป็นไฟล์ PDF
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="แปลง Image เป็นรูปแบบอื่นที่รองรับ" subTitle="คุณยังสามารถแปลง Image และบันทึกเป็นรูปแบบไฟล์อื่นๆ ดูรูปแบบที่รองรับทั้งหมดด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/th/cpp/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}