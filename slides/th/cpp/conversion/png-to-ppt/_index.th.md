---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: แปลง PNG เป็น PPT ใน C++
url: /th/cpp/conversion/png-to-ppt/
keywords: แปลง PNG เป็น PPT, PNG เป็น PPT, PowerPoint, PNG, PPT, C++ API, C++ Library
description: แปลง PNG เป็น PPT ใน C++ ใช้ไลบรารี API ของ C++ เพื่อแปลงรูปภาพ PNG เป็น PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="แปลง PNG เป็น PPT ใน C++" h2="C++ API ข้ามแพลตฟอร์มอันทรงพลังสำหรับการแปลง PNG เป็น PPT โดยใช้โค้ด C++" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง PNG เป็น PPT ใน C++" variant="code" %}}

เมื่อใช้ [**Aspose.Slides สำหรับ C+**](https://products.aspose.com/slides/th/cpp/) คุณสามารถแปลงภาพ PNG เป็นงานนำเสนอ PowerPoint โดยใช้โค้ดเพียงไม่กี่บรรทัด:

{{< blocks/products/pf/slides-design-update-10-2026/code title="รหัส C++ สำหรับแปลง PNG เป็น PPT" >}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="แปลง PNG เป็น PPT โดยใช้ Aspose.Slides" %}}

[**Aspose.Slides สำหรับ C++++](https://products.aspose.com/slides/th/cpp/) เป็นไลบรารี C++ ที่มีประสิทธิภาพซึ่งใช้ในการสร้าง แปลง และจัดการงานนำเสนอ PowerPoint, PDF, เอกสาร HTML และอื่นๆ ไฟล์. เมื่อคุณแปลง PNG เป็น PPT คุณกำลังสร้างงานนำเสนอ PowerPoint ที่มีสไลด์ตามรูปภาพ PNG

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="วิธีแปลง PNG เป็น PPT ใน C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ติดตั้ง ** Aspose.Slides สำหรับ C++++ ดู [**การติดตั้ง**](https://docs.aspose.com/slides/cpp/installation/){{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}เพิ่มไลบรารีเป็นข้อมูลอ้างอิงในโครงการของคุณ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}สร้างอินสแตนซ์ของคลาสการนำเสนอ{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}โหลดภาพ PNG ที่คุณต้องการแปลงเป็น PPT{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}บันทึกไฟล์ผลลัพธ์เป็นงานนำเสนอ PPT{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="ตัวแปลงออนไลน์ฟรี"
  description="[วิธีแปลง PPT เป็น HTML ใน Python](https://products.aspose.com/slides/th/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="การแปลง PowerPoint อื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลงไฟล์ในรูปแบบอื่นเป็น PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/th/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
